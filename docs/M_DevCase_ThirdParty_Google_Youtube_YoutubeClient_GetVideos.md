# YoutubeClient.GetVideos Method 
 

Gets a list containing the videos uploaded in the specified channel.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<PlaylistItem>> GetVideos(
	string channelId
)
```

**VB**<br />
``` VB
Public Function GetVideos ( 
	channelId As String
) As Task(Of List(Of PlaylistItem))
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
Dim channelId As String
Dim returnValue As Task(Of List(Of PlaylistItem))

returnValue = instance.GetVideos(channelId)
```

**C++**<br />
``` C++
public:
Task<List<PlaylistItem^>^>^ GetVideos(
	String^ channelId
)
```

**F#**<br />
``` F#
member GetVideos : 
        channelId : string -> Task<List<PlaylistItem>> 

```


#### Parameters
&nbsp;<dl><dt>channelId</dt><dd>Type: System.String<br />\[Missing <param name="channelId"/> documentation for "M:DevCase.ThirdParty.Google.Youtube.YoutubeClient.GetVideos(System.String)"\]</dd></dl>

#### Return Value
Type: Task(List(PlaylistItem))<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/youtube/v3/docs/channels/list" target="_blank">http://developers.google.com/youtube/v3/docs/channels/list</a><a href="http://developers.google.com/youtube/v3/docs/playlistItems/list" target="_blank">http://developers.google.com/youtube/v3/docs/playlistItems/list</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com")
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim videos As List(Of PlaylistItem) = Await client.GetVideos("UC2xskkQVFEpLcGFnNSLQY0A") ' RihannaVEVO channel.
Dim videoCount As Integer

For Each video As PlaylistItem In videos
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(videoCount),
                              video.Id, video.Snippet.Title,
                              String.Format("http://www.youtube.com/watch?v={0}", video.Snippet.ResourceId.VideoId)))

Next video
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_YoutubeClient">YoutubeClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />