# AssemblyExtensions.GetSecurityPermission Method 
 

Gets the SecurityPermissionAttribute (if any) of the source Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static SecurityPermissionAttribute GetSecurityPermission(
	this Assembly sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetSecurityPermission ( 
	sender As Assembly
) As SecurityPermissionAttribute
```

**VB Usage**<br />
``` VB Usage
Dim sender As [Assembly]
Dim returnValue As SecurityPermissionAttribute

returnValue = sender.GetSecurityPermission()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static SecurityPermissionAttribute^ GetSecurityPermission(
	Assembly^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetSecurityPermission : 
        sender : Assembly -> SecurityPermissionAttribute 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: SecurityPermissionAttribute<br />The SecurityPermissionAttribute of the source Assembly.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Assembly. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim securityPermission As SecurityPermissionAttribute = GetSecurityPermission(asm)

Console.WriteLine(securityPermission.Flags.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />