# DefineDosDeviceFlags Enumeration
 

Specifies the controllable aspects of the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DefineDosDevice">DefineDosDevice(DefineDosDeviceFlags, String, String)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum DefineDosDeviceFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration DefineDosDeviceFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As DefineDosDeviceFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class DefineDosDeviceFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type DefineDosDeviceFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DefineDosDeviceFlags.ExactMatchOnRemove">**ExactMatchOnRemove**</td><td>4</td><td>If this value is specified along with RemoveDefinition, the function will use an exact match to determine which mapping to remove. 

 Use this value to ensure that you do not delete something that you did not define.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DefineDosDeviceFlags.NoBroadcastSystem">**NoBroadcastSystem**</td><td>8</td><td>Do not broadcast the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SettingChange</a> message. 

 By default, this message is broadcast to notify the shell and applications of the change.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DefineDosDeviceFlags.RawTargetPath">**RawTargetPath**</td><td>1</td><td>Uses the `targetPath` parameter string as is. Otherwise, it is converted from an MS-DOS path to a path.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.DefineDosDeviceFlags.RemoveDefinition">**RemoveDefinition**</td><td>2</td><td>Removes the specified definition for the specified device. 

 To determine which definition to remove, the function walks the list of mappings for the device, looking for a match of `targetPath` parameter against a prefix of each mapping associated with this device. The first mapping that matches is the one removed, and then the function returns. 

 If `targetPath` parameter is NULL or a pointer to a NULL string, the function will remove the first mapping associated with the device and pop the most recent one pushed. If there is nothing left to pop, the device name will be removed. 

 If RemoveDefinition value is not specified, the string pointed to by the `targetPath` parameter will become the new mapping for this device.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-definedosdevicew" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/fileapi/nf-fileapi-definedosdevicew</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />