# GroupingInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Text_GroupingInfo">GroupingInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public GroupingInfo(
	string source,
	List<GroupingCharsInfo> groupingChars,
	bool hasClosedGroups,
	bool hasOpenGroups,
	int groupsClosedCount,
	int groupsOpenCount,
	Dictionary<int, int> groupsClosedPositions,
	List<int> groupsOpenPositions
)
```

**VB**<br />
``` VB
Public Sub New ( 
	source As String,
	groupingChars As List(Of GroupingCharsInfo),
	hasClosedGroups As Boolean,
	hasOpenGroups As Boolean,
	groupsClosedCount As Integer,
	groupsOpenCount As Integer,
	groupsClosedPositions As Dictionary(Of Integer, Integer),
	groupsOpenPositions As List(Of Integer)
)
```

**VB Usage**<br />
``` VB Usage
Dim source As String
Dim groupingChars As List(Of GroupingCharsInfo)
Dim hasClosedGroups As Boolean
Dim hasOpenGroups As Boolean
Dim groupsClosedCount As Integer
Dim groupsOpenCount As Integer
Dim groupsClosedPositions As Dictionary(Of Integer, Integer)
Dim groupsOpenPositions As List(Of Integer)

Dim instance As New GroupingInfo(source, 
	groupingChars, hasClosedGroups, 
	hasOpenGroups, groupsClosedCount, 
	groupsOpenCount, groupsClosedPositions, 
	groupsOpenPositions)
```

**C++**<br />
``` C++
public:
GroupingInfo(
	String^ source, 
	List<GroupingCharsInfo^>^ groupingChars, 
	bool hasClosedGroups, 
	bool hasOpenGroups, 
	int groupsClosedCount, 
	int groupsOpenCount, 
	Dictionary<int, int>^ groupsClosedPositions, 
	List<int>^ groupsOpenPositions
)
```

**F#**<br />
``` F#
new : 
        source : string * 
        groupingChars : List<GroupingCharsInfo> * 
        hasClosedGroups : bool * 
        hasOpenGroups : bool * 
        groupsClosedCount : int * 
        groupsOpenCount : int * 
        groupsClosedPositions : Dictionary<int, int> * 
        groupsOpenPositions : List<int> -> GroupingInfo
```


#### Parameters
&nbsp;<dl><dt>source</dt><dd>Type: System.String<br />The source string.</dd><dt>groupingChars</dt><dd>Type: System.Collections.Generic.List(<a href="T_DevCase_Core_Text_GroupingCharsInfo">GroupingCharsInfo</a>)<br />The grouping characters.</dd><dt>hasClosedGroups</dt><dd>Type: System.Boolean<br />A value that determines whether the source string contains enclosed groups.</dd><dt>hasOpenGroups</dt><dd>Type: System.Boolean<br />A value that determines whether the source string contains open groups.</dd><dt>groupsClosedCount</dt><dd>Type: System.Int32<br />The amount of enclosed groups.</dd><dt>groupsOpenCount</dt><dd>Type: System.Int32<br />The amount of open groups.</dd><dt>groupsClosedPositions</dt><dd>Type: System.Collections.Generic.Dictionary(Int32, Int32)<br />The positions in the string of the enclosed groups.</dd><dt>groupsOpenPositions</dt><dd>Type: System.Collections.Generic.List(Int32)<br />The positions in the string of the open groups.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_GroupingInfo">GroupingInfo Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />