# IProgressDialog.SetLine Method 
 

Displays a message in the progress dialog.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetLine(
	uint lineNum,
	string text,
	bool compactPath,
	IntPtr reserved = null
)
```

**VB**<br />
``` VB
Sub SetLine ( 
	lineNum As UInteger,
	text As String,
	compactPath As Boolean,
	Optional reserved As IntPtr = Nothing
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IProgressDialog
Dim lineNum As UInteger
Dim text As String
Dim compactPath As Boolean
Dim reserved As IntPtr

instance.SetLine(lineNum, text, compactPath, 
	reserved)
```

**C++**<br />
``` C++
void SetLine(
	unsigned int lineNum, 
	String^ text, 
	bool compactPath, 
	IntPtr reserved = nullptr
)
```

**F#**<br />
``` F#
abstract SetLine : 
        lineNum : uint32 * 
        text : string * 
        compactPath : bool * 
        ?reserved : IntPtr 
(* Defaults:
        let _reserved = defaultArg reserved null
*)
-> unit 

```


#### Parameters
&nbsp;<dl><dt>lineNum</dt><dd>Type: System.UInt32<br />The line number on which the text is to be displayed. Currently there are three lines—1, 2, and 3. 

 If the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProgressDialogFlags">AutoTime</a> flag was included in the flags parameter when <a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog_StartProgressDialog">StartProgressDialog(IntPtr, Object, ProgressDialogFlags, IntPtr)</a> was called, only lines 1 and 2 can be used. 

 The estimated time will be displayed on line 3.</dd><dt>text</dt><dd>Type: System.String<br />A null-terminated Unicode string that contains the text.</dd><dt>compactPath</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to have path strings compacted if they are too large to fit on a line. 

 The paths are compacted with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathCompactPath">PathCompactPath(IntPtr, StringBuilder, UInt32)</a> function.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />Reserved. Set to Zero.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IProgressDialog">IProgressDialog Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />