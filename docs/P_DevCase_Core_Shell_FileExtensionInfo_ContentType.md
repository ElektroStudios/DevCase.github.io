# FileExtensionInfo.ContentType Property 
 

Gets a general type of MIME file association, such as 'image' and 'bmp', so that applications can make general assumptions about a specific file type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ContentType { get; set; }
```

**VB**<br />
``` VB
Public Property ContentType As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.ContentType

instance.ContentType = value
```

**C++**<br />
``` C++
public:
property String^ ContentType {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member ContentType : string with get, set

```


#### Property Value
Type: String<br />A general type of MIME file association, such as 'image' and 'bmp'.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />