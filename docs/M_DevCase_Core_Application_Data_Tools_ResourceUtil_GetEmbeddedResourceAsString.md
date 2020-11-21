# ResourceUtil.GetEmbeddedResourceAsString Method (String, Assembly, Encoding)
 

Gets an embedded resource of type String in the specified Assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string GetEmbeddedResourceAsString(
	string name,
	Assembly asm,
	Encoding enc = null
)
```

**VB**<br />
``` VB
Public Shared Function GetEmbeddedResourceAsString ( 
	name As String,
	asm As Assembly,
	Optional enc As Encoding = Nothing
) As String
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim asm As [Assembly]
Dim enc As Encoding
Dim returnValue As String

returnValue = ResourceUtil.GetEmbeddedResourceAsString(name, 
	asm, enc)
```

**C++**<br />
``` C++
public:
static String^ GetEmbeddedResourceAsString(
	String^ name, 
	Assembly^ asm, 
	Encoding^ enc = nullptr
)
```

**F#**<br />
``` F#
static member GetEmbeddedResourceAsString : 
        name : string * 
        asm : Assembly * 
        ?enc : Encoding 
(* Defaults:
        let _enc = defaultArg enc null
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the resource.</dd><dt>asm</dt><dd>Type: System.Reflection.Assembly<br />The Assembly to look for the resource.</dd><dt>enc (Optional)</dt><dd>Type: System.Text.Encoding<br />\[Missing <param name="enc"/> documentation for "M:DevCase.Core.Application.Data.Tools.ResourceUtil.GetEmbeddedResourceAsString(System.String,System.Reflection.Assembly,System.Text.Encoding)"\]</dd></dl>

#### Return Value
Type: String<br />The embedded resource as String.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = GetEmbeddedResourceAsString("file.txt", Assembly.GetCallingAssembly(), Encoding.Default)
Console.WriteLine(str)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_ResourceUtil_GetEmbeddedResourceAsString">GetEmbeddedResourceAsString Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />