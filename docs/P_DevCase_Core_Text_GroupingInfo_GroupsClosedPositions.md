# GroupingInfo.GroupsClosedPositions Property 
 

Gets the positions in the string of the enclosed groups.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Dictionary<int, int> GroupsClosedPositions { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property GroupsClosedPositions As Dictionary(Of Integer, Integer)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As GroupingInfo
Dim value As Dictionary(Of Integer, Integer)

value = instance.GroupsClosedPositions

```

**C++**<br />
``` C++
public:
property Dictionary<int, int>^ GroupsClosedPositions {
	Dictionary<int, int>^ get ();
}
```

**F#**<br />
``` F#
member GroupsClosedPositions : Dictionary<int, int> with get

```


#### Property Value
Type: Dictionary(Int32, Int32)<br />The positions in the string of the enclosed groups.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_GroupingInfo">GroupingInfo Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />