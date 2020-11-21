# MruUtil.Load(*T*) Method (List(MruItem(*T*)), String)
 

Loads a serialized List(T) from the specified local file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void Load<T>(
	ref List<MruItem<T>> refCol,
	string filepath
)

```

**VB**<br />
``` VB
Public Shared Sub Load(Of T) ( 
	ByRef refCol As List(Of MruItem(Of T)),
	filepath As String
)
```

**VB Usage**<br />
``` VB Usage
Dim refCol As List(Of MruItem(Of T))
Dim filepath As StringMruUtil.Load(refCol, filepath)
```

**C++**<br />
``` C++
public:
generic<typename T>
static void Load(
	List<MruItem<T>^>^% refCol, 
	String^ filepath
)
```

**F#**<br />
``` F#
static member Load : 
        refCol : List<MruItem<'T>> byref * 
        filepath : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>refCol</dt><dd>Type: System.Collections.Generic.List(<a href="T_DevCase_Core_Application_Data_MruItem_1">MruItem</a>(*T*))<br />The target List(T).</dd><dt>filepath</dt><dd>Type: System.String<br />The source filepath.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As New List(Of MruItem(Of String))
' ...

Load(mruItems, ".\MRU.tmp")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_MruUtil">MruUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_MruUtil_Load">Load Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />