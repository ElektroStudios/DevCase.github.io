# OutlookMailClientExperimental.GetMessagesAsync Method 
 

Asynchronously gets the messages contained in the specified mailbox folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<IPagedCollection<IMessage>> GetMessagesAsync(
	IMailFolder folder
)
```

**VB**<br />
``` VB
Public Function GetMessagesAsync ( 
	folder As IMailFolder
) As Task(Of IPagedCollection(Of IMessage))
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClientExperimental
Dim folder As IMailFolder
Dim returnValue As Task(Of IPagedCollection(Of IMessage))

returnValue = instance.GetMessagesAsync(folder)
```

**C++**<br />
``` C++
public:
Task<IPagedCollection<IMessage^>^>^ GetMessagesAsync(
	IMailFolder^ folder
)
```

**F#**<br />
``` F#
member GetMessagesAsync : 
        folder : IMailFolder -> Task<IPagedCollection<IMessage>> 

```


#### Parameters
&nbsp;<dl><dt>folder</dt><dd>Type: IMailFolder<br />The source mailbox folder.</dd></dl>

#### Return Value
Type: Task(IPagedCollection(IMessage))<br />The resulting Task(TResult) that represents the mailbox folder messages.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim outlookClient As New OutlookMailClient(Process.GetCurrentProcess.MainWindowHandle, "YOUR CLIENT ID", OutlookMailScopes.ReadWrite Or OutlookMailScopes.Send)
Await outlookClient.AuthorizeAsync()
Dim folder As IMailFolder = Await outlookClient.GetFolderAsyncByKnownId(OutlookMailFolderIds.Inbox)
Dim messages As IPagedCollection(Of IMessage) = Await outlookClient.GetMessagesAsync(folder)

' Iterate the messages.
Do While True
    For Each msg As IMessage In messages.CurrentPage
        ' Do something with the current message...
    Next msg

    ' Read next page of messages.
    If messages.MorePagesAvailable Then
        messages = Await messages.GetNextPageAsync()
    Else
        Exit Do
    End If
Loop
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClientExperimental">OutlookMailClientExperimental Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />