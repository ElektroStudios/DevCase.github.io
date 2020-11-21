# ThumbnailCacheFlags Enumeration
 

Specifies cache options for the extraction and display of a thumbnail image. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache_GetThumbnail">GetThumbnail(IShellItem, UInt32, ThumbnailFlags, ISharedBitmap, ThumbnailCacheFlags, ThumbnailId)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ThumbnailCacheFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ThumbnailCacheFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThumbnailCacheFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ThumbnailCacheFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ThumbnailCacheFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags.Default">**Default**</td><td>0</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags.LowQuality">**LowQuality**</td><td>1</td><td>Set when the returned bitmap dimensions are less than the value specified in `requestedThumbSize` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache_GetThumbnail">GetThumbnail(IShellItem, UInt32, ThumbnailFlags, ISharedBitmap, ThumbnailCacheFlags, ThumbnailId)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags.Cached">**Cached**</td><td>2</td><td>Set when the returned image is in the cache.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/es-es/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailcache-getthumbnail" target="_blank">https://docs.microsoft.com/es-es/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailcache-getthumbnail</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />