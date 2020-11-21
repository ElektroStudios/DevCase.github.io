# NativeMethods.SHGetInstanceExplorer Method (Object)
 

Retrieves an interface that allows hosted Shell extensions and other components to prevent their host process from closing prematurely. 

 The host process is typically `Windows Explorer` or `Windows Internet Explorer`, but this function can also be used by other applications.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll")]
public static int SHGetInstanceExplorer(
	out Object refPunk
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll">]
Public Shared Function SHGetInstanceExplorer ( 
	<OutAttribute> ByRef refPunk As Object
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim refPunk As Object
Dim returnValue As Integer

returnValue = NativeMethods.SHGetInstanceExplorer(refPunk)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll")]
static int SHGetInstanceExplorer(
	[OutAttribute] Object^% refPunk
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll")>]
static member SHGetInstanceExplorer : 
        refPunk : Object byref -> int 

```


#### Parameters
&nbsp;<dl><dt>refPunk</dt><dd>Type: System.Object<br />When this function returns successfully, contains the address of the host process' IUnknown interface pointer. 

 This is a free-threaded interface used to prevent the host process from terminating. 

 If the function call fails, this value is set to a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762186%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762186%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetInstanceExplorer">SHGetInstanceExplorer Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />