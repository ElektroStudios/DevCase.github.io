# IThumbnailCache.GetThumbnailByID Method 
 

Gets a thumbnail from the thumbnail cache, given its ID.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
void GetThumbnailByID(
	ThumbnailId thumbnailId,
	uint requestedThumbSize,
	out ISharedBitmap refThumb,
	out ThumbnailCacheFlags refOutFlags
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Sub GetThumbnailByID ( 
	thumbnailId As ThumbnailId,
	requestedThumbSize As UInteger,
	<OutAttribute> ByRef refThumb As ISharedBitmap,
	<OutAttribute> ByRef refOutFlags As ThumbnailCacheFlags
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IThumbnailCache
Dim thumbnailId As ThumbnailId
Dim requestedThumbSize As UInteger
Dim refThumb As ISharedBitmap
Dim refOutFlags As ThumbnailCacheFlags

instance.GetThumbnailByID(thumbnailId, 
	requestedThumbSize, refThumb, refOutFlags)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
void GetThumbnailByID(
	[InAttribute] ThumbnailId thumbnailId, 
	[InAttribute] unsigned int requestedThumbSize, 
	[OutAttribute] ISharedBitmap^% refThumb, 
	[OutAttribute] ThumbnailCacheFlags% refOutFlags
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract GetThumbnailByID : 
        thumbnailId : ThumbnailId * 
        requestedThumbSize : uint32 * 
        refThumb : ISharedBitmap byref * 
        refOutFlags : ThumbnailCacheFlags byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>thumbnailId</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ThumbnailId">DevCase.Interop.Unmanaged.Win32.Structures.ThumbnailId</a><br />\[Missing <param name="thumbnailId"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IThumbnailCache.GetThumbnailByID(DevCase.Interop.Unmanaged.Win32.Structures.ThumbnailId,System.UInt32,DevCase.Interop.Unmanaged.Win32.Interfaces.ISharedBitmap@,DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags@)"\]</dd><dt>requestedThumbSize</dt><dd>Type: System.UInt32<br />The requested thumbnail size in pixels. 

 This value cannot be larger than 1024.</dd><dt>refThumb</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">DevCase.Interop.Unmanaged.Win32.Interfaces.ISharedBitmap</a><br />The address of a <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> interface pointer that, when this method returns successfully, receives the object for accessing the requested thumbnail. 

 This parameter can be NULL.</dd><dt>refOutFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailCacheFlags">DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags</a><br />A pointer to a value that, when this method returns successfully, receives a combination of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailCacheFlags">ThumbnailCacheFlags</a> flags. 

 This value can be set to NULL if this information is not needed.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailcache-getthumbnailbyid" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailcache-getthumbnailbyid</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache">IThumbnailCache Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />