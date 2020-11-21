# ReparsePointTags Enumeration
 

Specifies a predefined Microsoft reparse point tag, for the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ReparseDataBuffer_ReparseTag">ReparseTag</a> member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ReparsePointTags
```

**VB**<br />
``` VB
Public Enumeration ReparsePointTags
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReparsePointTags
```

**C++**<br />
``` C++
public enum class ReparsePointTags
```

**F#**<br />
``` F#
type ReparsePointTags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Reserved0">**Reserved0**</td><td>0</td><td>Reserved reparse tag value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Reserved1">**Reserved1**</td><td>1</td><td>Reserved reparse tag value.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.MountPoint">**MountPoint**</td><td>2684354563</td><td>Tag used for a mount point. 

 For a symbolic link, see: SymbolicLink</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.HSM">**HSM**</td><td>3221225476</td><td>Obsolete. Tag used by legacy Hierarchical Storage Manager Product.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.HSM2">**HSM2**</td><td>2147483654</td><td>Obsolete. Tag used by legacy Hierarchical Storage Manager Product.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.SIS">**SIS**</td><td>2147483655</td><td>Tag used by single-instance storage (SIS) filter driver.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.WIM">**WIM**</td><td>2147483656</td><td>Tag used for by WIM.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CSV">**CSV**</td><td>2147483657</td><td>CSV reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.DFS">**DFS**</td><td>2147483658</td><td>Tag used by the DFS (Distributed File System) filter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.SymbolicLink">**SymbolicLink**</td><td>2684354572</td><td>Tag used for for a symbolic link. 

 For a mount point, see: MountPoint</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.DFSR">**DFSR**</td><td>2147483666</td><td>Tag used by the DFS (Distributed File System) filter.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.DEDUP">**DEDUP**</td><td>2147483667</td><td>DEDUP reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.NFS">**NFS**</td><td>2147483668</td><td>Tag used by the Network File System (NFS) component.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.FilePlaceholder">**FilePlaceholder**</td><td>2147483669</td><td>FilePlaceholder reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.WOF">**WOF**</td><td>2147483671</td><td>WOF reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.WCI">**WCI**</td><td>2147483672</td><td>WCI reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.WCI1">**WCI1**</td><td>2415923224</td><td>WCI1 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.GlobalReparse">**GlobalReparse**</td><td>2684354585</td><td>GlobalReparse reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud">**Cloud**</td><td>2415919130</td><td>Cloud reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud1">**Cloud1**</td><td>2415923226</td><td>Cloud1 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud2">**Cloud2**</td><td>2415927322</td><td>Cloud2 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud3">**Cloud3**</td><td>2415931418</td><td>Cloud3 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud4">**Cloud4**</td><td>2415935514</td><td>Cloud4 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud5">**Cloud5**</td><td>2415939610</td><td>Cloud5 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud6">**Cloud6**</td><td>2415943706</td><td>Cloud6 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud7">**Cloud7**</td><td>2415947802</td><td>Cloud7 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud8">**Cloud8**</td><td>2415951898</td><td>Cloud8 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Cloud9">**Cloud9**</td><td>2415955994</td><td>Cloud9 reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudA">**CloudA**</td><td>2415960090</td><td>CloudA reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudB">**CloudB**</td><td>2415964186</td><td>CloudB reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudC">**CloudC**</td><td>2415968282</td><td>CloudC reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudD">**CloudD**</td><td>2415972378</td><td>CloudD reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudE">**CloudE**</td><td>2415976474</td><td>CloudE reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudF">**CloudF**</td><td>2415980570</td><td>CloudF reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.CloudMask">**CloudMask**</td><td>61440</td><td>CloudMask reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.AppExecLink">**AppExecLink**</td><td>2147483675</td><td>AppExecLink reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.GVFS">**GVFS**</td><td>2415919132</td><td>GVFS reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.StorageSync">**StorageSync**</td><td>2147483678</td><td>StorageSync reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.WCI_Tombstone">**WCI_Tombstone**</td><td>2684354591</td><td>WCI_Tombstone reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.Unhandled">**Unhandled**</td><td>2147483680</td><td>Unhandled reparse point tag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.OneDrive">**OneDrive**</td><td>2147483681</td><td>Tag used by OneDrive.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.ReparsePointTags.GVFS_Tombstone">**GVFS_Tombstone**</td><td>2684354594</td><td>GVFS_Tombstone reparse point tag.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa365511(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa365511(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />