# VmRunException Constructor 
 

Initializes a new instance of the System.Exception class with a specified error message and exit code.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare_Exceptions">DevCase.ThirdParty.VmWare.Exceptions</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public VmRunException(
	string message,
	int exitCode
)
```

**VB**<br />
``` VB
Public Sub New ( 
	message As String,
	exitCode As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim message As String
Dim exitCode As Integer

Dim instance As New VmRunException(message, 
	exitCode)
```

**C++**<br />
``` C++
public:
VmRunException(
	String^ message, 
	int exitCode
)
```

**F#**<br />
``` F#
new : 
        message : string * 
        exitCode : int -> VmRunException
```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: System.String<br />The error message thrown by VMWare's vmrun.exe application.</dd><dt>exitCode</dt><dd>Type: System.Int32<br />The exit code of VMWare's vmrun.exe application</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_VmWare_Exceptions_VmRunException">VmRunException Class</a><br /><a href="N_DevCase_ThirdParty_VmWare_Exceptions">DevCase.ThirdParty.VmWare.Exceptions Namespace</a><br />