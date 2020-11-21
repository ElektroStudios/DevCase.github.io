# ClipboardUtil.CountChars Method 
 

Counts the text characters contained in the Clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int CountChars(
	TextDataFormat format = TextDataFormat.Text
)
```

**VB**<br />
``` VB
Public Shared Function CountChars ( 
	Optional format As TextDataFormat = TextDataFormat.Text
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim format As TextDataFormat
Dim returnValue As Integer

returnValue = ClipboardUtil.CountChars(format)
```

**C++**<br />
``` C++
public:
static int CountChars(
	TextDataFormat format = TextDataFormat::Text
)
```

**F#**<br />
``` F#
static member CountChars : 
        ?format : TextDataFormat 
(* Defaults:
        let _format = defaultArg format TextDataFormat.Text
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>format (Optional)</dt><dd>Type: System.Windows.Forms.TextDataFormat<br />The specific TextDataFormat, default is Text.</dd></dl>

#### Return Value
Type: Int32<br />If the clipboard content is text, the value is the amount of characters. 

 If the clipboard content is not text, the value is `0`.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_ClipboardUtil">ClipboardUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />