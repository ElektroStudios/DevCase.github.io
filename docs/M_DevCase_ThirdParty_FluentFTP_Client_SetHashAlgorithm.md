# Client.SetHashAlgorithm Method 
 

Tells the FTP server wich hash algorithm to use for the HASH command.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool SetHashAlgorithm(
	FtpHashAlgorithm algorithm
)
```

**VB**<br />
``` VB
Public Function SetHashAlgorithm ( 
	algorithm As FtpHashAlgorithm
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As Client
Dim algorithm As FtpHashAlgorithm
Dim returnValue As Boolean

returnValue = instance.SetHashAlgorithm(algorithm)
```

**C++**<br />
``` C++
public:
bool SetHashAlgorithm(
	FtpHashAlgorithm algorithm
)
```

**F#**<br />
``` F#
member SetHashAlgorithm : 
        algorithm : FtpHashAlgorithm -> bool 

```


#### Parameters
&nbsp;<dl><dt>algorithm</dt><dd>Type: FtpHashAlgorithm<br />The HASH algorithm.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.ThirdParty.FluentFTP.Client.SetHashAlgorithm(FluentFTP.FtpHashAlgorithm)"\]

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_FluentFTP_Client">Client Class</a><br /><a href="N_DevCase_ThirdParty_FluentFTP">DevCase.ThirdParty.FluentFTP Namespace</a><br />