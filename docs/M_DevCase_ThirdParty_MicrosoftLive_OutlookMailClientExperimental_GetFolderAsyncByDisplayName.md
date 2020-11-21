# OutlookMailClientExperimental.GetFolderAsyncByDisplayName Method 
 

Asynchronously gets a mailbox folder that satisfies the specified display name.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<IMailFolder> GetFolderAsyncByDisplayName(
	string displayName
)
```

**VB**<br />
``` VB
Public Function GetFolderAsyncByDisplayName ( 
	displayName As String
) As Task(Of IMailFolder)
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClientExperimental
Dim displayName As String
Dim returnValue As Task(Of IMailFolder)

returnValue = instance.GetFolderAsyncByDisplayName(displayName)
```

**C++**<br />
``` C++
public:
Task<IMailFolder^>^ GetFolderAsyncByDisplayName(
	String^ displayName
)
```

**F#**<br />
``` F#
member GetFolderAsyncByDisplayName : 
        displayName : string -> Task<IMailFolder> 

```


#### Parameters
&nbsp;<dl><dt>displayName</dt><dd>Type: System.String<br />The target mailbox folder display name.</dd></dl>

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
Dim folder As IMailFolder = Await outlookClient.GetFolderAsyncByDisplayName("Bandeja de entrada")
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_MicrosoftLive_OutlookMailClientExperimental">OutlookMailClientExperimental Class</a><br /><a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />