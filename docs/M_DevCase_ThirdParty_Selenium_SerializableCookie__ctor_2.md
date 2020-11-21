# SerializableCookie Constructor (String, String, String, Nullable(DateTime))
 

Initializes a new instance of the <a href="T_DevCase_ThirdParty_Selenium_SerializableCookie">SerializableCookie</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SerializableCookie(
	string name,
	string value,
	string path,
	Nullable<DateTime> expiry
)
```

**VB**<br />
``` VB
Public Sub New ( 
	name As String,
	value As String,
	path As String,
	expiry As Nullable(Of DateTime)
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim value As String
Dim path As String
Dim expiry As Nullable(Of DateTime)

Dim instance As New SerializableCookie(name, value, 
	path, expiry)
```

**C++**<br />
``` C++
public:
SerializableCookie(
	String^ name, 
	String^ value, 
	String^ path, 
	Nullable<DateTime> expiry
)
```

**F#**<br />
``` F#
new : 
        name : string * 
        value : string * 
        path : string * 
        expiry : Nullable<DateTime> -> SerializableCookie
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the cookie.</dd><dt>value</dt><dd>Type: System.String<br />The value of the cookie.</dd><dt>path</dt><dd>Type: System.String<br />The path of the cookie.</dd><dt>expiry</dt><dd>Type: System.Nullable(DateTime)<br />The expiration date of the cookie.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_SerializableCookie">SerializableCookie Class</a><br /><a href="Overload_DevCase_ThirdParty_Selenium_SerializableCookie__ctor">SerializableCookie Overload</a><br /><a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium Namespace</a><br />