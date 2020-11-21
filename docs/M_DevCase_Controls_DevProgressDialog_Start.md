# DevProgressDialog.Start Method 
 

Starts the progress dialog box.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void Start(
	IWin32Window hwndParent
)
```

**VB**<br />
``` VB
Public Overridable Sub Start ( 
	hwndParent As IWin32Window
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim hwndParent As IWin32Window

instance.Start(hwndParent)
```

**C++**<br />
``` C++
public:
virtual void Start(
	IWin32Window^ hwndParent
)
```

**F#**<br />
``` F#
abstract Start : 
        hwndParent : IWin32Window -> unit 
override Start : 
        hwndParent : IWin32Window -> unit 
```


#### Parameters
&nbsp;<dl><dt>hwndParent</dt><dd>Type: System.Windows.Forms.IWin32Window<br />The progress dialog box's parent window. 

 This value can be a null reference (`Nothing` in Visual Basic).</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />