# MruUtil.Load(*T*) Method (String)
 

Loads a serialized List(T) from the specified local file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<MruFileItem> Load<T>(
	string filepath
)
where T : MruFileItem

```

**VB**<br />
``` VB
Public Shared Function Load(Of T As MruFileItem) ( 
	filepath As String
) As List(Of MruFileItem)
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As List(Of MruFileItem)

returnValue = MruUtil.Load(filepath)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : MruFileItem
static List<MruFileItem^>^ Load(
	String^ filepath
)
```

**F#**<br />
``` F#
static member Load : 
        filepath : string -> List<MruFileItem>  when 'T : MruFileItem

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source filepath.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Return Value
Type: List(<a href="T_DevCase_Core_Application_Data_MruFileItem">MruFileItem</a>)<br />The resulting List(T).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As List(Of MruFileItem) = Load(Of MruFileItem)(".\MRU.tmp").ToList
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_MruUtil">MruUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_MruUtil_Load">Load Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />