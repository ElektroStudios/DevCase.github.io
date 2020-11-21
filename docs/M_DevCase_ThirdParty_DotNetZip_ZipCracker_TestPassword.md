# ZipCracker.TestPassword Method 
 

Tests the specified password.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool TestPassword(
	string password
)
```

**VB**<br />
``` VB
Public Function TestPassword ( 
	password As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipCracker
Dim password As String
Dim returnValue As Boolean

returnValue = instance.TestPassword(password)
```

**C++**<br />
``` C++
public:
bool TestPassword(
	String^ password
)
```

**F#**<br />
``` F#
member TestPassword : 
        password : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>password</dt><dd>Type: System.String<br />The password to test.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the password matches, `false` (`False` in Visual Basic) otherwise.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipCracker">ZipCracker Class</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />