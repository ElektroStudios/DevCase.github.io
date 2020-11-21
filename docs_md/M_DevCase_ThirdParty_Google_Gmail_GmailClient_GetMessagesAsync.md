# GmailClient.GetMessagesAsync Method 
 

Asynchronously gets the messages contained in the specified mailbox folder.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Task<List<Message>> GetMessagesAsync(
	Label folder
)
```

**VB**<br />
``` VB
Public Function GetMessagesAsync ( 
	folder As Label
) As Task(Of List(Of Message))
```

**VB Usage**<br />
``` VB Usage
Dim instance As GmailClient
Dim folder As Label
Dim returnValue As Task(Of List(Of Message))

returnValue = instance.GetMessagesAsync(folder)
```

**C++**<br />
``` C++
public:
Task<List<Message^>^>^ GetMessagesAsync(
	Label^ folder
)
```

**F#**<br />
``` F#
member GetMessagesAsync : 
        folder : Label -> Task<List<Message>> 

```


#### Parameters
&nbsp;<dl><dt>folder</dt><dd>Type: Label<br />\[Missing <param name="folder"/> documentation for "M:DevCase.ThirdParty.Google.Gmail.GmailClient.GetMessagesAsync(Google.Apis.Gmail.v1.Data.Label)"\]</dd></dl>

#### Return Value
Type: Task(List(Message))<br />The resulting Task(TResult).

## Remarks
<a href="http://developers.google.com/gmail/api/v1/reference/users/messages/get" target="_blank">http://developers.google.com/gmail/api/v1/reference/users/messages/get</a>

## Examples
This example demonstrates how to iterate the messages contained in the "Inbox" mailbox folder to retrieve message info. 
**VB**<br />
``` VB
Dim client As New GmailClient("C:\GoogleSecrets.json", "yourmail@gmail.com", GmailScopes.ReadOnly Or GmailScopes.Modify Or GmailScopes.Send)
Dim credential As UserCredential = Await client.AuthorizeAsync()
Dim folder As Google.Apis.Gmail.v1.Data.Label = Await client.GetFolderAsyncByKnownId(GmailFolderIds.Inbox)
Dim messages As List(Of Google.Apis.Gmail.v1.Data.Message) = Await client.GetMessagesAsync(folder)
Dim msgCount As Integer

Dim [date] As String = ""
Dim from As String = ""
Dim subject As String = ""
Dim body As String = ""

For Each msg As Google.Apis.Gmail.v1.Data.Message In messages

    For Each header As MessagePartHeader In msg.Payload.Headers

        Select Case header.Name

            Case "Date"
                [date] = header.Value

            Case "From"
                from = header.Value

            Case "Subject"
                subject = header.Value

            Case Else
                ' ...

        End Select

    Next header

    Console.WriteLine(String.Format("Count: {0}; Id: {1}; From: {2}, Date: {3}, Subject: {4}",
                                    Interlocked.Increment(msgCount),
                                    msg.Id, from, [date], subject))

    body = msg.Payload.Body.Data

    ' We need to evaluate this because some message bodies are Base64 encoded, and some others aren't.
    If DevCase.Core.Cryptography.CryptoUtil.IsBase64Encoded(msg.Payload.Body.Data) Then
        body = DevCase.Core.Cryptography.CryptoUtil.Base64Decode(msg.Payload.Body.Data)
    End If

    ' Console.WriteLine(body)

Next msg
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Gmail_GmailClient">GmailClient Class</a><br /><a href="N_DevCase_ThirdParty_Google_Gmail">DevCase.ThirdParty.Google.Gmail Namespace</a><br />