# Get.GetChannelUrl Method 
 

Gets the video's channel Url. 

 eg. `http://www.youtube.com/channel/{ChannelId}`

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_SearchResult">DevCase.ThirdParty.Google.Youtube.Extensions.SearchResult</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetChannelUrl(
	this SearchResult sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetChannelUrl ( 
	sender As SearchResult
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As SearchResult
Dim returnValue As String

returnValue = sender.GetChannelUrl()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetChannelUrl(
	SearchResult^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetChannelUrl : 
        sender : SearchResult -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: SearchResult<br />The source SearchResult.</dd></dl>

#### Return Value
Type: String<br />The resulting Url.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SearchResult. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_Extensions_SearchResult_Get">Get Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_SearchResult">DevCase.ThirdParty.Google.Youtube.Extensions.SearchResult Namespace</a><br />