# WebUtil.UserAgents Property 
 

Gets a collection of common user-agents, as is, for testing purposes in web-crawlers.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<string> UserAgents { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property UserAgents As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of String)

value = WebUtil.UserAgents

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<String^>^ UserAgents {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
static member UserAgents : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />The user agents.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Tools_WebUtil">WebUtil Class</a><br /><a href="N_DevCase_Core_NET_Tools">DevCase.Core.NET.Tools Namespace</a><br />