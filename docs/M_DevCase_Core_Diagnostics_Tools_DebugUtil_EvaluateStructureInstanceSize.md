# DebugUtil.EvaluateStructureInstanceSize Method 
 

Determines whether the instance size (in bytes) of a Structure (ValueType) is smaller and/or greater than the size recommended by Microsoft guidelines.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool EvaluateStructureInstanceSize(
	ValueType struct,
	ref string refMessage
)
```

**VB**<br />
``` VB
Public Shared Function EvaluateStructureInstanceSize ( 
	struct As ValueType,
	ByRef refMessage As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim struct As ValueType
Dim refMessage As String
Dim returnValue As Boolean

returnValue = DebugUtil.EvaluateStructureInstanceSize(struct, 
	refMessage)
```

**C++**<br />
``` C++
public:
static bool EvaluateStructureInstanceSize(
	ValueType^ struct, 
	String^% refMessage
)
```

**F#**<br />
``` F#
static member EvaluateStructureInstanceSize : 
        struct : ValueType * 
        refMessage : string byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>struct</dt><dd>Type: System.ValueType<br />The source Structure (ValueType) to evaluate.</dd><dt>refMessage</dt><dd>Type: System.String<br />When the function returns, it contains a detailed message about the size of the source Structure.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the size of the source Structure is between the minimum and maximum recommended size by Microsoft guidelines; `false` (`False` in Visual Basic) otherwise.

## Examples
This is a code example. 
**VB**<br />
``` VB
' Declare a simple Structure.
Public Structure MyStructure
    Public Field1 As Object
    Public Field2 As Object
    Public Field3 As Object
    Public Field4 As Object
    ' Public Field5 As Object
End Structure

' Test the Structure size.
Dim struct As New MyStructure()
Dim message As String = String.Empty
Dim result As Boolean = EvaluateStructureInstanceSize(struct, message)

Debug.WriteLine(String.Format("Passed: {0}; Message: {1}", result, message))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_Tools_DebugUtil">DebugUtil Class</a><br /><a href="N_DevCase_Core_Diagnostics_Tools">DevCase.Core.Diagnostics.Tools Namespace</a><br />