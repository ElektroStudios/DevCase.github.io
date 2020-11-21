# ISharedBitmap Interface
 

Exposes memory-efficient methods for accessing bitmaps. 

 This interface is used as a thin wrapper around HBITMAP objects, allowing those objects to be reference counted and protected from having their underlying data changed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("091162a4-bc96-411f-aae8-c5122cd03363")]
public interface ISharedBitmap
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("091162a4-bc96-411f-aae8-c5122cd03363")>
Public Interface ISharedBitmap
```

**VB Usage**<br />
``` VB Usage
Dim instance As ISharedBitmap
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"091162a4-bc96-411f-aae8-c5122cd03363")]
public interface class ISharedBitmap
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("091162a4-bc96-411f-aae8-c5122cd03363")>]
type ISharedBitmap =  interface end
```

The ISharedBitmap type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_Detach">Detach</a></td><td>
Retrieves the bitmap contained in an ISharedBitmap object, and returns a copy if the contained bitmap resides in shared memory. 

 After calling this method the bitmap is no longer associated with this ISharedBitmap object and you cannot call <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSharedBitmap">GetSharedBitmap(IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_Detach">Detach(IntPtr)</a> on it again.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetFormat">GetFormat</a></td><td>
Retrieves the alpha type of the bitmap image..</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSharedBitmap">GetSharedBitmap</a></td><td>
Retrieves the bitmap contained in an ISharedBitmap object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_GetSize">GetSize</a></td><td>
Retrieves the size of the bitmap contained in an ISharedBitmap object.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap_InitializeBitmap">InitializeBitmap</a></td><td>
Initializes a new ISharedBitmap object with a given bitmap.</td></tr></table>&nbsp;
<a href="#isharedbitmap-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nn-thumbcache-isharedbitmap" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nn-thumbcache-isharedbitmap</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />