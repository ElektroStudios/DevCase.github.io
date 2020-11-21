# ResourceUtil.GetEmbeddedResourceAsImage Method (String)
 

Gets an embedded resource of type Image in the calling assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Image GetEmbeddedResourceAsImage(
	string name
)
```

**VB**<br />
``` VB
Public Shared Function GetEmbeddedResourceAsImage ( 
	name As String
) As Image
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim returnValue As Image

returnValue = ResourceUtil.GetEmbeddedResourceAsImage(name)
```

**C++**<br />
``` C++
public:
static Image^ GetEmbeddedResourceAsImage(
	String^ name
)
```

**F#**<br />
``` F#
static member GetEmbeddedResourceAsImage : 
        name : string -> Image 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the resource.</dd></dl>

#### Return Value
Type: Image<br />The embedded resource as Image.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim img As Image = GetEmbeddedResourceAsImage("file.png")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsImage">GetEmbeddedResourceAsImage Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />