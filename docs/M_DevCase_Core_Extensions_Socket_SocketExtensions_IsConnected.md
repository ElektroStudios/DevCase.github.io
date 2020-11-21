# SocketExtensions.IsConnected Method 
 

Determines whether the source Socket has a connection established.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Socket">DevCase.Core.Extensions.Socket</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static bool IsConnected(
	this Socket sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function IsConnected ( 
	sender As Socket
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim sender As Socket
Dim returnValue As Boolean

returnValue = sender.IsConnected()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static bool IsConnected(
	Socket^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member IsConnected : 
        sender : Socket -> bool 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Net.Sockets.Socket<br />The source Socket.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the Socket has a connection established; otherwise, `false` (`False` in Visual Basic).

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Socket. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Socket_SocketExtensions">SocketExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Socket">DevCase.Core.Extensions.Socket Namespace</a><br />