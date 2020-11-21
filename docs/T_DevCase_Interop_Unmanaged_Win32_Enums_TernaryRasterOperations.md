# TernaryRasterOperations Enumeration
 

Specifies a raster-operation code. 

 These codes define how the color data for the source rectangle is to be combined with the color data for the destination rectangle to achieve the final color.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum TernaryRasterOperations
```

**VB**<br />
``` VB
Public Enumeration TernaryRasterOperations
```

**VB Usage**<br />
``` VB Usage
Dim instance As TernaryRasterOperations
```

**C++**<br />
``` C++
public enum class TernaryRasterOperations
```

**F#**<br />
``` F#
type TernaryRasterOperations
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.SrcCopy">**SrcCopy**</td><td>13369376</td><td>[ Destination = Source ] 

 Copies the source rectangle directly to the destination rectangle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.SrcPaint">**SrcPaint**</td><td>15597702</td><td>[ Destination = Source OR Destination ] 

 Combines the colors of the source and destination rectangles by using the Boolean OR operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.SrcAnd">**SrcAnd**</td><td>8913094</td><td>[ Destination = Source AND Destination ] 

 Combines the colors of the source and destination rectangles by using the Boolean AND operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.SrcInvert">**SrcInvert**</td><td>6684742</td><td>[ Destination = Source XOR Destination ] 

 Combines the colors of the source and destination rectangles by using the Boolean XOR operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.SrcErase">**SrcErase**</td><td>4457256</td><td>[ Destination = Source AND NOT Destination ] 

 Combines the colors of the source and destination rectangles by using the Boolean OR operator and then inverts the resultant color.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.NotSrcCopy">**NotSrcCopy**</td><td>3342344</td><td>[ Destination = NOT Source ] 

 Copies the inverted source rectangle to the destination.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.NotSrcErase">**NotSrcErase**</td><td>1114278</td><td>[ Destination = NOT Source AND NOT Destinatio) ] 

 Combines the colors of the source and destination rectangles by using the Boolean OR operator and then inverts the resultant color.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.MergeCopy">**MergeCopy**</td><td>12583114</td><td>[ Destination = Source AND Pattern) ] 

 Merges the colors of the source rectangle with the brush currently selected in hdcDest, by using the Boolean AND operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.MergePaint">**MergePaint**</td><td>12255782</td><td>[ Destination = NOT Source OR Destination ] 

 Merges the colors of the inverted source rectangle with the colors of the destination rectangle by using the Boolean OR operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.PatCopy">**PatCopy**</td><td>15728673</td><td>[ Destination = Pattern ] 

 Copies the brush currently selected in hdcDest, into the destination bitmap.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.PatPaint">**PatPaint**</td><td>16452105</td><td>[ Destination = DPSnoo ] 

 Combines the colors of the brush currently selected in hdcDest, with the colors of the inverted source rectangle by using the Boolean OR operator. 

 The result of this operation is combined with the colors of the destination rectangle by using the Boolean OR operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.PatInvert">**PatInvert**</td><td>5898313</td><td>[ Destination = Pattern XOR Destination ] 

 Combines the colors of the brush currently selected in hdcDest, with the colors of the destination rectangle by using the Boolean XOR operator.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.DstInvert">**DstInvert**</td><td>5570569</td><td>[ Destination = NOT Destination ] 

 Inverts the destination rectangle.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.Blackness">**Blackness**</td><td>66</td><td>[ Destination = BLACK ] 

 Fills the destination rectangle using the color associated with index 0 in the physical palette. 

 (This color is black for the default physical palette).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.Whiteness">**Whiteness**</td><td>16711778</td><td>[ Destination = WHITE ] 

 Fills the destination rectangle using the color associated with index 1 in the physical palette. 

 (This color is white for the default physical palette).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.CaptureBlt">**CaptureBlt**</td><td>1073741824</td><td>Capture window as seen on screen. 

 This includes layered windows such as WPF windows with AllowsTransparency="True"</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.TernaryRasterOperations.NoMirrorBitmap">**NoMirrorBitmap**</td><td>-2147483648</td><td>Prevents the bitmap from being mirrored.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd183370%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd183370%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />