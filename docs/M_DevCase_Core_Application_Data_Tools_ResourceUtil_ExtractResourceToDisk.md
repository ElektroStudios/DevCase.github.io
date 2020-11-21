# ResourceUtil.ExtractResourceToDisk Method 
 

Extracts a resource to disk.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ExtractResourceToDisk(
	byte[] resource,
	string targetFilepath,
	bool overwrite = false
)
```

**VB**<br />
``` VB
Public Shared Sub ExtractResourceToDisk ( 
	resource As Byte(),
	targetFilepath As String,
	Optional overwrite As Boolean = false
)
```

**VB Usage**<br />
``` VB Usage
Dim resource As Byte()
Dim targetFilepath As String
Dim overwrite As BooleanResourceUtil.ExtractResourceToDisk(resource, 
	targetFilepath, overwrite)
```

**C++**<br />
``` C++
public:
static void ExtractResourceToDisk(
	array<unsigned char>^ resource, 
	String^ targetFilepath, 
	bool overwrite = false
)
```

**F#**<br />
``` F#
static member ExtractResourceToDisk : 
        resource : byte[] * 
        targetFilepath : string * 
        ?overwrite : bool 
(* Defaults:
        let _overwrite = defaultArg overwrite false
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>resource</dt><dd>Type: System.Byte[]<br />The resource to extract.</dd><dt>targetFilepath</dt><dd>Type: System.String<br />The target filepath where to save the resource data.</dd><dt>overwrite (Optional)</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), overwites any existing file, otherwise, if the file already exists, a IOException exception is thrown.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
ExtractResourceToDisk(My.Resources.MyTextfile, "C:\File.txt")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />