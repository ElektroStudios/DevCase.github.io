# NativeMethods.SetThreadErrorMode Method 
 

Controls whether the system will handle the specified types of serious errors or whether the current thread will handle them.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool SetThreadErrorMode(
	ThreadErrorMode newMode,
	out ThreadErrorMode refOldMode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SetThreadErrorMode ( 
	newMode As ThreadErrorMode,
	<OutAttribute> ByRef refOldMode As ThreadErrorMode
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim newMode As ThreadErrorMode
Dim refOldMode As ThreadErrorMode
Dim returnValue As Boolean

returnValue = NativeMethods.SetThreadErrorMode(newMode, 
	refOldMode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool SetThreadErrorMode(
	ThreadErrorMode newMode, 
	[OutAttribute] ThreadErrorMode% refOldMode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetThreadErrorMode : 
        newMode : ThreadErrorMode * 
        refOldMode : ThreadErrorMode byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>newMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadErrorMode">DevCase.Interop.Unmanaged.Win32.Enums.ThreadErrorMode</a><br />The new error mode for the current thread.</dd><dt>refOldMode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ThreadErrorMode">DevCase.Interop.Unmanaged.Win32.Enums.ThreadErrorMode</a><br />If the function succeeds, this parameter is set to the thread's previous error mode. 

 This parameter can be a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd553630%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd553630%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />