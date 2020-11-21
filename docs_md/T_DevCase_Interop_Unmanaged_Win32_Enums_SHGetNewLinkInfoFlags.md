# SHGetNewLinkInfoFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetNewLinkInfo">SHGetNewLinkInfo(String, String, StringBuilder, Boolean, SHGetNewLinkInfoFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SHGetNewLinkInfoFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SHGetNewLinkInfoFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SHGetNewLinkInfoFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SHGetNewLinkInfoFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SHGetNewLinkInfoFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags.Pidl">**Pidl**</td><td>1</td><td>The target pointed to by `linkTo` parameter is a PIDL that represents the target. 

 If this flag is not included, `linkTo` parameter is regarded as the address of a string that contains the path and file name of the target.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags.NoUnique">**NoUnique**</td><td>2</td><td>Skip the normal checks that ensure that the shortcut name is unique within the destination folder. 

 If this flag is not included, the function creates the shortcut name and then determines whether the name is unique in the destination folder. 

 If a file with the same name already exists in the destination folder, the shortcut name will be modified. This process is repeated until a unique name is found.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags.PrefixName">**PrefixName**</td><td>4</td><td>The created name will be preceded by the string "Shortcut to ".</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags.NoLink">**NoLink**</td><td>8</td><td>Do not add the .lnk file name extension.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags.NoLocalName">**NoLocalName**</td><td>16</td><td>Use the non-localized parsing name of the target pointed to by `linkTo` parameter as the name of the shortcut file. 

 If this flag is not set, the localized name is used.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags.UseUrlText">**UseUrlText**</td><td>32</td><td>Append a .url file name extension (rather than .lnk) to the name pointed to by `name` parameter. 

 If this flag is not set, the shortcut name uses a .lnk extension unless NoLink is set.</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shgetnewlinkinfoa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shgetnewlinkinfoa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />