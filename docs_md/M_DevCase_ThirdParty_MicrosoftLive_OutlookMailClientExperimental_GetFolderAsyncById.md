# OutlookMailClientExperimental.GetFolderAsyncById Method 
 

Asynchronously gets a mailbox folder that satisfies the specified Id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<IMailFolder> GetFolderAsyncById(
	string id
)
```

**VB**<br />
``` VB
Public Function GetFolderAsyncById ( 
	id As String
) As Task(Of IMailFolder)
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClientExperimental
Dim id As String
Dim returnValue As Task(Of IMailFolder)

returnValue = instance.GetFolderAsyncById(id)
```

**C++**<br />
``` C++
public:
Task<IMailFolder^>^ GetFolderAsyncById(
	String^ id
)
```

**F#**<br />
``` F#
member GetFolderAsyncById : 
        id : string -> Task<IMailFolder> 

```


#### Parameters
&nbsp;<dl><dt>id</dt><dd>Type: System.String<br />The target mailbox folder Id.</dd></dl>

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
Dim folderId As String = "AQMkADAwATYwMAItYTI5NC02NgBkMC0wMAItMDAKAC4AAAP10PQF3tB9T6axZ5YUsGQeAQAvGPLjMgHlR4TDjnwToHw_AAAAIDbxCQAAAA=="
Dim folder As IMailFolder = Await outlookClient.GetFolderAsyncById(folderId)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClientExperimental">OutlookMailClientExperimental Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />