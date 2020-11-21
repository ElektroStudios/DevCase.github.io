# Get.GetThumbnail Method 
 

Gets the playlist item's thumbnail image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_PlaylistItem">DevCase.ThirdParty.Google.Youtube.Extensions.PlaylistItem</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static Image GetThumbnail(
	this PlaylistItem sender,
	ThumbnailQuality quality
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetThumbnail ( 
	sender As PlaylistItem,
	quality As ThumbnailQuality
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim sender As PlaylistItem
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
	PlaylistItem^ sender, 
	ThumbnailQuality quality
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetThumbnail : 
        sender : PlaylistItem * 
        quality : ThumbnailQuality -> Image 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: PlaylistItem<br />The source PlaylistItem.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Youtube_ThumbnailQuality">DevCase.ThirdParty.Google.Youtube.ThumbnailQuality</a><br />\[Missing <param name="quality"/> documentation for "M:DevCase.ThirdParty.Google.Youtube.Extensions.PlaylistItem.Get.GetThumbnail(Google.Apis.YouTube.v3.Data.PlaylistItem,DevCase.ThirdParty.Google.Youtube.ThumbnailQuality)"\]</dd></dl>

#### Return Value
Type: Image<br />The resulting Image.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type PlaylistItem. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim item As PlaylistItem = ...
Dim img As Image = item.GetThumbnail(ThumbnailQuality.Standard)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_Extensions_PlaylistItem_Get">Get Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_PlaylistItem">DevCase.ThirdParty.Google.Youtube.Extensions.PlaylistItem Namespace</a><br />