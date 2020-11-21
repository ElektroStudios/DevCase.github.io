# OutlookMailClient.DeleteMessageAsync Method 
 

Asynchronously permanentlly deletes the specified message.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<bool> DeleteMessageAsync(
	IMessage msg
)
```

**VB**<br />
``` VB
Public Function DeleteMessageAsync ( 
	msg As IMessage
) As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClient
Dim msg As IMessage
Dim returnValue As Task(Of Boolean)

returnValue = instance.DeleteMessageAsync(msg)
```

**C++**<br />
``` C++
public:
Task<bool>^ DeleteMessageAsync(
	IMessage^ msg
)
```

**F#**<br />
``` F#
member DeleteMessageAsync : 
        msg : IMessage -> Task<bool> 

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: IMessage<br />The source IMessage to delete.</dd></dl>

#### Return Value
Type: Task(Boolean)<br />`true` (`True` in Visual Basic) if the operation succeeds, otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim outlookClient As New OutlookMailClient("YOUR CLIENT ID", OutlookMailScopes.ReadWrite Or OutlookMailScopes.Send)
Await outlookClient.AuthorizeAsync()
Dim folder As IMailFolder = Await outlookClient.GetFolderAsyncByKnownId(OutlookMailFolderIds.Inbox)
Dim messages As IPagedCollection(Of IMessage) = Await outlookClient.GetMessagesAsync(folder)
Dim msg As IMessage = messages.CurrentPage(0)
Dim success As Boolean = Await outlookClient.DeleteMessageAsync(msg)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />