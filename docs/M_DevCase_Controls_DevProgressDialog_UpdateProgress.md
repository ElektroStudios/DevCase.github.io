# DevProgressDialog.UpdateProgress Method 
 

Updates the progress dialog box with the current state of the operation.

**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual void UpdateProgress(
	ulong completed,
	ulong total
)
```

**VB**<br />
``` VB
Public Overridable Sub UpdateProgress ( 
	completed As ULong,
	total As ULong
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevProgressDialog
Dim completed As ULong
Dim total As ULong

instance.UpdateProgress(completed, total)
```

**C++**<br />
``` C++
public:
virtual void UpdateProgress(
	unsigned long long completed, 
	unsigned long long total
)
```

**F#**<br />
``` F#
abstract UpdateProgress : 
        completed : uint64 * 
        total : uint64 -> unit 
override UpdateProgress : 
        completed : uint64 * 
        total : uint64 -> unit 
```


#### Parameters
&nbsp;<dl><dt>completed</dt><dd>Type: System.UInt64<br />An application-defined value that indicates what proportion of the operation has been completed at the time the method was called. 

 If called with this value equaling the value supplied in *total*, the <a href="M_DevCase_Controls_DevProgressDialog_Stop">Stop()</a> method will be called to close the progress dialog.</dd><dt>total</dt><dd>Type: System.UInt64<br />An application-defined value that specifies what value *completed* will have when the operation is complete.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Controls_DevProgressDialog">DevProgressDialog Class</a><br /><a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />