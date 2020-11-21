# WinMmResult Enumeration
 

Defines an error value for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WaveOutGetVolume">WaveOutGetVolume(IntPtr, UInt32)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_WaveOutSetVolume">WaveOutSetVolume(IntPtr, UInt32)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum WinMmResult
```

**VB**<br />
``` VB
Public Enumeration WinMmResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As WinMmResult
```

**C++**<br />
``` C++
public enum class WinMmResult
```

**F#**<br />
``` F#
type WinMmResult
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WinMmResult.NoError">**NoError**</td><td>0</td><td>Successful, no error.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WinMmResult.BadDeviceId">**BadDeviceId**</td><td>2</td><td>Specified device identification number is out of range.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WinMmResult.InvalidHandle">**InvalidHandle**</td><td>5</td><td>Specified device handle is invalid.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WinMmResult.NoDriver">**NoDriver**</td><td>6</td><td>No device driver is present.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WinMmResult.NoMem">**NoMem**</td><td>7</td><td>Unable to allocate or lock memory.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WinMmResult.NotSupported">**NotSupported**</td><td>8</td><td>Function is not supported.</td></tr></table>

## Remarks
<a href="http://www.pinvoke.net/default.aspx/winmm/MMRESULT.html" target="_blank">http://www.pinvoke.net/default.aspx/winmm/MMRESULT.html</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />