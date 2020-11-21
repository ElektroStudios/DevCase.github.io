# TextMargins.Equals Method (TextMargins)
 

Determines whether the specified <a href="T_DevCase_Core_Design_TextMargins">TextMargins</a> is equal to this instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Advanced)]
public bool Equals(
	TextMargins margins
)
```

**VB**<br />
``` VB
<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>
Public Function Equals ( 
	margins As TextMargins
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextMargins
Dim margins As TextMargins
Dim returnValue As Boolean

returnValue = instance.Equals(margins)
```

**C++**<br />
``` C++
public:
[EditorBrowsableAttribute(EditorBrowsableState::Advanced)]
bool Equals(
	TextMargins^ margins
)
```

**F#**<br />
``` F#
[<EditorBrowsableAttribute(EditorBrowsableState.Advanced)>]
member Equals : 
        margins : TextMargins -> bool 

```


#### Parameters
&nbsp;<dl><dt>margins</dt><dd>Type: <a href="T_DevCase_Core_Design_TextMargins">DevCase.Core.Design.TextMargins</a><br />Another <a href="T_DevCase_Core_Design_TextMargins">TextMargins</a> to compare to.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the specified <a href="T_DevCase_Core_Design_TextMargins">TextMargins</a> is equal to this instance; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Design_TextMargins">TextMargins Class</a><br /><a href="Overload_DevCase_Core_Design_TextMargins_Equals">Equals Overload</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />