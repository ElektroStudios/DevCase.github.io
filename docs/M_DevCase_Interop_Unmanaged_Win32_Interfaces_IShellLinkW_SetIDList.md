# IShellLinkW.SetIDList Method 
 

Sets the pointer to an item identifier list (PIDL) for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void SetIDList(
	IntPtr pidl
)
```

**VB**<br />
``` VB
Sub SetIDList ( 
	pidl As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim pidl As IntPtr

instance.SetIDList(pidl)
```

**C++**<br />
``` C++
void SetIDList(
	IntPtr pidl
)
```

**F#**<br />
``` F#
abstract SetIDList : 
        pidl : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: System.IntPtr<br />The object's fully qualified PIDL.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />