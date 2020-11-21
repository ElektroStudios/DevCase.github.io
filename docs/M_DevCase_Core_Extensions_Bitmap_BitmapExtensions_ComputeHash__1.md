# BitmapExtensions.ComputeHash(*T*) Method 
 

Computes a hash code for the source Bitmap.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ComputeHash<T>(
	this Bitmap sender
)
where T : HashAlgorithm

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ComputeHash(Of T As HashAlgorithm) ( 
	sender As Bitmap
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Bitmap
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
	Bitmap^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ComputeHash : 
        sender : Bitmap -> string  when 'T : HashAlgorithm

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Drawing.Bitmap<br />The source Bitmap.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.Bitmap.BitmapExtensions.ComputeHash``1(System.Drawing.Bitmap)"\]</dd></dl>

#### Return Value
Type: String<br />An Hexadecimal representation of the resulting hash code.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Bitmap. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim bmp As Bitmap = Image.FromFile("C:\File.png")
Dim hash As String = bmp.ComputeHash(Of MD5CryptoServiceProvider)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Bitmap_BitmapExtensions">BitmapExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Bitmap">DevCase.Core.Extensions.Bitmap Namespace</a><br />