# NativeMethods.SetCaretBlinkTime Method 
 

Sets the caret blink time to the specified number of milliseconds. 

 The blink time is the elapsed time, in milliseconds, required to invert the caret's pixels.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SetCaretBlinkTime(
	uint seconds
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SetCaretBlinkTime ( 
	seconds As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim seconds As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.SetCaretBlinkTime(seconds)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SetCaretBlinkTime(
	unsigned int seconds
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SetCaretBlinkTime : 
        seconds : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>seconds</dt><dd>Type: System.UInt32<br />The new blink time, in milliseconds.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648404%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648404%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />