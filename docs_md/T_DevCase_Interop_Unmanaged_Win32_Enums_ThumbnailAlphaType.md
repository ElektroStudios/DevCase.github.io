# ThumbnailAlphaType Enumeration
 

Specifies the alpha channel type of a thumbnail image.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ThumbnailAlphaType
```

**VB**<br />
``` VB
Public Enumeration ThumbnailAlphaType
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThumbnailAlphaType
```

**C++**<br />
``` C++
public enum class ThumbnailAlphaType
```

**F#**<br />
``` F#
type ThumbnailAlphaType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailAlphaType.Unknown">**Unknown**</td><td>0</td><td>The bitmap is an unknown format. The Shell tries nonetheless to detect whether the image has an alpha channel.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailAlphaType.RGB">**RGB**</td><td>1</td><td>The bitmap is an RGB image without alpha. The alpha channel is invalid and the Shell ignores it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailAlphaType.ARGB">**ARGB**</td><td>2</td><td>The bitmap is an ARGB image with a valid alpha channel.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailprovider-getthumbnail" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailprovider-getthumbnail</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />