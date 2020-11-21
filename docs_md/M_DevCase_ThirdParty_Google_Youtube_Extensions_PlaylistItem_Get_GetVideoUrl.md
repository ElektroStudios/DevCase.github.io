# Get.GetVideoUrl Method 
 

Gets the playlist item's video Url. 

 eg. `http://www.youtube.com/watch?v={VideoId}`

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_PlaylistItem">DevCase.ThirdParty.Google.Youtube.Extensions.PlaylistItem</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetVideoUrl(
	this PlaylistItem sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetVideoUrl ( 
	sender As PlaylistItem
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As PlaylistItem
Dim returnValue As String

returnValue = sender.GetVideoUrl()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetVideoUrl(
	PlaylistItem^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetVideoUrl : 
        sender : PlaylistItem -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: PlaylistItem<br />The source PlaylistItem.</dd></dl>

#### Return Value
Type: String<br />The resulting Url.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type PlaylistItem. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_Extensions_PlaylistItem_Get">Get Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_PlaylistItem">DevCase.ThirdParty.Google.Youtube.Extensions.PlaylistItem Namespace</a><br />