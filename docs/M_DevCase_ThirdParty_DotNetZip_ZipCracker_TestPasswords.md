# ZipCracker.TestPasswords Method 
 

Tests the specified passwords.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string TestPasswords(
	IEnumerable<string> passwords
)
```

**VB**<br />
``` VB
Public Function TestPasswords ( 
	passwords As IEnumerable(Of String)
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As ZipCracker
Dim passwords As IEnumerable(Of String)
Dim returnValue As String

returnValue = instance.TestPasswords(passwords)
```

**C++**<br />
``` C++
public:
String^ TestPasswords(
	IEnumerable<String^>^ passwords
)
```

**F#**<br />
``` F#
member TestPasswords : 
        passwords : IEnumerable<string> -> string 

```


#### Parameters
&nbsp;<dl><dt>passwords</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />The passwords to test.</dd></dl>

#### Return Value
Type: String<br />If one of the given password matches, the return value is the password; otherwise, the return value is String.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DotNetZip_ZipCracker">ZipCracker Class</a><br /><a href="N_DevCase_ThirdParty_DotNetZip">DevCase.ThirdParty.DotNetZip Namespace</a><br />