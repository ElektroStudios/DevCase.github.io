# IDisposableMail.GetMessages Method 
 

Gets the inbox messages.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET">DevCase.Core.NET</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
IEnumerable<MailMessage> GetMessages()
```

**VB**<br />
``` VB
Function GetMessages As IEnumerable(Of MailMessage)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IDisposableMail
Dim returnValue As IEnumerable(Of MailMessage)

returnValue = instance.GetMessages()
```

**C++**<br />
``` C++
IEnumerable<MailMessage^>^ GetMessages()
```

**F#**<br />
``` F#
abstract GetMessages : unit -> IEnumerable<MailMessage> 

```


#### Return Value
Type: IEnumerable(MailMessage)<br />The inbox messages.

## See Also


#### Reference
<a href="T_DevCase_Core_NET_IDisposableMail">IDisposableMail Interface</a><br /><a href="N_DevCase_Core_NET">DevCase.Core.NET Namespace</a><br />