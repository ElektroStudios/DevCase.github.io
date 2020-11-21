# DwmWindowAttribute Enumeration
 

Specifies the attribute to set when calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmSetWindowAttribute">DwmSetWindowAttribute(IntPtr, DwmWindowAttribute, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DwmWindowAttribute
```

**VB**<br />
``` VB
Public Enumeration DwmWindowAttribute
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmWindowAttribute
```

**C++**<br />
``` C++
public enum class DwmWindowAttribute
```

**F#**<br />
``` F#
type DwmWindowAttribute
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.NcRenderingEnabled">**NcRenderingEnabled**</td><td>1</td><td>Is non-client rendering enabled/disabled.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.NcRenderingPolicy">**NcRenderingPolicy**</td><td>2</td><td>Non-client rendering policy.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.TransitionsForceDisabled">**TransitionsForceDisabled**</td><td>3</td><td>Potentially enable/forcibly disable transitions.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.AllowNcPaint">**AllowNcPaint**</td><td>4</td><td>Allow contents rendered In the non-client area To be visible On the DWM-drawn frame.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.CaptionButtonBounds">**CaptionButtonBounds**</td><td>5</td><td>Bounds Of the caption button area In window-relative space.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.NonClientRtlLayout">**NonClientRtlLayout**</td><td>6</td><td>Set the non-client content RTL mirrored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.ForceIconicRepresentation">**ForceIconicRepresentation**</td><td>7</td><td>Force this window To display iconic thumbnails.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.Flip3DPolicy">**Flip3DPolicy**</td><td>8</td><td>Designates how Flip3D will treat the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.ExtendedFrameBounds">**ExtendedFrameBounds**</td><td>9</td><td>Gets the extended frame bounds rectangle In screen space.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.HasIconicBitmap">**HasIconicBitmap**</td><td>10</td><td>Indicates an available bitmap When there Is no better thumbnail representation.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.DisallowPeek">**DisallowPeek**</td><td>11</td><td>Don't invoke Peek on the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.ExcludedFromPeek">**ExcludedFromPeek**</td><td>12</td><td>Set LivePreview exclusion information.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.Cloak">**Cloak**</td><td>13</td><td>Cloaks or uncloaks the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.Cloaked">**Cloaked**</td><td>14</td><td>Gets the cloaked state Of the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute.FreezeRepresentation">**FreezeRepresentation**</td><td>15</td><td>Force this window To freeze the thumbnail without live update.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762108(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762108(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />