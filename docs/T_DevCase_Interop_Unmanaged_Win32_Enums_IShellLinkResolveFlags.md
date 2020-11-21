# IShellLinkResolveFlags Enumeration
 

IShellLink.Resolve method action flags.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum IShellLinkResolveFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration IShellLinkResolveFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellLinkResolveFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class IShellLinkResolveFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type IShellLinkResolveFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.NoUI">**NoUI**</td><td>1</td><td>Do not display a dialog box if the link cannot be resolved. When SLR_NO_UI is set, the high-order word of fFlags can be set to a time-out value that specifies the maximum amount of time to be spent resolving the link. The function returns if the link cannot be resolved within the time-out duration. If the high-order word is set to zero, the time-out duration will be set to the default value of 3,000 milliseconds (3 seconds). To specify a value, set the high word of fFlags to the desired time-out duration, in milliseconds.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.Update">**Update**</td><td>4</td><td>If the link object has changed, update its path and list of identifiers. If SLR_UPDATE is set, you do not need to call IPersistFile::IsDirty to determine, whether or not the link object has changed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.NoUpdate">**NoUpdate**</td><td>8</td><td>Do not update the link information</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.NoSearch">**NoSearch**</td><td>16</td><td>Do not execute the search heuristics</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.Notrack">**Notrack**</td><td>32</td><td>Do not use distributed link tracking</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.NoLinkInfo">**NoLinkInfo**</td><td>64</td><td>Disable distributed link tracking. By default, distributed link tracking tracks removable media, across multiple devices based on the volume name. It also uses the Universal Naming Convention (UNC) path to track remote file systems, whose drive letter has changed. Setting SLR_NOLINKINFO disables both types of tracking.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.IShellLinkResolveFlags.InvokeMsi">**InvokeMsi**</td><td>128</td><td>Call the Microsoft Windows Installer</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb774952%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb774952%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />