# NativeMethods.CheckRemoteDebuggerPresent Method 
 

Determines whether the specified process is being debugged.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool CheckRemoteDebuggerPresent(
	IntPtr hProcess,
	out bool refIsDebuggerPresent
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function CheckRemoteDebuggerPresent ( 
	hProcess As IntPtr,
	<OutAttribute> ByRef refIsDebuggerPresent As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hProcess As IntPtr
Dim refIsDebuggerPresent As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.CheckRemoteDebuggerPresent(hProcess, 
	refIsDebuggerPresent)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool CheckRemoteDebuggerPresent(
	[InAttribute] IntPtr hProcess, 
	[OutAttribute] bool% refIsDebuggerPresent
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member CheckRemoteDebuggerPresent : 
        hProcess : IntPtr * 
        refIsDebuggerPresent : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hProcess</dt><dd>Type: System.IntPtr<br />A handle to the process.</dd><dt>refIsDebuggerPresent</dt><dd>Type: System.Boolean<br />A variable that the function sets to `true` (`True` in Visual Basic) if the specified process is being debugged, or `false` (`False` in Visual Basic) otherwise.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679280(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679280(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />