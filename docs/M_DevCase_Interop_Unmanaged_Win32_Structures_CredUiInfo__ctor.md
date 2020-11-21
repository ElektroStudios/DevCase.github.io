# CredUiInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo">CredUiInfo</a> struct.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CredUiInfo(
	IntPtr hwndOwner,
	string caption,
	string text
)
```

**VB**<br />
``` VB
Public Sub New ( 
	hwndOwner As IntPtr,
	caption As String,
	text As String
)
```

**VB Usage**<br />
``` VB Usage
Dim hwndOwner As IntPtr
Dim caption As String
Dim text As String

Dim instance As New CredUiInfo(hwndOwner, 
	caption, text)
```

**C++**<br />
``` C++
public:
CredUiInfo(
	IntPtr hwndOwner, 
	String^ caption, 
	String^ text
)
```

**F#**<br />
``` F#
new : 
        hwndOwner : IntPtr * 
        caption : string * 
        text : string -> CredUiInfo
```


#### Parameters
&nbsp;<dl><dt>hwndOwner</dt><dd>Type: System.IntPtr<br />The handle to the parent window of the dialog box. 

 The dialog box is modal with respect to the parent window. 

 If this member is Zero, the desktop is the parent window of the dialog box.</dd><dt>caption</dt><dd>Type: System.String<br />The title for the dialog box.</dd><dt>text</dt><dd>Type: System.String<br />A brief message to display in the dialog box.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_CredUiInfo">CredUiInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />