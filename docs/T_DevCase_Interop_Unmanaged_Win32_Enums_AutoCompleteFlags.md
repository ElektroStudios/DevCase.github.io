# AutoCompleteFlags Enumeration
 

Flags for <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHAutoComplete">SHAutoComplete(IntPtr, AutoCompleteFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum AutoCompleteFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration AutoCompleteFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As AutoCompleteFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class AutoCompleteFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type AutoCompleteFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.AutoAppendForceOff">**AutoAppendForceOff**</td><td>2147483648</td><td>Ignore the registry default and force the AutoAppend feature off. 

 This flag must be used in combination with one or more of the following flags: 

FileSystem, FileSystemDirs, FileSystemOnly, UrlHistory or UrlMRU.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.AutoAppendForceOn">**AutoAppendForceOn**</td><td>1073741824</td><td>Ignore the registry value and force the AutoAppend feature on. 

 The completed string will be displayed in the edit box with the added characters highlighted. 

 This flag must be used in combination with one or more of the following flags: 

FileSystem, FileSystemDirs, FileSystemOnly, UrlHistory or UrlMRU.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.AutoSuggestForceOff">**AutoSuggestForceOff**</td><td>536870912</td><td>Ignore the registry default and force the AutoSuggest feature off. 

 This flag must be used in combination with one or more of the following flags: 

FileSystem, FileSystemDirs, FileSystemOnly, UrlHistory or UrlMRU.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.AutoSuggestForceOn">**AutoSuggestForceOn**</td><td>268435456</td><td>Ignore the registry value and force the AutoSuggest feature on. 

 A selection of possible completed strings will be displayed as a drop-down list, below the edit box. 

 This flag must be used in combination with one or more of the following flags: 

FileSystem, FileSystemDirs, FileSystemOnly, UrlHistory or UrlMRU.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.Default">**Default**</td><td>0</td><td>The default setting, equivalent to `AutoCompleteFlags.FileSystem Or AutoCompleteFlags.UrlAll`. 

Default cannot be combined with any other flags.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.FileSystemOnly">**FileSystemOnly**</td><td>16</td><td>Include the file system only.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.FileSystemDirs">**FileSystemDirs**</td><td>32</td><td>Include the file system and directories, UNC servers, and UNC server shares.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.FileSystem">**FileSystem**</td><td>1</td><td>Include the file system and the rest of the Shell (Desktop, Computer, and Control Panel, for example).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.UrlAll">**UrlAll**</td><td>6</td><td>Include the URLs in the users History and Recently Used lists. 

 Equivalent to `AutoCompleteFlags.UrlHistory Or AutoCompleteFlags.UrlMRU`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.UrlHistory">**UrlHistory**</td><td>2</td><td>Include the URLs in the user's History list.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.UrlMRU">**UrlMRU**</td><td>4</td><td>Include the URLs in the user's Most Recently Used (MRU) list.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.UseTab">**UseTab**</td><td>8</td><td>Allow the user to select from the autosuggest list by pressing the TAB key. 

 If this flag is not set, pressing the TAB key will shift focus to the next control and close the autosuggest list. 

 If UseTab is set, pressing the TAB key will select the first item in the list. Pressing TAB again will select the next item in the list, and so on. When the user reaches the end of the list, the next TAB key press will cycle the focus back to the edit control. 

 This flag must be used in combination with one or more of the following flags: 

FileSystem, FileSystemDirs, FileSystemOnly, UrlHistory or UrlMRU.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.AutoCompleteFlags.VirtualNamespace">**VirtualNamespace**</td><td>64</td><td>Also include the virtual namespace</td></tr></table>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shautocomplete" target="_blank">https://docs.microsoft.com/en-us/windows/win32/api/shlwapi/nf-shlwapi-shautocomplete</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />