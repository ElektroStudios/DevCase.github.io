# DevMessageBox Constructor (Control, Int32)
 

Initializes a new instance of the <a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DevMessageBox(
	Control owner,
	int timeOut
)
```

**VB**<br />
``` VB
Public Sub New ( 
	owner As Control,
	timeOut As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim owner As Control
Dim timeOut As Integer

Dim instance As New DevMessageBox(owner, timeOut)
```

**C++**<br />
``` C++
public:
DevMessageBox(
	Control^ owner, 
	int timeOut
)
```

**F#**<br />
``` F#
new : 
        owner : Control * 
        timeOut : int -> DevMessageBox
```


#### Parameters
&nbsp;<dl><dt>owner</dt><dd>Type: System.Windows.Forms.Control<br />T The Control that owns this <a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox</a>.</dd><dt>timeOut</dt><dd>Type: System.Int32<br />The time interval to auto-close this <a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox</a>, in milliseconds. 

 Default value is 0, which means Infinite.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DevMessageBox">DevMessageBox Class</a><br /><a href="Overload_DevCase_Core_Application_UserInterface_DevMessageBox__ctor">DevMessageBox Overload</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />