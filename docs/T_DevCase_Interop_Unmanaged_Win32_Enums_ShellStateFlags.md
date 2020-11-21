# ShellStateFlags Enumeration
 

Specifies which members of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ShellState">ShellState</a> structure should be set or retrived. 

 This enumeration is used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHGetSetSettings">SHGetSetSettings(ShellState, ShellStateFlags, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ShellStateFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ShellStateFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShellStateFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ShellStateFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ShellStateFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowAllObjects">**ShowAllObjects**</td><td>1</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowAllObjects">ShowAllObjects</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowFilenameExtensions">**ShowFilenameExtensions**</td><td>2</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowFilenameExtensions">ShowFilenameExtensions</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowCompressedFilesColor">**ShowCompressedFilesColor**</td><td>8</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowCompressedFilesColor">ShowCompressedFilesColor</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.SortColumns">**SortColumns**</td><td>16</td><td>The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ParamSort">ParamSort</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_SortDirection">SortDirection</a> members are being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowSystemFiles">**ShowSystemFiles**</td><td>32</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowSystemFiles">ShowSystemFiles</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.DoubleClickInWebView">**DoubleClickInWebView**</td><td>128</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_DoubleClickInWebView">DoubleClickInWebView</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.DesktopHtml">**DesktopHtml**</td><td>512</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_DesktopHtml">DesktopHtml</a> member is being requested. 

 Set is not available. Instead, for versions of Windows prior to Windows XP, enable desktop HTML by `IActiveDesktop`.  The use of `IActiveDesktop` for this purpose, however, is not recommended for Windows XP and later versions of Windows, and is deprecated in Windows Vista.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.DontPrettyPath">**DontPrettyPath**</td><td>2048</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_DontPrettyPath">DontPrettyPath</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.MapNetDrvBtn">**MapNetDrvBtn**</td><td>4096</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_MapNetDrvBtn">MapNetDrvBtn</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowInfoTip">**ShowInfoTip**</td><td>8192</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowInfoTip">ShowInfoTip</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.HideDesktopIcons">**HideDesktopIcons**</td><td>16384</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_HideDesktopIcons">HideDesktopIcons</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.NoConfirmRecycle">**NoConfirmRecycle**</td><td>32768</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_NoConfirmRecycle">NoConfirmRecycle</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.WebView">**WebView**</td><td>131072</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_WebView">WebView</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowSuperHiddenFiles">**ShowSuperHiddenFiles**</td><td>262144</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowSuperHiddenFiles">ShowSuperHiddenFiles</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ExplorerSeparateProcess">**ExplorerSeparateProcess**</td><td>524288</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ExplorerSeparateProcess">ExplorerSeparateProcess</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.NoNetCrawling">**NoNetCrawling**</td><td>1048576</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_NoNetCrawling">NoNetCrawling</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.AutoCheckboxSelection">**AutoCheckboxSelection**</td><td>8388608</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_AutoCheckboxSelection">AutoCheckboxSelection</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowIconsOnly">**ShowIconsOnly**</td><td>16777216</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowIconsOnly">ShowIconsOnly</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowTypeOverlay">**ShowTypeOverlay**</td><td>33554432</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowTypeOverlay">ShowTypeOverlay</a> member is being requested.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ShellStateFlags.ShowStatusBar">**ShowStatusBar**</td><td>67108864</td><td>The <a href="P_DevCase_Interop_Unmanaged_Win32_Structures_ShellState_ShowStatusBar">ShowStatusBar</a> member is being requested.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/bb762591%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/bb762591%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />