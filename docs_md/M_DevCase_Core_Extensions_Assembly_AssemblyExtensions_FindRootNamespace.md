# AssemblyExtensions.FindRootNamespace Method 
 

Tries to detect the root namespace name of the source Assembly. 

 Note that an assembly does not necessarily should have defined a root namespace, and also FindRootNamespace(Assembly) could return a wrong root namespace name in some circumstances.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static XNamespace FindRootNamespace(
	this Assembly sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function FindRootNamespace ( 
	sender As Assembly
) As XNamespace
```

**VB Usage**<br />
``` VB Usage
Dim sender As [Assembly]
Dim returnValue As XNamespace

returnValue = sender.FindRootNamespace()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static XNamespace^ FindRootNamespace(
	Assembly^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member FindRootNamespace : 
        sender : Assembly -> XNamespace 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd></dl>

#### Return Value
Type: XNamespace<br />The resulting XNamespace. 

 If the root namespace is not found, the return value is None.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Assembly. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim ns As XNamespace = TryGetRootNamespace(asm)

If (ns = XNamespace.None) Then
    Console.WriteLine("Root namespace not found.")
Else
    Console.WriteLine(String.Format("Root namespace name: {0}", ns.NamespaceName))
End If
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />