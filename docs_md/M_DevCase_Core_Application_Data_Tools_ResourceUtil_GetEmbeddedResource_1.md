# ResourceUtil.GetEmbeddedResource Method (String, Assembly)
 

Gets an embedded resource in the specified Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] GetEmbeddedResource(
	string name,
	Assembly asm
)
```

**VB**<br />
``` VB
Public Shared Function GetEmbeddedResource ( 
	name As String,
	asm As Assembly
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim asm As [Assembly]
Dim returnValue As Byte()

returnValue = ResourceUtil.GetEmbeddedResource(name, 
	asm)
```

**C++**<br />
``` C++
public:
static array<unsigned char>^ GetEmbeddedResource(
	String^ name, 
	Assembly^ asm
)
```

**F#**<br />
``` F#
static member GetEmbeddedResource : 
        name : string * 
        asm : Assembly -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the resource.</dd><dt>asm</dt><dd>Type: System.Reflection.Assembly<br />The Assembly to look for the resource.</dd></dl>

#### Return Value
Type: Byte[]<br />A Byte array containing the bytes of the embedded resource.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim data As Byte() = GetEmbeddedResource("file.txt", Assembly.GetCallingAssembly())
Dim str As String = Encoding.Default.GetString(data)
Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResource">GetEmbeddedResource Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />