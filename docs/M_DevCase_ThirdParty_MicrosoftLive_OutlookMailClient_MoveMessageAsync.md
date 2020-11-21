# OutlookMailClient.MoveMessageAsync Method 
 

Asynchronously moves the specified message to the target folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<bool> MoveMessageAsync(
	IMessage msg,
	IMailFolder destination
)
```

**VB**<br />
``` VB
Public Function MoveMessageAsync ( 
	msg As IMessage,
	destination As IMailFolder
) As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClient
Dim msg As IMessage
Dim destination As IMailFolder
Dim returnValue As Task(Of Boolean)

returnValue = instance.MoveMessageAsync(msg, 
	destination)
```

**C++**<br />
``` C++
public:
Task<bool>^ MoveMessageAsync(
	IMessage^ msg, 
	IMailFolder^ destination
)
```

**F#**<br />
``` F#
member MoveMessageAsync : 
        msg : IMessage * 
        destination : IMailFolder -> Task<bool> 

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: IMessage<br />The source IMessage to move.</dd><dt>destination</dt><dd>Type: IMailFolder<br />The target IMailFolder.</dd></dl>

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
Dim srcFolder As IMailFolder = Await outlookClient.GetFolderAsyncByKnownId(OutlookMailFolderIds.Inbox)
Dim dstFolder As IMailFolder = Await outlookClient.GetFolderAsyncByKnownId(OutlookMailFolderIds.DeletedItems)
Dim messages As IPagedCollection(Of IMessage) = Await outlookClient.GetMessagesAsync(srcFolder)
Dim msg As IMessage = messages.CurrentPage(0)
Dim success As Boolean = Await outlookClient.MoveMessageAsync(msg, dstFolder)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient">OutlookMailClient Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />