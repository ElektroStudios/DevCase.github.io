# GmailClient.GetFolderAsyncByKnownId Method 
 

Asynchronously gets a mailbox folder that satisfies the specified known Id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<Label> GetFolderAsyncByKnownId(
	GmailFolderIds knownId
)
```

**VB**<br />
``` VB
Public Function GetFolderAsyncByKnownId ( 
	knownId As GmailFolderIds
) As Task(Of Label)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim knownId As GmailFolderIds
Dim returnValue As Task(Of Label)

returnValue = instance.GetFolderAsyncByKnownId(knownId)
```

**C++**<br />
``` C++
public:
Task<Label^>^ GetFolderAsyncByKnownId(
	GmailFolderIds knownId
)
```

**F#**<br />
``` F#
member GetFolderAsyncByKnownId : 
        knownId : GmailFolderIds -> Task<Label> 

```


#### Parameters
&nbsp;<dl><dt>knownId</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Gmail_GmailFolderIds">DevCase.ThirdParty.Google.Gmail.GmailFolderIds</a><br />A known mailbox folder id.</dd></dl>

#### Return Value
Type: Task(Label)<br />The resulting Task(TResult) that represents the mailbox folder.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim folder As Google.Apis.Gmail.v1.Data.Label = Await client.GetFolderAsyncByKnownId(GmailFolderIds.Inbox)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />