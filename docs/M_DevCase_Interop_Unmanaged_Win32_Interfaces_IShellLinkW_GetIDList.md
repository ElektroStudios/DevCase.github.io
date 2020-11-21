# IShellLinkW.GetIDList Method 
 

Retrieves the list of item identifiers for a Shell link object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetIDList(
	ref IntPtr refPidl
)
```

**VB**<br />
``` VB
Sub GetIDList ( 
	ByRef refPidl As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkW
Dim refPidl As IntPtr

instance.GetIDList(refPidl)
```

**C++**<br />
``` C++
void GetIDList(
	IntPtr% refPidl
)
```

**F#**<br />
``` F#
abstract GetIDList : 
        refPidl : IntPtr byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refPidl</dt><dd>Type: System.IntPtr<br />When this method returns, contains the address of a PIDL.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellLinkW">IShellLinkW Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />