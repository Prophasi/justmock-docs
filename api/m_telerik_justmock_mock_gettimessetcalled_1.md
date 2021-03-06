---
title: GetTimesSetCalled Method (Action, Args)
page_title: GetTimesSetCalled Method (Action, Args) | JustMock Documentation
description: Documentation page about GetTimesSetCalled Method (Action, Args).
previous_url: /m_telerik_justmock_mock_gettimessetcalled_1.html
slug: m_telerik_justmock_mock_gettimessetcalled_1
published: True
fullPath: api/n_telerik_justmock/t_telerik_justmock_mock/methods_t_telerik_justmock_mock/overload_telerik_justmock_mock_gettimessetcalled/m_telerik_justmock_mock_gettimessetcalled_1
category: "api"
---

# Mock.GetTimesSetCalled Method (Action, Args)



Returns the number of times the specified setter or event subscription method was called.


 **Namespace:**  [Telerik.JustMock](n_telerik_justmock) <br> **Assembly:** Telerik.JustMock(in Telerik.JustMock.dll)
## Syntax


<div id="syntaxCodeBlocks" class="code"><span codeLanguage="CSharp"><table><tr><th>C#</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">public</span> <span class="keyword">static</span> <a href="https://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">int</a> <span class="identifier">GetTimesSetCalled</span>(
	<a href="https://msdn2.microsoft.com/en-us/library/bb534741" target="_blank">Action</a> <span class="parameter">action</span>,
	<a href="T_Telerik_JustMock_Args.html">Args</a> <span class="parameter">args</span>
)</pre></td></tr></table></span><span codeLanguage="VisualBasicDeclaration"><table><tr><th>Visual Basic</th></tr><tr><td><pre xml:space="preserve"><span class="keyword">Public</span> <span class="keyword">Shared</span> <span class="keyword">Function</span> <span class="identifier">GetTimesSetCalled</span> ( _
	<span class="parameter">action</span> <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/bb534741" target="_blank">Action</a>, _
	<span class="parameter">args</span> <span class="keyword">As</span> <a href="T_Telerik_JustMock_Args.html">Args</a> _
) <span class="keyword">As</span> <a href="https://msdn2.microsoft.com/en-us/library/td2s409d" target="_blank">Integer</a></pre></td></tr></table></span></div>



action<br>


Type: [System.Action](bb534741) <br>The setter or event subscription method to inspect



args<br>


Type: [Telerik.JustMock.Args](t_telerik_justmock_args) <br>Specifies to ignore the instance and/or arguments during assertion.


Number of calls

## See Also



 [Mock Class](t_telerik_justmock_mock) 

 [Mock Members](allmembers_t_telerik_justmock_mock) 

 [GetTimesSetCalled Overload](overload_telerik_justmock_mock_gettimessetcalled) 

 [Telerik.JustMock Namespace](n_telerik_justmock) 



