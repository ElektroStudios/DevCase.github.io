# ScintillaNetUtil.AddLineNumbers Method 
 

Adds line numbers on the specified Scintilla editor.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_ScintillaNet">DevCase.ThirdParty.ScintillaNet</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void AddLineNumbers(
	Scintilla editor,
	int marginIndex
)
```

**VB**<br />
``` VB
Public Shared Sub AddLineNumbers ( 
	editor As Scintilla,
	marginIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim editor As Scintilla
Dim marginIndex As Integer

ScintillaNetUtil.AddLineNumbers(editor, marginIndex)
```

**C++**<br />
``` C++
public:
static void AddLineNumbers(
	Scintilla^ editor, 
	int marginIndex
)
```

**F#**<br />
``` F#
static member AddLineNumbers : 
        editor : Scintilla * 
        marginIndex : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>editor</dt><dd>Type: Scintilla<br />The source Scintilla editor.</dd><dt>marginIndex</dt><dd>Type: System.Int32<br />The margin index of the Margins where to display the line numbers.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_ScintillaNet_ScintillaNetUtil">ScintillaNetUtil Class</a><br /><a href="N_DevCase_ThirdParty_ScintillaNet">DevCase.ThirdParty.ScintillaNet Namespace</a><br />