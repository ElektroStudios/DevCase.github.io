# ResourceUtil.GetEmbeddedResource Method (String)
 

Gets an embedded resource in the calling assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] GetEmbeddedResource(
	string name
)
```

**VB**<br />
``` VB
Public Shared Function GetEmbeddedResource ( 
	name As String
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim returnValue As Byte()

returnValue = ResourceUtil.GetEmbeddedResource(name)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ GetEmbeddedResource(
	String^ name
)
```

**F#**<br />
``` F#
static member GetEmbeddedResource : 
        name : string -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the resource.</dd></dl>

#### Return Value
Type: Byte[]<br />A Byte array containing the bytes of the embedded resource.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data As Byte() = GetEmbeddedResource("file.txt")
Dim str As String = Encoding.Default.GetString(data)
Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResource">GetEmbeddedResource Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />