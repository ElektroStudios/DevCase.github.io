# DirectoryInfoExtensions.ExtractIcon Method 
 

Extracts the icon associated for the source directory.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Bitmap ExtractIcon(
	this DirectoryInfo directory,
	IconSizes iconSize = IconSizes._256x256
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ExtractIcon ( 
	directory As DirectoryInfo,
	Optional iconSize As IconSizes = IconSizes._256x256
) As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim directory As DirectoryInfo
Dim iconSize As IconSizes
Dim returnValue As Bitmap

returnValue = directory.ExtractIcon(iconSize)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Bitmap^ ExtractIcon(
	DirectoryInfo^ directory, 
	IconSizes iconSize = IconSizes::_256x256
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ExtractIcon : 
        directory : DirectoryInfo * 
        ?iconSize : IconSizes 
(* Defaults:
        let _iconSize = defaultArg iconSize IconSizes._256x256
*)
-> Bitmap 

```


#### Parameters
&nbsp;<dl><dt>directory</dt><dd>Type: System.IO.DirectoryInfo<br />The source DirectoryInfo.</dd><dt>iconSize (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Imaging_IconSizes">DevCase.Core.Imaging.IconSizes</a><br />The icon size to extract. 

 Default value is <a href="T_DevCase_Core_Imaging_IconSizes">_256x256</a></dd></dl>

#### Return Value
Type: Bitmap<br />The resulting icon.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type DirectoryInfo. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim dir As New DirectoryInfo("C:\Windows")
Dim bmp As Bitmap = ExtractIcon(dir)
PictureBox1.BackgroundImage = bmp
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_DirectoryInfo_DirectoryInfoExtensions">DirectoryInfoExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_DirectoryInfo">DevCase.Core.Extensions.DirectoryInfo Namespace</a><br />