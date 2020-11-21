# RegInfo(*T*).SubKeyPath Property 
 

Gets or sets the registry subkey path. ( eg: subkey1\subkey2\ )

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string SubKeyPath { get; set; }
```

**VB**<br />
``` VB
Public Property SubKeyPath As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As RegInfo
Dim value As String

value = instance.SubKeyPath

instance.SubKeyPath = value
```

**C++**<br />
``` C++
public:
property String^ SubKeyPath {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member SubKeyPath : string with get, set

```


#### Property Value
Type: String<br />The registry subkey path.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_RegInfo_1">RegInfo(T) Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />