# DevCase.Core.NET Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_BBCodeDocument">BBCodeDocument</a></td><td>
Represents an entire BBCode document. Similar to the HTML tag <body></td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_BBCodeHtmlRenderer">BBCodeHtmlRenderer</a></td><td>
Exposes HTML rendering methods for BBCode documents.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_BBCodeNode">BBCodeNode</a></td><td>
Represents a BBCode node.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_BBCodeTextNode">BBCodeTextNode</a></td><td>
Represents an entire BBCode text node.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_NET_DevWebClient">DevWebClient</a></td><td>
A extended WebClient component, with support for cookies and requests timeout.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_FirewallRule">FirewallRule</a></td><td>
Provides the information of a Windows Firewall rule.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_GeoInfo">GeoInfo</a></td><td>
Defines the geographic info of a host.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_MailAccount">MailAccount</a></td><td>
Represents a mail account.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_NET_NetworkTrafficMonitor">NetworkTrafficMonitor</a></td><td>
Monitorizes the traffic of a network interface.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_NET_ProcessTrafficMonitor">ProcessTrafficMonitor</a></td><td>
Monitorizes the network traffic of a process.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Core_NET_SmtpClients">SmtpClients</a></td><td>
Represents the Bitcoin (symbol: BTC) cryptocurrency.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_NET_TenMinuteMail">TenMinuteMail</a></td><td>
Creates and manages a temporary mail address using the https://10minutemail.com/ service. 

 Be aware the mail address will permanently expire in approx. 10 minutes after calling the <a href="M_DevCase_Core_NET_TenMinuteMail_Dispose">Dispose()</a> method.</td></tr><tr><td>![Public class](media/pubclass.gif "Public class")![Code example](media/CodeExample.png "Code example")</td><td><a href="T_DevCase_Core_NET_YoutubeUrl">YoutubeUrl</a></td><td>
Represents a Youtube Url.</td></tr></table>

## Interfaces
&nbsp;<table><tr><th></th><th>Interface</th><th>Description</th></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Core_NET_ICryptoCurrency">ICryptoCurrency</a></td><td>
Represents a cryptocurrency.</td></tr><tr><td>![Public interface](media/pubinterface.gif "Public interface")</td><td><a href="T_DevCase_Core_NET_IDisposableMail">IDisposableMail</a></td><td>
Represents a disposable mail address.</td></tr></table>

## Delegates
&nbsp;<table><tr><th></th><th>Delegate</th><th>Description</th></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Core_NET_BBCodeHtmlRenderer_BBCodeHtmlRendererCallback">BBCodeHtmlRenderer.BBCodeHtmlRendererCallback</a></td><td>
A delegate that allows you to register for your own BBCode tags. 

 This is called when the parser encounters the respective custom tag.</td></tr></table>

## Enumerations
&nbsp;<table><tr><th></th><th>Enumeration</th><th>Description</th></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_Currencies">Currencies</a></td><td>
Specifies the ISO-4217 3-character currency codes.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_FirewallNetworkProfile">FirewallNetworkProfile</a></td><td>
Specifies a Windows firewall network profile.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_FirewallProtocol">FirewallProtocol</a></td><td>
Specifies the IP protocol of a firewall.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_FirewallRuleAction">FirewallRuleAction</a></td><td>
Specifies the action for a firewall rule.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_FirewallRuleDirection">FirewallRuleDirection</a></td><td>
Specifies the direction of traffic to which a firewall rule applies.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_GoogleLanguage">GoogleLanguage</a></td><td>
Specifies a language abbreviation for Google services. 

 Last revision to this enum was did on 09-November-2014.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_IEBrowserEmulationMode">IEBrowserEmulationMode</a></td><td>
Specifies a Internet Explorer browser emulation mode.</td></tr><tr><td>![Public enumeration](media/pubenumeration.gif "Public enumeration")</td><td><a href="T_DevCase_Core_NET_TrafficMonitorUpdateBehavior">TrafficMonitorUpdateBehavior</a></td><td>
Specifies a behavior of the <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> and <a href="E_DevCase_Core_NET_NetworkTrafficMonitor_TrafficChanged">TrafficChanged</a> events.</td></tr></table>&nbsp;
