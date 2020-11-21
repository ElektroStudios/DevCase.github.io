# NativeMethods.GetThreadDesktop Method 
 

Retrieves a handle to the desktop assigned to the specified thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr GetThreadDesktop(
	uint threadId
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetThreadDesktop ( 
	threadId As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim threadId As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.GetThreadDesktop(threadId)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr GetThreadDesktop(
	unsigned int threadId
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetThreadDesktop : 
        threadId : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>threadId</dt><dd>Type: System.UInt32<br />The thread identifier. The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetCurrentThreadId">GetCurrentThreadId()</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateProcess">CreateProcess(String, StringBuilder, SecurityAttributes, SecurityAttributes, Boolean, CreateProcessFlags, IntPtr, String, ProcessStartupInfo, ProcessInformation)</a> functions return thread identifiers.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the desktop associated with the specified thread. You do not need to call the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CloseDesktop">CloseDesktop(IntPtr)</a> function to close the returned handle. 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getthreaddesktop" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getthreaddesktop</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />