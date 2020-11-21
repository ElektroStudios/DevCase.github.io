# GeckoFxProxyType Enumeration
 

Specifies a proxy type of a GeckoFx web-browser.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum GeckoFxProxyType
```

**VB**<br />
``` VB
Public Enumeration GeckoFxProxyType
```

**VB Usage**<br />
``` VB Usage
Dim instance As GeckoFxProxyType
```

**C++**<br />
``` C++
public enum class GeckoFxProxyType
```

**F#**<br />
``` F#
type GeckoFxProxyType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.ThirdParty.GeckoFx.GeckoFxProxyType.DirectConnection">**DirectConnection**</td><td>0</td><td>Direct connection, no proxy. 

 (Default in Windows and Mac previous to 1.9.2.4 /Firefox 3.6.4)</td></tr><tr><td /><td target="F:DevCase.ThirdParty.GeckoFx.GeckoFxProxyType.Manual">**Manual**</td><td>1</td><td>Manual proxy configuration.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.GeckoFx.GeckoFxProxyType.AutoConfiguration">**AutoConfiguration**</td><td>2</td><td>Proxy auto-configuration (PAC).</td></tr><tr><td /><td target="F:DevCase.ThirdParty.GeckoFx.GeckoFxProxyType.AutoDetect">**AutoDetect**</td><td>4</td><td>Auto-detect proxy settings.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.GeckoFx.GeckoFxProxyType.System">**System**</td><td>5</td><td>Use system proxy settings. 

 (Default in Linux; default for all platforms, starting in 1.9.2.4 /Firefox 3.6.4)</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_GeckoFx">DevCase.ThirdParty.GeckoFx Namespace</a><br />