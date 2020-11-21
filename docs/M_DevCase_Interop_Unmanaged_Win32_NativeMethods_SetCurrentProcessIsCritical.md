# NativeMethods.SetCurrentProcessIsCritical Method 
 

Establish the current process to be considered a critical process. 

 When attempting to terminate a critical process, brings down the system in a controlled manner.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("NtDll.dll", EntryPoint = "RtlSetProcessIsCritical", 
	SetLastError = true)]
public static void SetCurrentProcessIsCritical(
	bool isCritical,
	ref bool refWasCritical,
	bool needSystemCriticalBreaks
)
```

**VB**<br />
``` VB
<DllImportAttribute("NtDll.dll", EntryPoint := "RtlSetProcessIsCritical", 
	SetLastError := true>]
Public Shared Sub SetCurrentProcessIsCritical ( 
	isCritical As Boolean,
	ByRef refWasCritical As Boolean,
	needSystemCriticalBreaks As Boolean
)
```

**VB Usage**<br />
``` VB Usage
Dim isCritical As Boolean
Dim refWasCritical As Boolean
Dim needSystemCriticalBreaks As BooleanNativeMethods.SetCurrentProcessIsCritical(isCritical, 
	refWasCritical, needSystemCriticalBreaks)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"NtDll.dll", EntryPoint = L"RtlSetProcessIsCritical", 
	SetLastError = true)]
static void SetCurrentProcessIsCritical(
	bool isCritical, 
	bool% refWasCritical, 
	bool needSystemCriticalBreaks
)
```

**F#**<br />
``` F#
[<DllImportAttribute("NtDll.dll", EntryPoint = "RtlSetProcessIsCritical", 
	SetLastError = true)>]
static member SetCurrentProcessIsCritical : 
        isCritical : bool * 
        refWasCritical : bool byref * 
        needSystemCriticalBreaks : bool -> unit 

```


#### Parameters
&nbsp;<dl><dt>isCritical</dt><dd>Type: System.Boolean<br />A value that indicates whether the current process is critical.</dd><dt>refWasCritical</dt><dd>Type: System.Boolean<br />A variable passed by-reference to store a value indicating whether the current process was critical.</dd><dt>needSystemCriticalBreaks</dt><dd>Type: System.Boolean<br />**UNDOCUMENTED**</dd></dl>

## Remarks
<a href="http://www.geoffchappell.com/studies/windows/win32/ntdll/api/rtl/peb/setprocessiscritical.htm" target="_blank">http://www.geoffchappell.com/studies/windows/win32/ntdll/api/rtl/peb/setprocessiscritical.htm</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />