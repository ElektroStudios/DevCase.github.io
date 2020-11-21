# NativeMethods.SoundSentry Method 
 

Triggers a visual signal to indicate that a sound is playing.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static bool SoundSentry()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function SoundSentry As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = NativeMethods.SoundSentry()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static bool SoundSentry()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member SoundSentry : unit -> bool 

```


#### Return Value
Type: Boolean<br />Return `true` (`True` in Visual Basic) if the visual signal was or will be displayed correctly. 

 Returns `false` (`False` in Visual Basic) if an error prevented the signal from being displayed.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-soundsentry" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-soundsentry</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />