# FileExtensionInfo.ShellExtension Property 
 

For an object that has a Shell extension associated with it, you can use this to retrieve the CLSID of that Shell extension object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ShellExtension { get; set; }
```

**VB**<br />
``` VB
Public Property ShellExtension As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.ShellExtension

instance.ShellExtension = value
```

**C++**<br />
``` C++
public:
property String^ ShellExtension {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member ShellExtension : string with get, set

```


#### Property Value
Type: String<br />The CLSID of the associated Shell extension object.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />