# IThumbnailCache.GetThumbnail Method 
 

Gets a cached thumbnail for a given Shell item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
HResult GetThumbnail(
	IShellItem shellItem,
	uint requestedThumbSize,
	ThumbnailFlags flags,
	out ISharedBitmap refThumb,
	out ThumbnailCacheFlags refOutFlags,
	out ThumbnailId refThumbnailId
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Function GetThumbnail ( 
	shellItem As IShellItem,
	requestedThumbSize As UInteger,
	flags As ThumbnailFlags,
	<OutAttribute> ByRef refThumb As ISharedBitmap,
	<OutAttribute> ByRef refOutFlags As ThumbnailCacheFlags,
	<OutAttribute> ByRef refThumbnailId As ThumbnailId
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IThumbnailCache
Dim shellItem As IShellItem
Dim requestedThumbSize As UInteger
Dim flags As ThumbnailFlags
Dim refThumb As ISharedBitmap
Dim refOutFlags As ThumbnailCacheFlags
Dim refThumbnailId As ThumbnailId
Dim returnValue As HResult

returnValue = instance.GetThumbnail(shellItem, 
	requestedThumbSize, flags, refThumb, 
	refOutFlags, refThumbnailId)
```

**C++**<br />
``` C++
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
HResult GetThumbnail(
	[InAttribute] IShellItem^ shellItem, 
	[InAttribute] unsigned int requestedThumbSize, 
	[InAttribute] ThumbnailFlags flags, 
	[OutAttribute] ISharedBitmap^% refThumb, 
	[OutAttribute] ThumbnailCacheFlags% refOutFlags, 
	[OutAttribute] ThumbnailId% refThumbnailId
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
abstract GetThumbnail : 
        shellItem : IShellItem * 
        requestedThumbSize : uint32 * 
        flags : ThumbnailFlags * 
        refThumb : ISharedBitmap byref * 
        refOutFlags : ThumbnailCacheFlags byref * 
        refThumbnailId : ThumbnailId byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>shellItem</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem</a><br />A pointer to the Shell item for which to retrieve a thumbnail.</dd><dt>requestedThumbSize</dt><dd>Type: System.UInt32<br />The requested thumbnail size in pixels. 

 The maximum value is 1024.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailFlags">DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags</a><br />Specifies options for the extraction and display of a thumbnail image.</dd><dt>refThumb</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">DevCase.Interop.Unmanaged.Win32.Interfaces.ISharedBitmap</a><br />The address of an <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_ISharedBitmap">ISharedBitmap</a> pointer that, when this method returns successfully, receives the object used to access the thumbnail. 

 This parameter may be NULL.</dd><dt>refOutFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailCacheFlags">DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags</a><br />A pointer to a value that, when this method returns successfully, receives a combination of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThumbnailCacheFlags">ThumbnailCacheFlags</a> flags.</dd><dt>refThumbnailId</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ThumbnailId">DevCase.Interop.Unmanaged.Win32.Structures.ThumbnailId</a><br />\[Missing <param name="refThumbnailId"/> documentation for "M:DevCase.Interop.Unmanaged.Win32.Interfaces.IThumbnailCache.GetThumbnail(DevCase.Interop.Unmanaged.Win32.Interfaces.IShellItem,System.UInt32,DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailFlags,DevCase.Interop.Unmanaged.Win32.Interfaces.ISharedBitmap@,DevCase.Interop.Unmanaged.Win32.Enums.ThumbnailCacheFlags@,DevCase.Interop.Unmanaged.Win32.Structures.ThumbnailId@)"\]</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailcache-getthumbnail" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/thumbcache/nf-thumbcache-ithumbnailcache-getthumbnail</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IThumbnailCache">IThumbnailCache Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />