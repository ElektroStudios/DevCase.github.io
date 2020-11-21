# NativeMethods.WaveOutSetVolume Method 
 

Sets the volume level of the specified waveform-audio output device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("WinMM.dll", EntryPoint = "waveOutSetVolume", SetLastError = true)]
public static WinMmResult WaveOutSetVolume(
	IntPtr hwo,
	uint volume
)
```

**VB**<br />
``` VB
<DllImportAttribute("WinMM.dll", EntryPoint := "waveOutSetVolume", SetLastError := true>]
Public Shared Function WaveOutSetVolume ( 
	hwo As IntPtr,
	volume As UInteger
) As WinMmResult
```

**VB Usage**<br />
``` VB Usage
Dim hwo As IntPtr
Dim volume As UInteger
Dim returnValue As WinMmResult

returnValue = NativeMethods.WaveOutSetVolume(hwo, 
	volume)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"WinMM.dll", EntryPoint = L"waveOutSetVolume", SetLastError = true)]
static WinMmResult WaveOutSetVolume(
	IntPtr hwo, 
	unsigned int volume
)
```

**F#**<br />
``` F#
[<DllImportAttribute("WinMM.dll", EntryPoint = "waveOutSetVolume", SetLastError = true)>]
static member WaveOutSetVolume : 
        hwo : IntPtr * 
        volume : uint32 -> WinMmResult 

```


#### Parameters
&nbsp;<dl><dt>hwo</dt><dd>Type: System.IntPtr<br />A IntPtr to an open waveform-audio output device. 

 This parameter can also be a device identifier.</dd><dt>volume</dt><dd>Type: System.UInt32<br />T New volume setting. 

 The low-order word contains the left-channel volume setting, and the high-order word contains the right-channel setting. A value of `0xFFFF` represents full volume, and a value of `0x0000` is silence. 

 If a device does not support both left and right volume control, the low-order word of *volume* specifies the volume level, and the high-order word is ignored.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">WinMmResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NoError</a> if successful. 

 Possible error values include the following: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">BadDeviceId</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">InvalidHandle</a><a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NoDriver</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NoMem</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WinMmResult">NotSupported</a>.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd743874%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd743874%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />