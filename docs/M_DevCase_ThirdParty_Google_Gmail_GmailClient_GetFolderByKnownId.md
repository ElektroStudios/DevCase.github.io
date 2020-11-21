# GmailClient.GetFolderByKnownId Method 
 

Gets a mailbox folder that satisfies the specified known Id.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Label GetFolderByKnownId(
	GmailFolderIds knownId
)
```

**VB**<br />
``` VB
Public Function GetFolderByKnownId ( 
	knownId As GmailFolderIds
) As Label
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim knownId As GmailFolderIds
Dim returnValue As Label

returnValue = instance.GetFolderByKnownId(knownId)
```

**C++**<br />
``` C++
public:
Label^ GetFolderByKnownId(
	GmailFolderIds knownId
)
```

**F#**<br />
``` F#
member GetFolderByKnownId : 
        knownId : GmailFolderIds -> Label 

```


#### Parameters
&nbsp;<dl><dt>knownId</dt><dd>Type: <a href="T_DevCase_ThirdParty_Google_Gmail_GmailFolderIds">DevCase.ThirdParty.Google.Gmail.GmailFolderIds</a><br />A known mailbox folder id.</dd></dl>

#### Return Value
Type: Label<br />The resulting Label that represents the mailbox folder.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = client.Authorize()
Dim folder As Google.Apis.Gmail.v1.Data.Label = client.GetFolderByKnownId(GmailFolderIds.Inbox)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />