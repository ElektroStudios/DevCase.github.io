# MruUtil.Save Method (List(MruFileItem), String)
 

Saves the specified List(T) to local file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Save(
	List<MruFileItem> mruCol,
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Sub Save ( 
	mruCol As List(Of MruFileItem),
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim mruCol As List(Of MruFileItem)
Dim filepath As StringMruUtil.Save(mruCol, filepath)
```

**C++**<br />
``` C++
public:
static void Save(
	List<MruFileItem^>^ mruCol, 
	String^ filepath
)
```

**F#**<br />
``` F#
static member Save : 
        mruCol : List<MruFileItem> * 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>mruCol</dt><dd>Type: System.Collections.Generic.List(<a href="T_DevCase_Core_Application_Data_MruFileItem">MruFileItem</a>)<br />The source List(T).</dd><dt>filepath</dt><dd>Type: System.String<br />The target filepath.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As New List(Of MruFileItem)

Save(mruItems, ".\MRU.tmp")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_MruUtil">MruUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_MruUtil_Save">Save Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />