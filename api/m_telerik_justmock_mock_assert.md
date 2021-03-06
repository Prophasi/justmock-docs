---
title: Assert Method (Expression(Action), String)
page_title: Assert Method (Expression(Action), String) | JustMock Documentation
description: Documentation page about Assert Method (Expression(Action), String).
previous_url: /m_telerik_justmock_mock_assert.html
slug: m_telerik_justmock_mock_assert
published: True
fullPath: api/n_telerik_justmock/t_telerik_justmock_mock/methods_t_telerik_justmock_mock/overload_telerik_justmock_mock_assert/m_telerik_justmock_mock_assert
category: "api"
---

# Mock.Assert Method (Expression&lt;Action&gt;, String)



Asserts a specific call from expression.


 **Namespace:**  [Telerik.JustMock](n_telerik_justmock) <br> **Assembly:** Telerik.JustMock(in Telerik.JustMock.dll)
## Syntax


<div id="syntaxCodeBlocks" class="code"><span codeLanguage="CSharp"><table><tr><th>C#</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">public</span> <span class="keyword">static</span> <span class="keyword">void</span> <span class="identifier">Assert</span>(
	<a href="https://msdn2.microsoft.com/en-us/library/bb335710" target="_blank">Expression</a>&lt;<a href="https://msdn2.microsoft.com/en-us/library/bb534741" target="_blank">Action</a>&gt; <span class="parameter">expression</span>,
	<a href="https://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">string</a> <span class="parameter">message</span> = <span class="keyword">null</span>
)</pre></td></tr></table></span><span codeLanguage="VisualBasicDeclaration"><table><tr><th>Visual Basic</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">Public</span> <span class="keyword">Shared</span> <span class="keyword">Sub</span> <span class="identifier">Assert</span> ( _
	<span class="parameter">expression</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/bb335710" target="_blank">Expression</a>(<span class="keyword">Of</span> <a href="https://msdn2.microsoft.com/en-us/library/bb534741" target="_blank">Action</a>), _
	Optional <span class="parameter">message</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a> = <span class="keyword">Nothing</span> _
)</pre></td></tr></table></span></div>



expression<br>


Type: [System.Linq.Expressions.Expression](bb335710) &lt; [Action](bb534741) &gt;<br>Action expression defining the action to verify.



message<br>
(Optional)

Type: [System.String](s1wwdcbf) <br>
[Missing &lt;param name="message"/&gt; documentation for "M:Telerik.JustMock.Mock.Assert(System.Linq.Expressions.Expression{System.Action},System.String)"]





## See Also



 [Mock Class](t_telerik_justmock_mock) 

 [Mock Members](allmembers_t_telerik_justmock_mock) 

 [Assert Overload](overload_telerik_justmock_mock_assert) 

 [Telerik.JustMock Namespace](n_telerik_justmock) 



