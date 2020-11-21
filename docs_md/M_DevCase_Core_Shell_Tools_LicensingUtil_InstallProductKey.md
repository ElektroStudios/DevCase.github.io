# LicensingUtil.InstallProductKey Method 
 

Installs a Windows product key on the current operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void InstallProductKey(
	string productKey
)
```

**VB**<br />
``` VB
Public Shared Sub InstallProductKey ( 
	productKey As String
)
```

**VB Usage**<br />
``` VB Usage
Dim productKey As StringLicensingUtil.InstallProductKey(productKey)
```

**C++**<br />
``` C++
public:
static void InstallProductKey(
	String^ productKey
)
```

**F#**<br />
``` F#
static member InstallProductKey : 
        productKey : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>productKey</dt><dd>Type: System.String<br />The product key.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>PlatformNotSupportedException</td><td>Windows 7 or newer is required to use this feature.</td></tr><tr><td>ArgumentNullException</td><td>productKey</td></tr><tr><td>Exception</td><td>The Software Licensing Service determined that the product key is invalid. or Unknown error occurred during the product key installation attempt.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/cc534590(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc534590(v=vs.85).aspx</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim productKey As String = "YTMG3-N6DKC-DKB77-7M9GH-8HVX7"
InstallProductKey(productKey)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />