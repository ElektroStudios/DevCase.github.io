# CharDiff Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Text_CharDiff">CharDiff</a> struct.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CharDiff(
	long position,
	char oldChar,
	char newChar,
	CharDiffState diffState
)
```

**VB**<br />
``` VB
Public Sub New ( 
	position As Long,
	oldChar As Char,
	newChar As Char,
	diffState As CharDiffState
)
```

**VB Usage**<br />
``` VB Usage
Dim position As Long
Dim oldChar As Char
Dim newChar As Char
Dim diffState As CharDiffState

Dim instance As New CharDiff(position, 
	oldChar, newChar, diffState)
```

**C++**<br />
``` C++
public:
CharDiff(
	long long position, 
	wchar_t oldChar, 
	wchar_t newChar, 
	CharDiffState diffState
)
```

**F#**<br />
``` F#
new : 
        position : int64 * 
        oldChar : char * 
        newChar : char * 
        diffState : CharDiffState -> CharDiff
```


#### Parameters
&nbsp;<dl><dt>position</dt><dd>Type: System.Int64<br />The character position in the string.</dd><dt>oldChar</dt><dd>Type: System.Char<br />The original character in the string.</dd><dt>newChar</dt><dd>Type: System.Char<br />The current character in the string.</dd><dt>diffState</dt><dd>Type: <a href="T_DevCase_Core_Text_CharDiffState">DevCase.Core.Text.CharDiffState</a><br />The difference state of the current character in the original string.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Text_CharDiff">CharDiff Structure</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />