# TenMinuteMail Class
 

Creates and manages a temporary mail address using the https://10minutemail.com/ service. 

 Be aware the mail address will permanently expire in approx. 10 minutes after calling the <a href="M_DevCase_Core_NET_TenMinuteMail_Dispose">Dispose()</a> method.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.NET.TenMinuteMail<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class TenMinuteMail : IDisposableMail, 
	IDisposable
```

**VB**<br />
``` VB
Public Class TenMinuteMail
	Implements IDisposableMail, IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As TenMinuteMail
```

**C++**<br />
``` C++
public ref class TenMinuteMail : IDisposableMail, 
	IDisposable
```

**F#**<br />
``` F#
type TenMinuteMail =  
    class
        interface IDisposableMail
        interface IDisposable
    end
```

The TenMinuteMail type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_TenMinuteMail__ctor">TenMinuteMail()</a></td><td>
Initializes a new instance of the TenMinuteMail class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_TenMinuteMail__ctor_1">TenMinuteMail(TimeSpan)</a></td><td>
Initializes a new instance of the TenMinuteMail class.</td></tr></table>&nbsp;
<a href="#tenminutemail-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_TenMinuteMail_IsBlocked">IsBlocked</a></td><td>
Gets a value indicating whether the temporary mail service is blocked. 

 If `true` (`True` in Visual Basic), this means you have requested too many temporary mail addresses from your IP address too quickly. 

 And you must wait some minutes to be able use 10minutemail.com service again.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_TenMinuteMail_MailAddress">MailAddress</a></td><td>
Gets the mail address.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_TenMinuteMail_MessageCount">MessageCount</a></td><td>
Gets the message count.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_TenMinuteMail_Messages">Messages</a></td><td>
Gets the inbox messages.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_TenMinuteMail_Messages_1">Messages(String)</a></td><td>
Gets the inbox message with the specified message id.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_TenMinuteMail_UpdateInterval">UpdateInterval</a></td><td>
Gets the time interval to check for new incoming messages.</td></tr></table>&nbsp;
<a href="#tenminutemail-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_TenMinuteMail_CreateNew">CreateNew</a></td><td>
Creates a new temporary mail address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_TenMinuteMail_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance. 

 Be aware the mail address will permanently expire in approx. 10 minutes after calling the <a href="M_DevCase_Core_NET_TenMinuteMail_Dispose">Dispose()</a> method.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_TenMinuteMail_Reply">Reply(MailMessage, String)</a></td><td>
Replies to the specified MailMessage.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_TenMinuteMail_Reply_1">Reply(String, String)</a></td><td>
Replies to a MailMessage with the specified message id.</td></tr></table>&nbsp;
<a href="#tenminutemail-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_NET_TenMinuteMail_MailMessageArrived">MailMessageArrived</a></td><td>
Occurs when a new inbox message arrived.</td></tr></table>&nbsp;
<a href="#tenminutemail-class">Back to Top</a>

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
<a href="#tenminutemail-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public NotInheritable Class Form1

    ''' <summary>
    ''' The temporary mail client.
    ''' </summary>
    Private WithEvents TempMail As TenMinuteMail

    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load
        Me.TempMail = New TenMinuteMail(TimeSpan.FromSeconds(10)) ' Set inbox notification interval to 10 sec.
        Console.WriteLine(String.Format("Your 10MinuteMail Address: '{0}'", Me.TempMail.MailAddress.Address))
    End Sub

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' Handles the <see cref="TenMinuteMail.MailMessageArrived"/> event of the <see cref="Form1.TempMail"/> object.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <param name="sender">
    ''' The source of the event.
    ''' </param>
    ''' 
    ''' <param name="e">
    ''' The <see cref="MailMessageArrivedEventArgs"/> instance containing the event data.
    ''' </param>
    ''' ----------------------------------------------------------------------------------------------------
    Private Sub TempMail_MailMessageArrived(ByVal sender As Object, ByVal e As MailMessageArrivedEventArgs) _
    Handles TempMail.MailMessageArrived

        Dim sb As New StringBuilder()
        With sb
            .AppendLine()
            .AppendLine("NEW MAIL MESSAGE ARRIVED")
            .AppendLine("************************")
            .AppendLine()
            .AppendLine(String.Format("From...: {0}", e.MailMessage.From.Address))
            .AppendLine(String.Format("To.....: {0}", String.Join(";", (From msg As MailAddress In e.MailMessage.To))))
            .AppendLine(String.Format("Subject: {0}", e.MailMessage.Subject))
            .AppendLine(String.Format("Msg.Id.: {0}", e.MailMessage.Headers("msgId")))
            .AppendLine()
            .AppendLine("-------BODY START-------")
            .AppendLine(e.MailMessage.Body)
            .AppendLine("-------BODY END---------")
        End With

        Console.WriteLine(sb.ToString())

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br /><a href="T_DevCase_Core_NET_IDisposableMail">DevCase.Core.NET.IDisposableMail</a><br />System.IDisposable<br />