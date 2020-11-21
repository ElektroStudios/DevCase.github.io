# NativeMethods.ReleaseMutex Method 
 

Releases ownership of the specified mutex object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ReleaseMutex(
	IntPtr hMutex
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ReleaseMutex ( 
	hMutex As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hMutex As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.ReleaseMutex(hMutex)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool ReleaseMutex(
	[InAttribute] IntPtr hMutex
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member ReleaseMutex : 
        hMutex : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hMutex</dt><dd>Type: System.IntPtr<br />A handle to the mutex object. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateMutex">CreateMutex(SecurityAttributes, Boolean, String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_OpenMutex">OpenMutex(UInt32, Boolean, String)</a> function returns this handle.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the Function fails, the Return value Is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-releasemutex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-releasemutex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />