---
title: Mock Multiple Interfaces
page_title: Mock Multiple Interfaces | JustMock Documentation
description: Mock Multiple Interfaces
previous_url: /scenarios-mock-multiple-interfaces.html
slug: justmock/scenarios/mock-multiple-interfaces
tags: mock,multiple,interfaces
published: True
position: 1
---

# Mock Multiple Interfaces

When a mock is created by using `Mock.Create` all dependencies are also implemented. Thus, if you are interested in a specific interface implementation you can use the `as` operator and call the interface members.

Consider the following interface:

  #### __[C#]__

  {{region MockMultipleInterfaces#Sample}}
    public interface IFoo : IDisposable
	{
	    void Do();
	}
  {{endregion}}

The `IFoo` interface has `IDisposable` implemented. When you are interested only in `IDisposable` calls, you need to perform a conversion from the created mock to `IDisposable`.

  #### __[C#]__

  {{region MockMultipleInterfaces#IDisposable}}
    // Arrange
	var foo = Mock.Create<IFoo>();
	var iDisposable = foo as IDisposable;
  {{endregion}}


Finally, check whether the dispose method invokes our mock code successfully.

  #### __[C#]__

  {{region MockMultipleInterfaces#Assert}}
    bool called = false;

	Mock.Arrange(() => iDisposable.Dispose()).DoInstead(() => called = true);
	
	// Act
	iDisposable.Dispose();
	
	// Assert
	Assert.IsTrue(called);
	
	Mock.Assert(() => iDisposable.Dispose(), Occurs.Once());
  {{endregion}}
