# NativeMethods.SetThreadDesktop Method 
 

Assigns the specified desktop to the calling thread. All subsequent operations on the desktop use the access rights granted to the desktop.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetThreadDesktop(
	IntPtr hDesktop
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetThreadDesktop ( 
	hDesktop As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDesktop As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.SetThreadDesktop(hDesktop)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetThreadDesktop(
	IntPtr hDesktop
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetThreadDesktop : 
        hDesktop : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDesktop</dt><dd>Type: System.IntPtr<br />A handle to the desktop to be assigned to the calling thread. 

 This handle is returned by the CreateDesktop, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetThreadDesktop">GetThreadDesktop(UInt32)</a>, OpenDesktop, or OpenInputDesktop function. 

 This desktop must be associated with the current window station for the process.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setthreaddesktop" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setthreaddesktop</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />