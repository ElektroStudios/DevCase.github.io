# Get.GetThumbnail Method 
 

Gets the thumbnail image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_SearchResult">DevCase.ThirdParty.Google.Youtube.Extensions.SearchResult</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image GetThumbnail(
	this SearchResult sender,
	ThumbnailQuality quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetThumbnail ( 
	sender As SearchResult,
	quality As ThumbnailQuality
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As SearchResult
Dim quality As ThumbnailQuality
Dim returnValue As Image

returnValue = sender.GetThumbnail(quality)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static Image^ GetThumbnail(
	SearchResult^ sender, 
	ThumbnailQuality quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetThumbnail : 
        sender : SearchResult * 
        quality : ThumbnailQuality -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: SearchResult<br />The source SearchResult.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Youtube_ThumbnailQuality">DevCase.ThirdParty.Google.Youtube.ThumbnailQuality</a><br />\[Missing <param name="quality"/> documentation for "M:DevCase.ThirdParty.Google.Youtube.Extensions.SearchResult.Get.GetThumbnail(Google.Apis.YouTube.v3.Data.SearchResult,DevCase.ThirdParty.Google.Youtube.ThumbnailQuality)"\]</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SearchResult. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim item As SearchResult = ...
Dim img As Image = item.GetThumbnail(ThumbnailQuality.Standard)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_Extensions_SearchResult_Get">Get Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_SearchResult">DevCase.ThirdParty.Google.Youtube.Extensions.SearchResult Namespace</a><br />