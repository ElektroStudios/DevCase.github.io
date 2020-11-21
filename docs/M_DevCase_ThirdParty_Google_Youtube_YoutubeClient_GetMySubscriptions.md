# YoutubeClient.GetMySubscriptions Method 
 

Gets a list containing the subscriptions of the current youtube account.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<Subscription>> GetMySubscriptions(
	OrderEnum resultSorting
)
```

**VB**<br />
``` VB
Public Function GetMySubscriptions ( 
	resultSorting As OrderEnum
) As Task(Of List(Of Subscription))
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeClient
Dim resultSorting As OrderEnum
Dim returnValue As Task(Of List(Of Subscription))

returnValue = instance.GetMySubscriptions(resultSorting)
```

**C++**<br />
``` C++
public:
Task<List<Subscription^>^>^ GetMySubscriptions(
	OrderEnum resultSorting
)
```

**F#**<br />
``` F#
member GetMySubscriptions : 
        resultSorting : OrderEnum -> Task<List<Subscription>> 

```


#### Parameters
&nbsp;<dl><dt>resultSorting</dt><dd>Type: OrderEnum<br />A value that determines the sorting method of the resulting playlists (Sort by date, sort by relevance, etc...)</dd></dl>

#### Return Value
Type: Task(List(Subscription))<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/youtube/v3/docs/subscriptions/list" target="_blank">http://developers.google.com/youtube/v3/docs/subscriptions/list</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New YoutubeClient("C:\GoogleSecrets.json", "yourmail@gmail.com")
Dim credential As UserCredential = Await client.AuthorizeAsync()

Dim subscriptions As List(Of Subscription) = Await client.GetMySubscriptions(SubscriptionsResource.ListRequest.OrderEnum.Relevance)
Dim subscriptionCount As Integer

For Each subscription As Subscription In subscriptions
    Console.WriteLine(String.Format("Count: {0}; Id: {1}; Title: {2}, Url: {3}",
                              Interlocked.Increment(subscriptionCount),
                              subscription.Id, subscription.Snippet.Title,
                              String.Format("http://www.youtube.com/channel/{0}", subscription.Snippet.ResourceId.ChannelId)))

Next subscription
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_YoutubeClient">YoutubeClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />