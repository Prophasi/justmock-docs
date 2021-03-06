---
title: AssertSet Method (Action, Args, Occurs, String)
page_title: AssertSet Method (Action, Args, Occurs, String) | JustMock Documentation
description: Documentation page about AssertSet Method (Action, Args, Occurs, String).
previous_url: /m_telerik_justmock_mock_assertset_2.html
slug: m_telerik_justmock_mock_assertset_2
published: True
fullPath: api/n_telerik_justmock/t_telerik_justmock_mock/methods_t_telerik_justmock_mock/overload_telerik_justmock_mock_assertset/m_telerik_justmock_mock_assertset_2
category: "api"
---

# Mock.AssertSet Method (Action, Args, Occurs, String)



Asserts the specific property set operation.


 **Namespace:**  [Telerik.JustMock](n_telerik_justmock) <br> **Assembly:** Telerik.JustMock(in Telerik.JustMock.dll)
## Syntax


<div id="syntaxCodeBlocks" class="code"><span codeLanguage="CSharp"><table><tr><th>C#</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">public</span> <span class="keyword">static</span> <span class="keyword">void</span> <span class="identifier">AssertSet</span>(
	<a href="https://msdn2.microsoft.com/en-us/library/bb534741" target="_blank">Action</a> <span class="parameter">action</span>,
	<a href="T_Telerik_JustMock_Args.html">Args</a> <span class="parameter">args</span>,
	<a href="T_Telerik_JustMock_Occurs.html">Occurs</a> <span class="parameter">occurs</span>,
	<a href="https://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">string</a> <span class="parameter">message</span> = <span class="keyword">null</span>
)</pre></td></tr></table></span><span codeLanguage="VisualBasicDeclaration"><table><tr><th>Visual Basic</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">Public</span> <span class="keyword">Shared</span> <span class="keyword">Sub</span> <span class="identifier">AssertSet</span> ( _
	<span class="parameter">action</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/bb534741" target="_blank">Action</a>, _
	<span class="parameter">args</span> <span class="keyword">As</span> <a href="T_Telerik_JustMock_Args.html">Args</a>, _
	<span class="parameter">occurs</span> <span class="keyword">As</span> <a href="T_Telerik_JustMock_Occurs.html">Occurs</a>, _
	Optional <span class="parameter">message</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> = <span class="keyword">Nothing</span> _
)</pre></td></tr></table></span></div>



action<br>


Type: [System.Action](bb534741) <br>Action defining the set operation



args<br>


Type: [Telerik.JustMock.Args](t_telerik_justmock_args) <br>Specifies to ignore the instance and/or arguments during assertion.



occurs<br>


Type: [Telerik.JustMock.Occurs](t_telerik_justmock_occurs) <br>Specifies the number of times a mock call should occur.



message<br>
(Optional)

Type: [System.String](s1wwdcbf) <br>
[Missing &lt;param name="message"/&gt; documentation for "M:Telerik.JustMock.Mock.AssertSet(System.Action,Telerik.JustMock.Args,Telerik.JustMock.Occurs,System.String)"]





## See Also



 [Mock Class](t_telerik_justmock_mock) 

 [Mock Members](allmembers_t_telerik_justmock_mock) 

 [AssertSet Overload](overload_telerik_justmock_mock_assertset) 

 [Telerik.JustMock Namespace](n_telerik_justmock) 



