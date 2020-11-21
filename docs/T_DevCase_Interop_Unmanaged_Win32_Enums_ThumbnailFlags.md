# ThumbnailFlags Enumeration
 

Specifies options for the extraction and display of a thumbnail image. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache_GetThumbnail">GetThumbnail(IShellItem, UInt32, ThumbnailFlags, ISharedBitmap, ThumbnailCacheFlags, ThumbnailId)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ThumbnailFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ThumbnailFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ThumbnailFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ThumbnailFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ThumbnailFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.Extract">**Extract**</td><td>0</td><td>Extract the thumbnail if it is not cached.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.InCacheOnly">**InCacheOnly**</td><td>1</td><td>Only return the thumbnail if it is cached.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.FastExtract">**FastExtract**</td><td>2</td><td>If not cached, only extract the thumbnail if it is embedded in EXIF format, typically 96x96.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.ForceExtract">**ForceExtract**</td><td>4</td><td>Ignore cache and extract thumbnail from source file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.SlowReclaim">**SlowReclaim**</td><td>8</td><td>The thumbnail has an extended lifetime. Use for volumes that might go offline, like non-fixed disks.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.ExtractDoNotcache">**ExtractDoNotcache**</td><td>32</td><td>Extract but do not add the thumbnail to the cache.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.ScaleForRequestedSize">**ScaleForRequestedSize**</td><td>64</td><td>If the specific thumbnail size requested in the `requestedThumbSize` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache_GetThumbnail">GetThumbnail(IShellItem, UInt32, ThumbnailFlags, ISharedBitmap, ThumbnailCacheFlags, ThumbnailId)</a> function is not available, resize the thumbnail to the requested size. 

 If possible, a larger bitmap is reduced in scale, preserving its aspect ratio, to the width and height required. 

 If the only available cached thumbnail is smaller than the requested size, then it is scaled up using the nearest-neighbor algorithm.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.SkipFastExtract">**SkipFastExtract**</td><td>128</td><td>Do not extract a thumbnail embedded in the metadata of an EXIF image.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.ExtractInProc">**ExtractInProc**</td><td>256</td><td>Ensures that the thumbnail handler is loaded in the same process as the caller. 

 When this flag is not specified, the handler is loaded into a surrogate process to protect the caller from unexpected crashes caused by the processing of the target file. 

 Use this value when debugging thumbnail extractors.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.CropToSquare">**CropToSquare**</td><td>512</td><td>If necessary, crop the bitmap's dimensions so that is square. 

 The length of the shortest side becomes the length of all sides.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.InstanceSurrogate">**InstanceSurrogate**</td><td>1024</td><td>Create a surrogate for this instance of the cache rather than using the shared DLLHost surrogate.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.RequireSurrogate">**RequireSurrogate**</td><td>2048</td><td>Require extractions to take place in the surrogate.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.AppStyle">**AppStyle**</td><td>8192</td><td>Pass the WTSCF_APPSTYLE flag to IThumbnailSettings::SetContext, if the provider supports it.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.WideThumbnails">**WideThumbnails**</td><td>16384</td><td>Stretch and crop the bitmap so that its height is 0.7 times its width.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.IdealCacheSizeOnly">**IdealCacheSizeOnly**</td><td>32768</td><td>Return from the ideal cache snap size only. 

 The returned image might be larger, but it will be pulled from the correct cache entry.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags.ScaleUp">**ScaleUp**</td><td>65536</td><td>If necessary, stretch the image so that the height and width fit the given size.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/ne-thumbcache-wts_flags" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/ne-thumbcache-wts_flags</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />