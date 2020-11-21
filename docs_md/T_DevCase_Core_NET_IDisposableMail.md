# IDisposableMail Interface
 

Represents a disposable mail address.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public interface IDisposableMail
```

**VB**<br />
``` VB
Public Interface IDisposableMail
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDisposableMail
```

**C++**<br />
``` C++
public interface class IDisposableMail
```

**F#**<br />
``` F#
type IDisposableMail =  interface end
```

The IDisposableMail type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_IDisposableMail_CreateNew">CreateNew</a></td><td>
Creates a new temporary mail address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_IDisposableMail_GetExpirationTime">GetExpirationTime</a></td><td>
Gets the time left to expire the current temporary mail address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_IDisposableMail_GetMailAddress">GetMailAddress</a></td><td>
Gets the mail address.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_IDisposableMail_GetMessageCount">GetMessageCount</a></td><td>
Gets the inbox message count.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_IDisposableMail_GetMessages">GetMessages</a></td><td>
Gets the inbox messages.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_IDisposableMail_Renew">Renew</a></td><td>
Renews the life-time for the current temporary mail address.</td></tr></table>&nbsp;
<a href="#idisposablemail-interface">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_NET_IDisposableMail_MailMessageArrived">MailMessageArrived</a></td><td>
Occurs when a new inbox message arrived.</td></tr></table>&nbsp;
<a href="#idisposablemail-interface">Back to Top</a>

## Remarks
Wikipedia article: <a href="https://en.wikipedia.org/wiki/Disposable_email_address" target="_blank">https://en.wikipedia.org/wiki/Disposable_email_address</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />