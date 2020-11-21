# ResourceUtil.GetResourcesOf(*T*) Method 
 

Gets the resources of the specified type in the calling assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<DictionaryEntry> GetResourcesOf<T>(
	CultureInfo culture = null
)

```

**VB**<br />
``` VB
Public Shared Function GetResourcesOf(Of T) ( 
	Optional culture As CultureInfo = Nothing
) As IEnumerable(Of DictionaryEntry)
```

**VB Usage**<br />
``` VB Usage
Dim culture As CultureInfo
Dim returnValue As IEnumerable(Of DictionaryEntry)

returnValue = ResourceUtil.GetResourcesOf(culture)
```

**C++**<br />
``` C++
public:
generic<typename T>
static IEnumerable<DictionaryEntry>^ GetResourcesOf(
	CultureInfo^ culture = nullptr
)
```

**F#**<br />
``` F#
static member GetResourcesOf : 
        ?culture : CultureInfo 
(* Defaults:
        let _culture = defaultArg culture null
*)
-> IEnumerable<DictionaryEntry> 

```


#### Parameters
&nbsp;<dl><dt>culture (Optional)</dt><dd>Type: System.Globalization.CultureInfo<br />The resource culture</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the resource to find.</dd></dl>

#### Return Value
Type: IEnumerable(DictionaryEntry)<br />IEnumerable(T).

## Examples
This is a code example to get all String resources. 
**VB**<br />
``` VB
Dim resources As IEnumerable(Of DictionaryEntry) = GetResourcesOf(Of Bitmap)()

For Each resource As DictionaryEntry In resources

    MsgBox(resource.Key)            '  Resource Name
    MsgBox(resource.Value.ToString()) '  Resource Data

Next resource
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_Tools_ResourceUtil">ResourceUtil Class</a><br /><a href="N_DevCase_Core_Application_Data_Tools">DevCase.Core.Application.Data.Tools Namespace</a><br />