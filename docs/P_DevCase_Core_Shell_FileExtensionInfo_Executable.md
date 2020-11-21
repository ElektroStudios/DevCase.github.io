# FileExtensionInfo.Executable Property 
 

Gets an executable from a Shell verb command string. 

 For example, this string is found as the (Default) value for a subkey such as HKEY_CLASSES_ROOT\ApplicationName\shell\Open\command.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string Executable { get; set; }
```

**VB**<br />
``` VB
Public Property Executable As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.Executable

instance.Executable = value
```

**C++**<br />
``` C++
public:
property String^ Executable {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member Executable : string with get, set

```


#### Property Value
Type: String<br />An executable from a Shell verb command string.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />