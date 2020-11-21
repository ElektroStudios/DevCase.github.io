# AssemblyExtensions.GetEmbeddedResource Method 
 

Gets an embedded resource from the source Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static MemoryStream GetEmbeddedResource(
	this Assembly sender,
	string resourceName
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetEmbeddedResource ( 
	sender As Assembly,
	resourceName As String
) As MemoryStream
```

**VB Usage**<br />
``` VB Usage
Dim sender As [Assembly]
Dim resourceName As String
Dim returnValue As MemoryStream

returnValue = sender.GetEmbeddedResource(resourceName)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static MemoryStream^ GetEmbeddedResource(
	Assembly^ sender, 
	String^ resourceName
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetEmbeddedResource : 
        sender : Assembly * 
        resourceName : string -> MemoryStream 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.Assembly<br />The source Assembly.</dd><dt>resourceName</dt><dd>Type: System.String<br />The resource name.</dd></dl>

#### Return Value
Type: MemoryStream<br />A MemoryStream that contains the raw resource.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Assembly. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentException</td><td>Resource not found with the specified name.;resourceName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim resourceName As String = "MyResources.resx"
Dim targetFilePath As String = Path.Combine("C:\", resourceName)

Using resource As MemoryStream = GetEmbeddedResource(asm, resourceName)
    File.WriteAllBytes(targetFilePath, resource.GetBuffer())
End Using
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Assembly_AssemblyExtensions">AssemblyExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Assembly">DevCase.Core.Extensions.Assembly Namespace</a><br />