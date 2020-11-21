# StringUtil.WordLists.Countries Property 
 

Gets a word-list that contains country names (eg. China, Spain, United States).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<string> Countries { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Countries As ReadOnlyCollection(Of String)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of String)

value = StringUtil.WordLists.Countries

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<String^>^ Countries {
	ReadOnlyCollection<String^>^ get ();
}
```

**F#**<br />
``` F#
static member Countries : ReadOnlyCollection<string> with get

```


#### Property Value
Type: ReadOnlyCollection(String)<br />The country names.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_Tools_StringUtil_WordLists">StringUtil.WordLists Class</a><br /><a href="N_DevCase_Core_Text_Tools">DevCase.Core.Text.Tools Namespace</a><br />