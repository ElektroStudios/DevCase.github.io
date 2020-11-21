# YoutubeClient.SearchChannels Method 
 

Searchs channels through Youtube that matches the specified criteria.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<SearchResult>> SearchChannels(
	string searchPattern,
	OrderEnum resultSorting
)
```

**VB**<br />
``` VB
Public Function SearchChannels ( 
	searchPattern As String,
	resultSorting As OrderEnum
) As Task(Of List(Of SearchResult))
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
Dim searchPattern As String
Dim resultSorting As OrderEnum
Dim returnValue As Task(Of List(Of SearchResult))

returnValue = instance.SearchChannels(searchPattern, 
	resultSorting)
```

**C++**<br />
``` C++
public:
Task<List<SearchResult^>^>^ SearchChannels(
	String^ searchPattern, 
	OrderEnum resultSorting
)
```

**F#**<br />
``` F#
member SearchChannels : 
        searchPattern : string * 
        resultSorting : OrderEnum -> Task<List<SearchResult>> 

```


#### Parameters
&nbsp;<dl><dt>searchPattern</dt><dd>Type: System.String<br />The search pattern. 

 Only channels matching the specified title pattern will be listed.</dd><dt>resultSorting</dt><dd>Type: OrderEnum<br />A value that determines the sorting method of the resulting channels (Sort by date, sort by relevance, etc...)</dd></dl>

#### Return Value
Type: Task(List(SearchResult))<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/youtube/v3/docs/search/list" target="_blank">http://developers.google.com/youtube/v3/docs/search/list</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com")
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim channels As List(Of SearchResult) = Await client.SearchChannels("Rihanna", OrderEnum.Relevance)
Dim channelCount As Integer

For Each channel As SearchResult In channels
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(channelCount),
                              channel.Id.ChannelId, channel.Snippet.Title,
                              String.Format("http://www.youtube.com/channel/{0}", channel.Id.ChannelId)))

Next channel
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_YoutubeClient">YoutubeClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />