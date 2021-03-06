---
title: Create Method (String, Action(IFluentConfig))
page_title: Create Method (String, Action(IFluentConfig)) | JustMock Documentation
description: Documentation page about Create Method (String, Action(IFluentConfig)).
previous_url: /m_telerik_justmock_mock_create_1.html
slug: m_telerik_justmock_mock_create_1
published: True
fullPath: api/n_telerik_justmock/t_telerik_justmock_mock/methods_t_telerik_justmock_mock/overload_telerik_justmock_mock_create/m_telerik_justmock_mock_create_1
category: "api"
---

# Mock.Create Method (String, Action&lt;IFluentConfig&gt;)



Creates a mocked instance from an internal class.


 **Namespace:**  [Telerik.JustMock](n_telerik_justmock) <br> **Assembly:** Telerik.JustMock(in Telerik.JustMock.dll)
## Syntax


<div id="syntaxCodeBlocks" class="code"><span codeLanguage="CSharp"><table><tr><th>C#</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">public</span> <span class="keyword">static</span> <a href="https://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a> <span class="identifier">Create</span>(
	<a href="https://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">string</a> <span class="parameter">fullName</span>,
	<a href="https://msdn2.microsoft.com/en-us/library/018hxwa8" target="_blank">Action</a>&lt;<span class="nolink">IFluentConfig</span>&gt; <span class="parameter">settings</span>
)</pre></td></tr></table></span><span codeLanguage="VisualBasicDeclaration"><table><tr><th>Visual Basic</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">Public</span> <span class="keyword">Shared</span> <span class="keyword">Function</span> <span class="identifier">Create</span> ( _
	<span class="parameter">fullName</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/s1wwdcbf" target="_blank">String</a>, _
	<span class="parameter">settings</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/018hxwa8" target="_blank">Action</a>(<span class="keyword">Of</span> <span class="nolink">IFluentConfig</span>) _
) <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/e5kfa45b" target="_blank">Object</a></pre></td></tr></table></span></div>



fullName<br>


Type: [System.String](s1wwdcbf) <br>Fully qualified name of the target type.



settings<br>


Type: [System.Action](018hxwa8) &lt;IFluentConfig&gt;<br>Settings for the mock


Mock instance

## See Also



 [Mock Class](t_telerik_justmock_mock) 

 [Mock Members](allmembers_t_telerik_justmock_mock) 

 [Create Overload](overload_telerik_justmock_mock_create) 

 [Telerik.JustMock Namespace](n_telerik_justmock) 



