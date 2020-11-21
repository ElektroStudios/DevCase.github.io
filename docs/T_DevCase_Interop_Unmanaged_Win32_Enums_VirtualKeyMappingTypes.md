# VirtualKeyMappingTypes Enumeration
 

Specifies a virtual key mapping type. 

 For <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MapVirtualKey">MapVirtualKey(UInt32, VirtualKeyMappingTypes)</a> and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MapVirtualKeyEx">MapVirtualKeyEx(UInt32, VirtualKeyMappingTypes, IntPtr)</a> functions.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum VirtualKeyMappingTypes
```

**VB**<br />
``` VB
Public Enumeration VirtualKeyMappingTypes
```

**VB Usage**<br />
``` VB Usage
Dim instance As VirtualKeyMappingTypes
```

**C++**<br />
``` C++
public enum class VirtualKeyMappingTypes
```

**F#**<br />
``` F#
type VirtualKeyMappingTypes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes.VKeyToScanCode">**VKeyToScanCode**</td><td>0</td><td>`code` parameter is a virtual-key code and is translated into a scan code. 

 If it is a virtual-key code that does not distinguish between left and right hand keys, the left-hand scan code is returned. 

 If there is no translation, the function returns `0`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes.ScanCodeToVKey">**ScanCodeToVKey**</td><td>1</td><td>`code` parameter is a scan code and is translated into a virtual-key code that does not distinguish between left and right hand keys. 

 If there is no translation, the function returns `0`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes.VKeyToChar">**VKeyToChar**</td><td>2</td><td>`code` parameter is a virtual-key code and is translated into an unshifted character value in the low-order word of the return value. 

 Dead keys (diacritics) are indicated by setting the top bit of the return value. 

 If there is no translation, the function returns `0`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes.ScanCodeToVKeyEx">**ScanCodeToVKeyEx**</td><td>3</td><td>`code` parameter is a scan code and is translated into a virtual-key code that distinguishes between left and right hand keys. 

 If there is no translation, the function returns `0`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.VirtualKeyMappingTypes.VKeyToScanCodeEx">**VKeyToScanCodeEx**</td><td>4</td><td>`code` parameter is a virtual-key code and is translated into a scan code. 

 If it is a virtual-key code that does not distinguish between left- and right-hand keys, the left-hand scan code is returned. 

 If the scan code is an extended scan code, the high byte of the `code` value can contain either `0xe0` or `0xe1` to specify the extended scan code. 

 If there is no translation, the function returns `0`.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776346(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776346(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />