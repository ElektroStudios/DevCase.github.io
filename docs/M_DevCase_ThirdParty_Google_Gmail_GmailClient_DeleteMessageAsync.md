# GmailClient.DeleteMessageAsync Method 
 

Asynchronously permanentlly deletes the specified message.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<bool> DeleteMessageAsync(
	Message msg
)
```

**VB**<br />
``` VB
Public Function DeleteMessageAsync ( 
	msg As Message
) As Task(Of Boolean)
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim msg As Message
Dim returnValue As Task(Of Boolean)

returnValue = instance.DeleteMessageAsync(msg)
```

**C++**<br />
``` C++
public:
Task<bool>^ DeleteMessageAsync(
	Message^ msg
)
```

**F#**<br />
``` F#
member DeleteMessageAsync : 
        msg : Message -> Task<bool> 

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: Message<br />The source Message to delete.</dd></dl>

#### Return Value
Type: Task(Boolean)<br />`true` (`True` in Visual Basic) if the operation succeeds, otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidOperationException</td><td /></tr></table>

## Remarks
<a href="http://developers.google.com/gmail/api/v1/reference/users/messages/delete" target="_blank">http://developers.google.com/gmail/api/v1/reference/users/messages/delete</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim folder As Google.Apis.Gmail.v1.Data.Label = Await client.GetFolderAsyncByKnownId(GmailFolderIds.Inbox)
Dim messages As List(Of Google.Apis.Gmail.v1.Data.Message) = Await client.GetMessagesAsync(folder)
Dim msg As Google.Apis.Gmail.v1.Data.Message = messages(0)
Dim success As Boolean = Await client.DeleteMessageAsync(msg)
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />