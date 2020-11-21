# FileExtensionInfo.DdeIfExec Property 
 

Gets the DDE command to use to create a process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DdeIfExec { get; set; }
```

**VB**<br />
``` VB
Public Property DdeIfExec As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.DdeIfExec

instance.DdeIfExec = value
```

**C++**<br />
``` C++
public:
property String^ DdeIfExec {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member DdeIfExec : string with get, set

```


#### Property Value
Type: String<br />The DDE command to use to create a process.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />