# NativeMethods.WaveOutGetVolume Method 
 

Gets the volume level of the specified waveform-audio output device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinMM.dll", EntryPoint = "waveOutGetVolume", SetLastError = true)]
public static WinMmResult WaveOutGetVolume(
	IntPtr hwo,
	ref uint refVolume
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinMM.dll", EntryPoint := "waveOutGetVolume", SetLastError := true>]
Public Shared Function WaveOutGetVolume ( 
	hwo As IntPtr,
	ByRef refVolume As UInteger
) As WinMmResult
```

**VB Usage**<br />
``` VB Usage
Dim hwo As IntPtr
Dim refVolume As UInteger
Dim returnValue As WinMmResult

returnValue = NativeMethods.WaveOutGetVolume(hwo, 
	refVolume)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinMM.dll", EntryPoint = L"waveOutGetVolume", SetLastError = true)]
static WinMmResult WaveOutGetVolume(
	IntPtr hwo, 
	unsigned int% refVolume
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinMM.dll", EntryPoint = "waveOutGetVolume", SetLastError = true)>]
static member WaveOutGetVolume : 
        hwo : IntPtr * 
        refVolume : uint32 byref -> WinMmResult 

```


#### Parameters
&nbsp;<dl><dt>hwo</dt><dd>Type: System.IntPtr<br />A IntPtr to an open waveform-audio output device. This parameter can also be a device identifier.</dd><dt>refVolume</dt><dd>Type: System.UInt32<br />T Pointer to a variable to be filled with the current volume setting. 

 The low-order word of this location contains the left-channel volume setting, and the high-order word contains the right-channel setting. 

 A value of `0xFFFF` represents full volume, and a value of `0x0000` is silence. 

 If a device does not support both left and right volume control, the low-order word of the specified location contains the mono volume level. 

 The full 16-bit setting(s) set with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WaveOutSetVolume">WaveOutSetVolume(IntPtr, UInt32)</a> function is returned, regardless of whether the device supports the full 16 bits of volume-level control.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">WinMmResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NoError</a> if successful. 

 Possible error values include the following: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">BadDeviceId</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">InvalidHandle</a><a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NoDriver</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NoMem</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NotSupported</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/aa909806.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/aa909806.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />