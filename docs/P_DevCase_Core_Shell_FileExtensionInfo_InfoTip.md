# FileExtensionInfo.InfoTip Property 
 

Corresponds to the InfoTip registry value. 

 Gets an info tip for an item, or list of properties in the form of an `IPropertyDescriptionList` from which to create an info tip, such as when hovering the cursor over a file name. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string InfoTip { get; set; }
```

**VB**<br />
``` VB
Public Property InfoTip As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.InfoTip

instance.InfoTip = value
```

**C++**<br />
``` C++
public:
property String^ InfoTip {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member InfoTip : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.FileExtensionInfo.InfoTip"\]

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />