# PropertyGridInputDialog.ShowDialog Method (IWin32Window)
 

Runs this dialog box with the specified owner.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual DialogResult ShowDialog(
	IWin32Window owner
)
```

**VB**<br />
``` VB
Public Overridable Function ShowDialog ( 
	owner As IWin32Window
) As DialogResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As PropertyGridInputDialog
Dim owner As IWin32Window
Dim returnValue As DialogResult

returnValue = instance.ShowDialog(owner)
```

**C++**<br />
``` C++
public:
virtual DialogResult ShowDialog(
	IWin32Window^ owner
)
```

**F#**<br />
``` F#
abstract ShowDialog : 
        owner : IWin32Window -> DialogResult 
override ShowDialog : 
        owner : IWin32Window -> DialogResult 
```


#### Parameters
&nbsp;<dl><dt>owner</dt><dd>Type: System.Windows.Forms.IWin32Window<br />Any object that implements IWin32Window that represents the top-level window that will own the modal dialog box.</dd></dl>

#### Return Value
Type: DialogResult<br />OK if the user clicks OK in the dialog box; otherwise, Cancel.

## See Also


#### Reference
<a href="T_DevCase_Controls_PropertyGridInputDialog">PropertyGridInputDialog Class</a><br /><a href="Overload_DevCase_Controls_PropertyGridInputDialog_ShowDialog">ShowDialog Overload</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />