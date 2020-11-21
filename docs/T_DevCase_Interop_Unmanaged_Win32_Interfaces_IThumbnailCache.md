# IThumbnailCache Interface
 

Exposes methods for a system thumbnail cache that is shared across applications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[GuidAttribute("F676C15D-596A-4ce2-8234-33996F445DB1")]
public interface IThumbnailCache
```

**VB**<br />
``` VB
<ComImportAttribute>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<GuidAttribute("F676C15D-596A-4ce2-8234-33996F445DB1")>
Public Interface IThumbnailCache
```

**VB Usage**<br />
``` VB Usage
Dim instance As IThumbnailCache
```

**C++**<br />
``` C++
[ComImportAttribute]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[GuidAttribute(L"F676C15D-596A-4ce2-8234-33996F445DB1")]
public interface class IThumbnailCache
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<GuidAttribute("F676C15D-596A-4ce2-8234-33996F445DB1")>]
type IThumbnailCache =  interface end
```

The IThumbnailCache type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache_GetThumbnail">GetThumbnail</a></td><td>
Gets a cached thumbnail for a given Shell item.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache_GetThumbnailByID">GetThumbnailByID</a></td><td>
Gets a thumbnail from the thumbnail cache, given its ID.</td></tr></table>&nbsp;
<a href="#ithumbnailcache-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nn-thumbcache-ithumbnailcache" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nn-thumbcache-ithumbnailcache</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />