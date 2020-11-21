# OutlookMailClientExperimental.GetFolderAsyncByKnownId Method 
 

Asynchronously gets a mailbox folder that satisfies the specified known Id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<IMailFolder> GetFolderAsyncByKnownId(
	OutlookMailFolderIds id
)
```

**VB**<br />
``` VB
Public Function GetFolderAsyncByKnownId ( 
	id As OutlookMailFolderIds
) As Task(Of IMailFolder)
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClientExperimental
Dim id As OutlookMailFolderIds
Dim returnValue As Task(Of IMailFolder)

returnValue = instance.GetFolderAsyncByKnownId(id)
```

**C++**<br />
``` C++
public:
Task<IMailFolder^>^ GetFolderAsyncByKnownId(
	OutlookMailFolderIds id
)
```

**F#**<br />
``` F#
member GetFolderAsyncByKnownId : 
        id : OutlookMailFolderIds -> Task<IMailFolder> 

```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: <a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailFolderIds">DevCase.ThirdParty.MicrosoftLive.OutlookMailFolderIds</a><br />The target mailbox known Id.</dd></dl>

#### Return Value
Type: Task(IMailFolder)<br />The resulting Task(TResult) that represents the mailbox folder.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim outlookClient As New OutlookMailClient(Process.GetCurrentProcess.MainWindowHandle, "YOUR CLIENT ID", OutlookMailScopes.ReadWrite Or OutlookMailScopes.Send)
Await outlookClient.AuthorizeAsync()
Dim folder As IMailFolder = Await outlookClient.GetFolderAsyncByKnownId(OutlookMailFolderIds.Inbox)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClientExperimental">OutlookMailClientExperimental Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />