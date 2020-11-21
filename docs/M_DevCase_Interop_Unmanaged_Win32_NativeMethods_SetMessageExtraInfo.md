# NativeMethods.SetMessageExtraInfo Method 
 

Sets the extra message information for the current thread. 

 Extra message information is an application- or driver-defined value associated with the current thread's message queue. 

 An application can use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMessageExtraInfo">GetMessageExtraInfo()</a> function to retrieve a thread's extra message information.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr SetMessageExtraInfo(
	IntPtr lParam
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetMessageExtraInfo ( 
	lParam As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim lParam As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SetMessageExtraInfo(lParam)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr SetMessageExtraInfo(
	IntPtr lParam
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetMessageExtraInfo : 
        lParam : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>lParam</dt><dd>Type: System.IntPtr<br />The value to be associated with the current thread.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the previous value associated with the current thread.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setmessageextrainfo" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setmessageextrainfo</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />