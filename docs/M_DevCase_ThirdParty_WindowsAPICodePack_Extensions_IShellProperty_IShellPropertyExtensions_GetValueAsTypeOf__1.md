# IShellPropertyExtensions.GetValueAsTypeOf(*T*) Method 
 

Gets the value of the specified IShellProperty as a normalized String and then convert that string to the specified type.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_WindowsAPICodePack_Extensions_IShellProperty">DevCase.ThirdParty.WindowsAPICodePack.Extensions.IShellProperty</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static T GetValueAsTypeOf<T>(
	this IShellProperty sender
)

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetValueAsTypeOf(Of T) ( 
	sender As IShellProperty
) As T
```

**VB Usage**<br />
``` VB Usage
Dim sender As IShellProperty
Dim returnValue As T

returnValue = sender.GetValueAsTypeOf()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
static T GetValueAsTypeOf(
	IShellProperty^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetValueAsTypeOf : 
        sender : IShellProperty -> 'T 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: IShellProperty<br />The source IShellProperty.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.ThirdParty.WindowsAPICodePack.Extensions.IShellProperty.IShellPropertyExtensions.GetValueAsTypeOf``1(Microsoft.WindowsAPICodePack.Shell.PropertySystem.IShellProperty)"\]</dd></dl>

#### Return Value
Type: *T*<br />The resulting value.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type IShellProperty. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As ShellObject = ShellObject.FromParsingName("C:\Image.jpg")
Dim prop As IShellProperty = img.Properties.GetProperty(SystemProperties.System.Image.VerticalSize)
Dim propValue As String = GetValueAsTypeOf(Of Integer)(prop)

Console.WriteLine(propValue)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_WindowsAPICodePack_Extensions_IShellProperty_IShellPropertyExtensions">IShellPropertyExtensions Class</a><br /><a href="N_DevCase_ThirdParty_WindowsAPICodePack_Extensions_IShellProperty">DevCase.ThirdParty.WindowsAPICodePack.Extensions.IShellProperty Namespace</a><br />