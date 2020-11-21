# SerializableCookie&nbsp;Implicit Conversion (ReturnedCookie to SerializableCookie)
 

Performs an implicit conversion from ReturnedCookie to <a href="T_DevCase_ThirdParty_Selenium_SerializableCookie">SerializableCookie</a>.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator SerializableCookie (
	ReturnedCookie cookie
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	cookie As ReturnedCookie
) As SerializableCookie
```

**VB Usage**<br />
``` VB Usage
Dim input As ReturnedCookie
Dim output As SerializableCookie

output = CType(input, SerializableCookie)
```

**C++**<br />
``` C++
static implicit operator SerializableCookie^ (
	ReturnedCookie^ cookie
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>cookie</dt><dd>Type: ReturnedCookie<br />The source ReturnedCookie.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_ThirdParty_Selenium_SerializableCookie">SerializableCookie</a><br />The resulting <a href="T_DevCase_ThirdParty_Selenium_SerializableCookie">SerializableCookie</a>.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Selenium_SerializableCookie">SerializableCookie Class</a><br /><a href="N_DevCase_ThirdParty_Selenium">DevCase.ThirdParty.Selenium Namespace</a><br />