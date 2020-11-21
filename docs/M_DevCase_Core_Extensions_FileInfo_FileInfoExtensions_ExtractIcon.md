# FileInfoExtensions.ExtractIcon Method 
 

Extracts the icon associated for the source file. 

 Note: the maximum size of the returned icon only can be 32x32.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ExtractIcon(
	this FileInfo file,
	IconSizes iconSize = IconSizes._256x256
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExtractIcon ( 
	file As FileInfo,
	Optional iconSize As IconSizes = IconSizes._256x256
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim file As FileInfo
Dim iconSize As IconSizes
Dim returnValue As Bitmap

returnValue = file.ExtractIcon(iconSize)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ExtractIcon(
	FileInfo^ file, 
	IconSizes iconSize = IconSizes::_256x256
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExtractIcon : 
        file : FileInfo * 
        ?iconSize : IconSizes 
(* Defaults:
        let _iconSize = defaultArg iconSize IconSizes._256x256
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.IO.FileInfo<br />The source FileInfo.</dd><dt>iconSize (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Imaging_IconSizes">DevCase.Core.Imaging.IconSizes</a><br />The icon size to extract. 

 Default value is <a href="T_DevCase_Core_Imaging_IconSizes">_256x256</a></dd></dl>

#### Return Value
Type: Bitmap<br />The resulting icon.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type FileInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim file As New FileInfo("C:\File.ext")
Dim bmp As Bitmap = ExtractIcon(file)
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_FileInfo_FileInfoExtensions">FileInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_FileInfo">DevCase.Core.Extensions.FileInfo Namespace</a><br />