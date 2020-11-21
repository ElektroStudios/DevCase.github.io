# SHChangeNotifyEventID Enumeration
 

Flags for `wEventId` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHChangeNotify">SHChangeNotify(SHChangeNotifyEventID, SHChangeNotifyFlags, IntPtr, IntPtr)</a> method.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SHChangeNotifyEventID
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SHChangeNotifyEventID
```

**VB Usage**<br />
``` VB Usage
Dim instance As SHChangeNotifyEventID
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SHChangeNotifyEventID
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SHChangeNotifyEventID
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.AllEvents">**AllEvents**</td><td>2147483647</td><td>All events have occurred.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.DirectoryCreated">**DirectoryCreated**</td><td>8</td><td>A folder has been created. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the folder that was created. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.DirectoryDeleted">**DirectoryDeleted**</td><td>16</td><td>A folder has been removed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the folder that was removed. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.DirectoryRenamed">**DirectoryRenamed**</td><td>131072</td><td>The name of a folder has changed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the previous pointer to an item identifier list (PIDL) or name of the folder. `dwItem2` contains the new PIDL or name of the folder.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.ItemCreated">**ItemCreated**</td><td>2</td><td>A non-folder item has been created. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the item that was created. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.ItemDeleted">**ItemDeleted**</td><td>4</td><td>A nonfolder item has been deleted. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the item that was deleted. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.ItemRenamed">**ItemRenamed**</td><td>1</td><td>The name of a nonfolder item has changed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the previous PIDL or name of the item. `dwItem2` contains the new PIDL or name of the item.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.DriveAdded">**DriveAdded**</td><td>256</td><td>A drive has been added. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the root of the drive that was added. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.DriveAddedShell">**DriveAddedShell**</td><td>65536</td><td>A drive has been added and the Shell should create a new window for the drive. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the root of the drive that was added. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.DriveRemoved">**DriveRemoved**</td><td>128</td><td>A drive has been removed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the root of the drive that was removed. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.MediaInserted">**MediaInserted**</td><td>32</td><td>Storage media has been inserted into a drive. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the root of the drive that contains the new media. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.MediaRemoved">**MediaRemoved**</td><td>64</td><td>Storage media has been removed from a drive. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the root of the drive from which the media was removed. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.NetShared">**NetShared**</td><td>512</td><td>A folder on the local computer is being shared via the network. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the folder that is being shared. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.NetUnshared">**NetUnshared**</td><td>1024</td><td>A folder on the local computer is no longer being shared via the network. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the folder that is no longer being shared. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.ServerDisconnected">**ServerDisconnected**</td><td>16384</td><td>The computer has disconnected from a server. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the server from which the computer was disconnected. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.ItemAttributesChanged">**ItemAttributesChanged**</td><td>2048</td><td>The attributes of an item or folder have changed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the item or folder that has changed. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.FileAssocChanged">**FileAssocChanged**</td><td>134217728</td><td>A file type association has changed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> must be specified in the `uFlags` parameter. 

`dwItem1` and `dwItem2` are not used and must be set as Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.FreespaceChanged">**FreespaceChanged**</td><td>262144</td><td>The amount of free space on a drive has changed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the root of the drive on which the free space changed. `dwItem2` is not used and should be Zero.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.UpdateDirectory">**UpdateDirectory**</td><td>4096</td><td>The contents of an existing folder have changed but the folder still exists and has not been renamed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">ItemIdList</a> or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">PathA</a> must be specified in `uFlags`. 

`dwItem1` contains the folder that has changed. `dwItem2` is not used and should be Zero. 

 If a folder has been created, deleted or renamed use DirectoryCreated, or DirectoryRenamed respectively instead.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SHChangeNotifyEventID.UpdateImage">**UpdateImage**</td><td>32768</td><td>An image in the system image list has changed. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHChangeNotifyFlags">Dword</a> must be specified in `uFlags`.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762118%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762118%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />