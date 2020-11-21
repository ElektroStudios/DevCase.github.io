# IShellItemImageFactoryGetImageFlags Enumeration
 

Specifies icon flags for <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItemImageFactory_GetImage">GetImage(Size, IShellItemImageFactoryGetImageFlags, IntPtr)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum IShellItemImageFactoryGetImageFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration IShellItemImageFactoryGetImageFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItemImageFactoryGetImageFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class IShellItemImageFactoryGetImageFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type IShellItemImageFactoryGetImageFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.ResizeToFit">**ResizeToFit**</td><td>0</td><td>Shrink the bitmap as necessary to fit, preserving its aspect ratio.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.BiggerSizeOk">**BiggerSizeOk**</td><td>1</td><td>Passed by callers if they want to stretch the returned image themselves. 

 For example, if the caller passes an icon size of 80x80, a 96x96 thumbnail could be returned. 

 This action can be used as a performance optimization if the caller expects that they will need to stretch the image. 

 Note that the Shell implementation of <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItemImageFactory">IShellItemImageFactory</a> performs a GDI stretch blit. 

 If the caller wants a higher quality image stretch than provided through that mechanism, they should pass this flag and perform the stretch themselves.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.MemoryOnly">**MemoryOnly**</td><td>2</td><td>Return the item only if it is already in memory. Do not access the disk even if the item is cached. 

 Note that this only returns an already-cached icon and can fall back to a per-class icon if an item has a per-instance icon that has not been cached. 

 Retrieving a thumbnail, even if it is cached, always requires the disk to be accessed, so <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItemImageFactory_GetImage">GetImage(Size, IShellItemImageFactoryGetImageFlags, IntPtr)</a> should not be called from the UI thread without passing MemoryOnly.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.IconOnly">**IconOnly**</td><td>4</td><td>Return only the icon, never the thumbnail.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.ThumbnailOnly">**ThumbnailOnly**</td><td>8</td><td>Return only the thumbnail, never the icon. 

 Note that not all items have thumbnails, so ThumbnailOnly will cause the method to fail in these cases.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.InCacheOnly">**InCacheOnly**</td><td>16</td><td>Allows access to the disk, but only to retrieve a cached item. 

 This returns a cached thumbnail if it is available. 

 If no cached thumbnail is available, it returns a cached per-instance icon but does not extract a thumbnail or icon.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.CropToSquare">**CropToSquare**</td><td>32</td><td>If necessary, crop the bitmap to a square.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.WideThumbnails">**WideThumbnails**</td><td>64</td><td>Stretch and crop the bitmap to a 0.7 aspect ratio.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.IconBackground">**IconBackground**</td><td>128</td><td>If returning an icon, paint a background using the associated app's registered background color.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellItemImageFactoryGetImageFlags.ScaleUp">**ScaleUp**</td><td>256</td><td>If necessary, stretch the bitmap so that the height and width fit the given size.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellitemimagefactory-getimage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-ishellitemimagefactory-getimage</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />