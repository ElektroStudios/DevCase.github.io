# ImageExtensions.ComputeHash(*T*) Method 
 

Computes a hash code for the source Image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ComputeHash<T>(
	this Image sender
)
where T : HashAlgorithm

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ComputeHash(Of T As HashAlgorithm) ( 
	sender As Image
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Image
Dim returnValue As String

returnValue = sender.ComputeHash()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : HashAlgorithm
static String^ ComputeHash(
	Image^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ComputeHash : 
        sender : Image -> string  when 'T : HashAlgorithm

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Image<br />The source Image.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.Image.ImageExtensions.ComputeHash``1(System.Drawing.Image)"\]</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting hash code.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Image. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = Image.FromFile("C:\File.png")
Dim hash As String = img.ComputeHash(Of MD5CryptoServiceProvider)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Image_ImageExtensions">ImageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Image">DevCase.Core.Extensions.Image Namespace</a><br />