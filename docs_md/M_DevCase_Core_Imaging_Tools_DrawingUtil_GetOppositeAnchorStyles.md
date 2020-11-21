# DrawingUtil.GetOppositeAnchorStyles Method 
 

Gets the opposite anchor style of the specified AnchorStyles.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static AnchorStyles GetOppositeAnchorStyles(
	AnchorStyles anchor
)
```

**VB**<br />
``` VB
Public Shared Function GetOppositeAnchorStyles ( 
	anchor As AnchorStyles
) As AnchorStyles
```

**VB Usage**<br />
``` VB Usage
Dim anchor As AnchorStyles
Dim returnValue As AnchorStyles

returnValue = DrawingUtil.GetOppositeAnchorStyles(anchor)
```

**C++**<br />
``` C++
public:
static AnchorStyles GetOppositeAnchorStyles(
	AnchorStyles anchor
)
```

**F#**<br />
``` F#
static member GetOppositeAnchorStyles : 
        anchor : AnchorStyles -> AnchorStyles 

```


#### Parameters
&nbsp;<dl><dt>anchor</dt><dd>Type: System.Windows.Forms.AnchorStyles<br />The anchor.</dd></dl>

#### Return Value
Type: AnchorStyles<br />The resulting AnchorStyles.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim result As AnchorStyles = GetOppositeAnchorStyles(AnchorStyles.Bottom Or AnchorStyles.Left)
Console.WriteLine(result.ToString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Tools_DrawingUtil">DrawingUtil Class</a><br /><a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />