# FileExtensionInfo.DefaultIcon Property 
 

Gets the path to the icon resources to use by default for this association. 

 Positive numbers indicate an index into the dll's resource table, while negative numbers indicate a resource ID. 

 An example of the syntax for the resource is "C:\myfolder\myfile.dll,-1".

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DefaultIcon { get; set; }
```

**VB**<br />
``` VB
Public Property DefaultIcon As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.DefaultIcon

instance.DefaultIcon = value
```

**C++**<br />
``` C++
public:
property String^ DefaultIcon {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member DefaultIcon : string with get, set

```


#### Property Value
Type: String<br />A command string associated with a Shell verb.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />