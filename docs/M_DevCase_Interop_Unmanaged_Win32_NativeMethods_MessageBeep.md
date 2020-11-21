# NativeMethods.MessageBeep Method 
 

Plays a waveform sound. 

 The waveform sound for each sound type is identified by an entry in the registry.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool MessageBeep(
	WindowsBeepType beeptype
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function MessageBeep ( 
	beeptype As WindowsBeepType
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim beeptype As WindowsBeepType
Dim returnValue As Boolean

returnValue = NativeMethods.MessageBeep(beeptype)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool MessageBeep(
	WindowsBeepType beeptype
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member MessageBeep : 
        beeptype : WindowsBeepType -> bool 

```


#### Parameters
&nbsp;<dl><dt>beeptype</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowsBeepType">DevCase.Interop.Unmanaged.Win32.Enums.WindowsBeepType</a><br />The sound to be played.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680356%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680356%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />