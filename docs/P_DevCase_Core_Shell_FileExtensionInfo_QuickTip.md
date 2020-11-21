# FileExtensionInfo.QuickTip Property 
 

Corresponds to the QuickTip registry value. Same as <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a>, except that it always returns a list of property names in the form of an `IPropertyDescriptionList`. 

 The difference between this value and <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a> is that this returns properties that are safe for any scenario that causes slow property retrieval, such as offline or slow networks. 

 Some of the properties returned from <a href="P_DevCase_Core_Shell_FileExtensionInfo_InfoTip">InfoTip</a> might not be appropriate for slow property retrieval scenarios. 

 The list of properties can be parsed with `PSGetPropertyDescriptionListFromString`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string QuickTip { get; set; }
```

**VB**<br />
``` VB
Public Property QuickTip As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.QuickTip

instance.QuickTip = value
```

**C++**<br />
``` C++
public:
property String^ QuickTip {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member QuickTip : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.Core.Shell.FileExtensionInfo.QuickTip"\]

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />