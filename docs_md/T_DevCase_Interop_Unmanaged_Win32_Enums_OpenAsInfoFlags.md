# OpenAsInfoFlags Enumeration
 

Flags for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_OpenAsInfo_Flags">Flags</a> property.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum OpenAsInfoFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration OpenAsInfoFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As OpenAsInfoFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class OpenAsInfoFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type OpenAsInfoFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.None">**None**</td><td>0</td><td /></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.AllowRegistration">**AllowRegistration**</td><td>1</td><td>Enable the "always use this program" checkbox. If not passed, it will be disabled. 

 Starting in Windows 10, the AllowRegistration flag will be ignored by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenWithDialog">SHOpenWithDialog(IntPtr, OpenAsInfo)</a>. The Open With dialog box can no longer be used to change the default program used to open a file extension. You can only use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenWithDialog">SHOpenWithDialog(IntPtr, OpenAsInfo)</a> to open a single file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.RegisterExtension">**RegisterExtension**</td><td>2</td><td>Do the registration after the user hits the `OK` button.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.Execute">**Execute**</td><td>4</td><td>Execute file after registering.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.ForceRegistration">**ForceRegistration**</td><td>8</td><td>Force the `Always use this program` checkbox to be checked. 

 Typically, you won't use the AllowRegistration flag when you pass this value. 

 Starting in Windows 10, the ForceRegistration flag will be ignored by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenWithDialog">SHOpenWithDialog(IntPtr, OpenAsInfo)</a>. The Open With dialog box can no longer be used to change the default program used to open a file extension. You can only use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenWithDialog">SHOpenWithDialog(IntPtr, OpenAsInfo)</a> to open a single file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.HideRegistration">**HideRegistration**</td><td>32</td><td>Hide the `Always use this program` checkbox. 

 If this flag is specified, the AllowRegistration and ForceRegistration flags will be ignored. 

 Starting in Windows 10, the HideRegistration flag will be ignored by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenWithDialog">SHOpenWithDialog(IntPtr, OpenAsInfo)</a>. The Open With dialog box can no longer be used to change the default program used to open a file extension. You can only use <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHOpenWithDialog">SHOpenWithDialog(IntPtr, OpenAsInfo)</a> to open a single file.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.UrlProtocol">**UrlProtocol**</td><td>64</td><td>The value for the extension that is passed is actually a protocol, so the `Open With` dialog box should show applications that are registered as capable of handling that protocol.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.OpenAsInfoFlags.FileIsUri">**FileIsUri**</td><td>128</td><td>The location pointed to by the parameter is given as a URI.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/ns-shlobj_core-_openasinfo" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/ns-shlobj_core-_openasinfo</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />