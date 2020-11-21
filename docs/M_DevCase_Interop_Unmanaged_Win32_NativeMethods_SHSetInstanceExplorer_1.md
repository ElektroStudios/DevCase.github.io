# NativeMethods.SHSetInstanceExplorer Method (Object)
 

Provides an interface that allows hosted Shell extensions and other components to prevent their host process from closing prematurely. 

 The host process is typically Windows Explorer or Windows Internet Explorer, but this function can also be used by other applications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", SetLastError = true)]
public static void SHSetInstanceExplorer(
	ref Object refPunk
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", SetLastError := true>]
Public Shared Sub SHSetInstanceExplorer ( 
	ByRef refPunk As Object
)
```

**VB Usage**<br />
``` VB Usage
Dim refPunk As ObjectNativeMethods.SHSetInstanceExplorer(refPunk)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", SetLastError = true)]
static void SHSetInstanceExplorer(
	Object^% refPunk
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", SetLastError = true)>]
static member SHSetInstanceExplorer : 
        refPunk : Object byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refPunk</dt><dd>Type: System.Object<br />A pointer to a free-threaded IUnknown. 

 Components can use this interface (through <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetInstanceExplorer_1">SHGetInstanceExplorer(Object)</a>) to prevent the host process from terminating. 

 This value can be a null reference (`Nothing` in Visual Basic), in which case the process reference is no longer made available to components.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shsetinstanceexplorer" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shsetinstanceexplorer</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHSetInstanceExplorer">SHSetInstanceExplorer Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />