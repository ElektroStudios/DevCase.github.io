# FileExtensionInfo.DelegateExecute Property 
 

For a verb invoked through COM and the `IExecuteCommand` interface, you can use this flag to retrieve the `IExecuteCommand` object's CLSID. 

 This CLSID is registered in the verb's command subkey as the `DelegateExecute` entry. 

 The verb is specified in the pwszExtra parameter in the call to `IQueryAssociations::GetString`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DelegateExecute { get; set; }
```

**VB**<br />
``` VB
Public Property DelegateExecute As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.DelegateExecute

instance.DelegateExecute = value
```

**C++**<br />
``` C++
public:
property String^ DelegateExecute {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member DelegateExecute : string with get, set

```


#### Property Value
Type: String<br />The CLSID of the associated `IExecuteCommand` object.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />