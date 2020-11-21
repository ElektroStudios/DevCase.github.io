# SHUpdateImageFlags Enumeration
 

Specifies the icon attributes when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHUpdateImage">SHUpdateImage(String, Int32, SHUpdateImageFlags, Int32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SHUpdateImageFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SHUpdateImageFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SHUpdateImageFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SHUpdateImageFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SHUpdateImageFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags.Async">**Async**</td><td>32</td><td>Set this flag to determine whether the icon should be extracted asynchronously. 

 If the icon can be extracted rapidly, this flag is usually ignored.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags.DefaultIcon">**DefaultIcon**</td><td>64</td><td>Retrieve information about the fallback icon. 

 Fallback icons are usually used while the desired icon is extracted and added to the cache.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags.ForShell">**ForShell**</td><td>2</td><td>The icon is displayed in a Shell folder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags.ForShortcut">**ForShortcut**</td><td>128</td><td>The icon indicates a shortcut. However, the icon extractor should not apply the shortcut overlay; that will be done later. 

 Shortcut icons are state-independent.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags.OpenIcon">**OpenIcon**</td><td>1</td><td>The icon is in the open state if both open-state and closed-state images are available. 

 If this flag is not specified, the icon is in the normal or closed state. 

 This flag is typically used for folder objects.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHUpdateImageFlags.CheckShield">**CheckShield**</td><td>512</td><td>Explicitly return whether or not the calling application must stamp the icon with the User Account Control (UAC) shield. 

 Do not block if Async is set.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shupdateimagea" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shupdateimagea</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />