# RegInfo(*T*).RootKeyName Property 
 

Gets or sets the registry root key. ( eg: HKCU or HKEY_CURRENT_USER)

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string RootKeyName { get; set; }
```

**VB**<br />
``` VB
Public Property RootKeyName As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo
Dim value As String

value = instance.RootKeyName

instance.RootKeyName = value
```

**C++**<br />
``` C++
public:
property String^ RootKeyName {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member RootKeyName : string with get, set

```


#### Property Value
Type: String<br />The registry root key.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T) Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />