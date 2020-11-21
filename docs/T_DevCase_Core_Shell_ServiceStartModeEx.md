# ServiceStartModeEx Enumeration
 

Specifies the start mode of a service.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ServiceStartModeEx
```

**VB**<br />
``` VB
Public Enumeration ServiceStartModeEx
```

**VB Usage**<br />
``` VB Usage
Dim instance As ServiceStartModeEx
```

**C++**<br />
``` C++
public enum class ServiceStartModeEx
```

**F#**<br />
``` F#
type ServiceStartModeEx
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.ServiceStartModeEx.Undefinied">**Undefinied**</td><td>0</td><td>The service has not a start mode defined. 

 Since a service should have a start mode defined, this means an error occured retrieving the start mode.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ServiceStartModeEx.AutomaticDelayed">**AutomaticDelayed**</td><td>1</td><td>The service is to be started (or was started) by the operating system, at system start-up. 

 The service is started after other auto-start services are started plus a short delay.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ServiceStartModeEx.Automatic">**Automatic**</td><td>2</td><td>The service is to be started (or was started) by the operating system, at system start-up. 

 If an automatically started service depends on a manually started service, the manually started service is also started automatically at system startup.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ServiceStartModeEx.Manual">**Manual**</td><td>3</td><td>The service is started only manually, by a user (using the Service Control Manager) or by an application.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ServiceStartModeEx.Disabled">**Disabled**</td><td>4</td><td>The service is disabled, so that it cannot be started by a user or application.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />