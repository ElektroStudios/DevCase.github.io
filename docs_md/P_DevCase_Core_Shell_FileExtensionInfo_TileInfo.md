# FileExtensionInfo.TileInfo Property 
 

Corresponds to the TileInfo registry value. 

 Contains a list of properties to be displayed for a particular file type in a Windows Explorer window that is in tile view. 

 This is the same as <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a>, but, like <a href="P_DevCase_Core_Shell_FileExtensionInfo_QuickTip">QuickTip</a>, it also returns a list of property names in the form of an `IPropertyDescriptionList`. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string TileInfo { get; set; }
```

**VB**<br />
``` VB
Public Property TileInfo As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.TileInfo

instance.TileInfo = value
```

**C++**<br />
``` C++
public:
property String^ TileInfo {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member TileInfo : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.FileExtensionInfo.TileInfo"\]

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />