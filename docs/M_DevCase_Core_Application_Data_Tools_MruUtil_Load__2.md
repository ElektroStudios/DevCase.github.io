# MruUtil.Load(*A*, *B*) Method (String)
 

Loads a serialized List(T) from the specified local file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static List<MruItem<A>> Load<A, B>(
	string filepath
)
where B : MruItem<A>

```

**VB**<br />
``` VB
Public Shared Function Load(Of A, B As MruItem(Of A)) ( 
	filepath As String
) As List(Of MruItem(Of A))
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As List(Of MruItem(Of A))

returnValue = MruUtil.Load(filepath)
```

**C++**<br />
``` C++
public:
generic<typename A, typename B>
where B : MruItem<A>
static List<MruItem<A>^>^ Load(
	String^ filepath
)
```

**F#**<br />
``` F#
static member Load : 
        filepath : string -> List<MruItem<'A>>  when 'B : MruItem<'A>

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The source filepath.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>A</dt><dd>The type.</dd><dt>B</dt><dd>The type.</dd></dl>

#### Return Value
Type: List(<a href="T_DevCase_Core_Application_Data_MruItem_1">MruItem</a>(*A*))<br />The resulting List(T).

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mruItems As List(Of MruItem(Of String)) = Load(Of String, MruItem(Of String))(".\MRU.tmp")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_MruUtil">MruUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Data_Tools_MruUtil_Load">Load Overload</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />