# FileUtil.PreloadInThumbnailCache Method 
 

Preloads the thumbnail of a file into Windows Thumbnail Cache system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void PreloadInThumbnailCache(
	string filePath,
	ThumbnailCacheSizes thumbnailSize = ThumbnailCacheSizes._256x256
)
```

**VB**<br />
``` VB
Public Shared Sub PreloadInThumbnailCache ( 
	filePath As String,
	Optional thumbnailSize As ThumbnailCacheSizes = ThumbnailCacheSizes._256x256
)
```

**VB Usage**<br />
``` VB Usage
Dim filePath As String
Dim thumbnailSize As ThumbnailCacheSizesFileUtil.PreloadInThumbnailCache(filePath, 
	thumbnailSize)
```

**C++**<br />
``` C++
public:
static void PreloadInThumbnailCache(
	String^ filePath, 
	ThumbnailCacheSizes thumbnailSize = ThumbnailCacheSizes::_256x256
)
```

**F#**<br />
``` F#
static member PreloadInThumbnailCache : 
        filePath : string * 
        ?thumbnailSize : ThumbnailCacheSizes 
(* Defaults:
        let _thumbnailSize = defaultArg thumbnailSize ThumbnailCacheSizes._256x256
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>filePath</dt><dd>Type: System.String<br />\[Missing <param name="filePath"/> documentation for "M:DevCase.Core.IO.Tools.FileUtil.PreloadInThumbnailCache(System.String,DevCase.Core.Imaging.ThumbnailCacheSizes)"\]</dd><dt>thumbnailSize (Optional)</dt><dd>Type: <a href="T_DevCase_Core_Imaging_ThumbnailCacheSizes">DevCase.Core.Imaging.ThumbnailCacheSizes</a><br />The requested thumbnail size, in pixels. 

 Default value is 256.</dd></dl>

## Remarks
Original idea took from here: <a href="https://github.com/bruhov/WinThumbsPreloader" target="_blank">https://github.com/bruhov/WinThumbsPreloader</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim directoryPath As String = "C:\Images"
Dim searchPattern As String = "*.jpg"
Dim searchOption As SearchOption = SearchOption.TopDirectoryOnly
Dim thumbSize As ThumbnailCacheSizes = ThumbnailCacheSizes._256x256

For Each file As FileInfo In New DirectoryInfo(directoryPath).EnumerateFiles(searchPattern, searchOption)
    Console.WriteLine($"Preloading thumbnail ({CStr(thumbSize)}x{CStr(thumbSize)}) for file: '{file.FullName}'")
    FileUtil.PreloadInThumbnailCache(file.FullName, thumbSize)
Next file
```


## See Also


#### Reference
<a href="T_DevCase_Core_IO_Tools_FileUtil">FileUtil Class</a><br /><a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />