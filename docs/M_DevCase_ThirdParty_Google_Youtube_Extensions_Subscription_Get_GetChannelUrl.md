# Get.GetChannelUrl Method 
 

Gets the subscription's channel Url. 

 eg. `http://www.youtube.com/channel/{ChannelId}`

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_Subscription">DevCase.ThirdParty.Google.Youtube.Extensions.Subscription</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetChannelUrl(
	this Subscription sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetChannelUrl ( 
	sender As Subscription
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Subscription
Dim returnValue As String

returnValue = sender.GetChannelUrl()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetChannelUrl(
	Subscription^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetChannelUrl : 
        sender : Subscription -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: Subscription<br />The source Subscription.</dd></dl>

#### Return Value
Type: String<br />The resulting Url.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Subscription. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Youtube_Extensions_Subscription_Get">Get Class</a><br /><a href="N_DevCase_ThirdParty_Google_Youtube_Extensions_Subscription">DevCase.ThirdParty.Google.Youtube.Extensions.Subscription Namespace</a><br />