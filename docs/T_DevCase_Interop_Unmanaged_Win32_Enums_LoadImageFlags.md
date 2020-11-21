# LoadImageFlags Enumeration
 

Flags that determines how the image is loaded by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadImage">LoadImage(IntPtr, String, LoadImageType, Int32, Int32, LoadImageFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum LoadImageFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration LoadImageFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As LoadImageFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class LoadImageFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type LoadImageFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.CreateDibSection">**CreateDibSection**</td><td>8192</td><td>When the uType parameter specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_LoadImageType">Bitmap</a>, causes the function to return a `DIB` section bitmap rather than a compatible bitmap. 

 This flag is useful for loading a bitmap without mapping it to the colors of the display device.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.DefaultColor">**DefaultColor**</td><td>0</td><td>The default flag; it does nothing. 

 All it means is "not Monochrome".</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.DefaultSize">**DefaultSize**</td><td>64</td><td>Uses the width or height specified by the system metric values for cursors or icons, if the `width` or `height` parameters are set to zero. 

 If this flag is not specified and `width` or `height` parameters are set to zero, the function uses the actual resource size. 

 If the resource contains multiple images, the function uses the size of the first image.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.LoadFromFile">**LoadFromFile**</td><td>16</td><td>Loads the stand-alone image from the file specified by `name` parameter (icon, cursor, or bitmap file).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.LoadMap3DColors">**LoadMap3DColors**</td><td>4096</td><td>Searches the color table for the image and replaces the following shades of gray with the corresponding 3-D color.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.LoadTransparent">**LoadTransparent**</td><td>32</td><td>Retrieves the color value of the first pixel in the image and replaces the corresponding entry in the color table with the default window color (`COLOR_WINDOW`). 

 All pixels in the image that use that entry become the default window color. 

 This value applies only to images that have corresponding color tables. 

 Do not use this option if you are loading a bitmap with a color depth greater than 8bpp.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.Monochrome">**Monochrome**</td><td>1</td><td>Loads the image in black and white.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.Shared">**Shared**</td><td>32768</td><td>Shares the image handle if the image is loaded multiple times. 

 If Shared is not set, a second call to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadImage">LoadImage(IntPtr, String, LoadImageType, Int32, Int32, LoadImageFlags)</a> for the same resource will load the image again and return a different handle. 

 When you use this flag, the system will destroy the resource when it is no longer needed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.LoadImageFlags.VGAColor">**VGAColor**</td><td>128</td><td>Uses true VGA colors.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648045%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648045%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />