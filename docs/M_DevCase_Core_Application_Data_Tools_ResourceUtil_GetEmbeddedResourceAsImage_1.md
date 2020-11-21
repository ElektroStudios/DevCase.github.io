# ResourceUtil.GetEmbeddedResourceAsImage Method (String, Assembly)
 

Gets an embedded resource of type Image in the specified Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image GetEmbeddedResourceAsImage(
	string name,
	Assembly asm
)
```

**VB**<br />
``` VB
Public Shared Function GetEmbeddedResourceAsImage ( 
	name As String,
	asm As Assembly
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim asm As [Assembly]
Dim returnValue As Image

returnValue = ResourceUtil.GetEmbeddedResourceAsImage(name, 
	asm)
```

**C++**<br />
``` C++
public:
static Image^ GetEmbeddedResourceAsImage(
	String^ name, 
	Assembly^ asm
)
```

**F#**<br />
``` F#
static member GetEmbeddedResourceAsImage : 
        name : string * 
        asm : Assembly -> Image 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the resource.</dd><dt>asm</dt><dd>Type: System.Reflection.Assembly<br />The Assembly to look for the resource.</dd></dl>

#### Return Value
Type: Image<br />The embedded resource as Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = GetEmbeddedResourceAsImage("file.png", Assembly.GetCallingAssembly())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsImage">GetEmbeddedResourceAsImage Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />