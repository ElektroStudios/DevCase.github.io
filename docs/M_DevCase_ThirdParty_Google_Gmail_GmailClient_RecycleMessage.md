# GmailClient.RecycleMessage Method 
 

Sends the specified message to the `Trash` folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool RecycleMessage(
	Message msg
)
```

**VB**<br />
``` VB
Public Function RecycleMessage ( 
	msg As Message
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim msg As Message
Dim returnValue As Boolean

returnValue = instance.RecycleMessage(msg)
```

**C++**<br />
``` C++
public:
bool RecycleMessage(
	Message^ msg
)
```

**F#**<br />
``` F#
member RecycleMessage : 
        msg : Message -> bool 

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: Message<br />The source Message to recycle.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the operation succeeds, otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Remarks
<a href="http://developers.google.com/gmail/api/v1/reference/users/messages/trash" target="_blank">http://developers.google.com/gmail/api/v1/reference/users/messages/trash</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = client.Authorize()
Dim folder As Google.Apis.Gmail.v1.Data.Label = client.GetFolderByKnownId(GmailFolderIds.Inbox)
Dim messages As List(Of Google.Apis.Gmail.v1.Data.Message) = client.GetMessages(folder)
Dim msg As Google.Apis.Gmail.v1.Data.Message = messages(0)
Dim success As Boolean = client.RecycleMessage(msg)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />