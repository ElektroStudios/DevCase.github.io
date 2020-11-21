# ScintillaNetUtil.RemoveLineNumbers Method (Scintilla, Int32, Int32)
 

Removes the line numbers on the specified Scintilla editor that were previously added by calling <a href="M_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_AddLineNumbers">AddLineNumbers(Scintilla, Int32)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ScintillaNet">DevCase.ThirdParty.ScintillaNet</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveLineNumbers(
	Scintilla editor,
	int marginIndex,
	int marginWidth
)
```

**VB**<br />
``` VB
Public Shared Sub RemoveLineNumbers ( 
	editor As Scintilla,
	marginIndex As Integer,
	marginWidth As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim editor As Scintilla
Dim marginIndex As Integer
Dim marginWidth As Integer

ScintillaNetUtil.RemoveLineNumbers(editor, marginIndex, 
	marginWidth)
```

**C++**<br />
``` C++
public:
static void RemoveLineNumbers(
	Scintilla^ editor, 
	int marginIndex, 
	int marginWidth
)
```

**F#**<br />
``` F#
static member RemoveLineNumbers : 
        editor : Scintilla * 
        marginIndex : int * 
        marginWidth : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>editor</dt><dd>Type: Scintilla<br />The source Scintilla editor.</dd><dt>marginIndex</dt><dd>Type: System.Int32<br />The margin index of the Margins where to remove the line numbers.</dd><dt>marginWidth</dt><dd>Type: System.Int32<br />Restores the width of the specified Margins to the desired value.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil">ScintillaNetUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil_RemoveLineNumbers">RemoveLineNumbers Overload</a><br /><a href="N_DevCase_ThirdParty_ScintillaNet">DevCase.ThirdParty.ScintillaNet Namespace</a><br />