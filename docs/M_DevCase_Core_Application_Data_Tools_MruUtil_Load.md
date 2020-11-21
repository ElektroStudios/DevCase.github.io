# MruUtil.Load Method (List(MruFileItem), String)
 

Loads a serialized List(T) from the specified local file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Load(
	ref List<MruFileItem> refCol,
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Sub Load ( 
	ByRef refCol As List(Of MruFileItem),
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim refCol As List(Of MruFileItem)
Dim filepath As StringMruUtil.Load(refCol, filepath)
```

**C++**<br />
``` C++
public:
static void Load(
	List<MruFileItem^>^% refCol, 
	String^ filepath
)
```

**F#**<br />
``` F#
static member Load : 
        refCol : List<MruFileItem> byref * 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>refCol</dt><dd>Type: System.Collections.Generic.List(<a href="T_DevCase_Core_Application_Data_MruFileItem">MruFileItem</a>)<br />The target List(T).</dd><dt>filepath</dt><dd>Type: System.String<br />The source filepath.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As New List(Of MruFileItem)
' ...

Load(mruItems, ".\MRU.tmp")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_MruUtil">MruUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_MruUtil_Load">Load Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />