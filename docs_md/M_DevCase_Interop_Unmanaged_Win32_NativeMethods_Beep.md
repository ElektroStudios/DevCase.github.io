# NativeMethods.Beep Method 
 

Generates simple tones on the speaker. 

 The function is synchronous; it performs an alertable wait and does not return control to its caller until the sound finishes.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static bool Beep(
	int frequency,
	uint duration
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function Beep ( 
	frequency As Integer,
	duration As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim frequency As Integer
Dim duration As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.Beep(frequency, 
	duration)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static bool Beep(
	int frequency, 
	unsigned int duration
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member Beep : 
        frequency : int * 
        duration : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>frequency</dt><dd>Type: System.Int32<br />The frequency of the sound, in hertz. 

 This parameter must be in the range `37` through `32,767` (`0x25` through `0x7FFF`).</dd><dt>duration</dt><dd>Type: System.UInt32<br />The duration of the sound, in milliseconds.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms679277%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms679277%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />