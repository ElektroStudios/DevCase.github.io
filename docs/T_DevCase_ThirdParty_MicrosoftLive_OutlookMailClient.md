# OutlookMailClient Class
 

A client for Outlook.com mail service. 

 This class uses the experimental Microsoft's ADAL build.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.MicrosoftLive.OutlookMailClient<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class OutlookMailClient : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class OutlookMailClient
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As OutlookMailClient
```

**C++**<br />
``` C++
public ref class OutlookMailClient sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type OutlookMailClient =  
    class
        inherit AestheticObject
    end
```

The OutlookMailClient type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient__ctor">OutlookMailClient</a></td><td>
Initializes a new instance of the OutlookMailClient class.</td></tr></table>&nbsp;
<a href="#outlookmailclient-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_Client">Client</a></td><td>
Gets the wrapped Outlook services client.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_ClientId">ClientId</a></td><td>
Gets the unique identifier of the registered application to use Outlook.com Mail API.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_IsAuthorized">IsAuthorized</a></td><td>
Gets a value that determines whether Outlook.com API authorization was done.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_Scopes">Scopes</a></td><td>
Gets the current Outlook.com mail OAuthv2 scopes.</td></tr></table>&nbsp;
<a href="#outlookmailclient-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_AuthorizeAsync">AuthorizeAsync</a></td><td>
Authorizes this instance to use Microsoft Outlook Mail services.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_DeleteMessageAsync">DeleteMessageAsync</a></td><td>
Asynchronously permanentlly deletes the specified message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_GetFolderAsyncByDisplayName">GetFolderAsyncByDisplayName</a></td><td>
Asynchronously gets a mailbox folder that satisfies the specified display name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_GetFolderAsyncById">GetFolderAsyncById</a></td><td>
Asynchronously gets a mailbox folder that satisfies the specified Id.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_GetFolderAsyncByKnownId">GetFolderAsyncByKnownId</a></td><td>
Asynchronously gets a mailbox folder that satisfies the specified known Id.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_GetMessagesAsync">GetMessagesAsync</a></td><td>
Asynchronously gets the messages contained in the specified mailbox folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_MoveMessageAsync">MoveMessageAsync</a></td><td>
Asynchronously moves the specified message to the target folder.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_ThirdParty_MicrosoftLive_OutlookMailClient_RecycleMessageAsync">RecycleMessageAsync</a></td><td>
Asynchronously sends the specified message to the `DeletedItems` folder.</td></tr></table>&nbsp;
<a href="#outlookmailclient-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#outlookmailclient-class">Back to Top</a>

## Examples
This example demonstrates how to iterate the messages contained in a custom mailbox folder named "Youtube", then parse those messages received from Youtube, extract the video urls, write the urls to a local text file, and finally recycle the parsed message. 
**VB**<br />
``` VB
Imports System.Threading.Tasks

Imports DevCase.ThirdParty.MicrosoftLive
Imports DevCase.ThirdParty.MicrosoftLive

Imports Microsoft.Identity.Client
Imports Microsoft.OData.ProxyExtensions
Imports Microsoft.Office365.OutlookServices

Public NotInheritable Class Form1 : Inherits Form

    Private outlookClient As OutlookMailClient

    ' You can get an API key at Microsoft's Application Registration Portal:
    ' https://apps.dev.microsoft.com/#/appList
    Private ReadOnly clientId As String = "YOUR CLIENT ID"

    Private ReadOnly folderName As String = "Youtube"
    Private ReadOnly dstFilepath As String = "C:\Youtube Urls.txt"

    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
        Me.BeginInvoke(Sub() Me.IterateMessages())
    End Sub

    Private Async Sub IterateMessages()

        Me.outlookClient = New OutlookMailClient(Me.clientId, OutlookMailScopes.ReadWrite Or OutlookMailScopes.Send)

        Await Me.outlookClient.AuthorizeAsync()
        Dim folder As IMailFolder = Await Me.outlookClient.GetFolderAsyncByDisplayName(Me.folderName)
        Dim messages As IPagedCollection(Of IMessage) = Await Me.outlookClient.GetMessagesAsync(folder)

        Dim pageCount As Integer

        Do While True

            Debug.WriteLine(String.Format("Reading page {0:00}", Threading.Interlocked.Increment(pageCount)))

            For Each msg As IMessage In messages.CurrentPage
                Dim success As Boolean = Await Me.ParseAndDeleteYoutubeMessage(msg, Me.dstFilepath)
            Next msg

            ' Read next page of messages.
            If messages.MorePagesAvailable Then
                messages = Await messages.GetNextPageAsync()
            Else
                Exit Do
            End If

        Loop

        Debug.WriteLine("Finished!")

    End Sub

    Private Async Function ParseAndDeleteYoutubeMessage(ByVal msg As IMessage, ByVal dstFile As String) As Task(Of Boolean)

        Dim urlRegex As New Regex("content=""http://www.youtube.com.+watch.+uploademail", RegexOptions.IgnoreCase)
        Dim attrRegex As New Regex("attribution_link\?a=(.){10,11}&u=\/watch%3Fv%3D", RegexOptions.IgnoreCase)

        Try
            If (msg.From.EmailAddress.Name.Equals("YouTube", StringComparison.OrdinalIgnoreCase)) Then

                Dim body As String = msg.Body.Content
                Dim isMatch As Boolean = urlRegex.IsMatch(body)

                If Not (isMatch) Then
                    Throw New InvalidOperationException("Youtube regex doesn't match.")

                Else
                    Dim urlMatches As MatchCollection = urlRegex.Matches(body)
                    Dim urls As String() =
                            (From m As Match In urlMatches.Cast(Of Match)
                             Select (Environment.NewLine & m.Value)
                            ).Distinct().ToArray()

                    For x As Integer = 0 To (urls.Length - 1)
                        Dim isAttrMatch As Boolean = attrRegex.IsMatch(urls(x))
                        If (isAttrMatch) Then
                            urls(x) = attrRegex.Replace(urls(x), "watch?v=")
                        End If
                        urls(x) = urls(x).Replace("content=""", "")
                        urls(x) = urls(x).Replace("%26feature%3Dem-uploademail", "")
                        urls(x) = urls(x).Replace("&feature=em-uploademail", "")
                        urls(x) = urls(x).Replace("%26no_autoplay%3D1", "")

                    Next x

                    File.AppendAllText(dstFile, String.Join("", urls))

                    msg.IsRead = True
                    Await msg.MoveAsync("DeletedItems")

                End If

            End If

            Return True

        Catch ex As Exception
            Throw
            Return False

        End Try

    End Function

End Class
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_MicrosoftLive">DevCase.ThirdParty.MicrosoftLive Namespace</a><br />