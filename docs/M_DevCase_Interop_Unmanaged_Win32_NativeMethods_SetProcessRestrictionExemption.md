# NativeMethods.SetProcessRestrictionExemption Method 
 

Exempts the calling process from restrictions preventing desktop processes from interacting with the Windows Store app environment. This function is used by development and debugging tools. 

 This function only succeeds if a developer license is present on the system. Once successful the calling process will be able to perform the following actions, subject to User Interface Privilege Isolation (UIPI) restrictions: 

 - Attach global hooks (and event hooks) to Windows Store app processes. 

 - Attach input queues between Windows Store app processes, Windows Store app browsers, system processes, and desktop application processes. 

 - Change foreground arbitrarily between the Windows Store app and desktop environments.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetProcessRestrictionExemption(
	bool enableExemption
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetProcessRestrictionExemption ( 
	enableExemption As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim enableExemption As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SetProcessRestrictionExemption(enableExemption)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetProcessRestrictionExemption(
	bool enableExemption
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetProcessRestrictionExemption : 
        enableExemption : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>enableExemption</dt><dd>Type: System.Boolean<br />When set to TRUE, indicates a request to disable exemption for the calling process.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setprocessrestrictionexemption" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setprocessrestrictionexemption</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />