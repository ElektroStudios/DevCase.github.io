# DevBroadcastVolume Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume">DevBroadcastVolume</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume_Flags">Flags</a></td><td>
This parameter can be one of the following values: '0x0001': Change affects media in drive. If not set, change affects physical device or drive. '0x0002': Indicated logical volume is a network volume.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume_Mask">Mask</a></td><td>
The logical unit mask identifying one or more logical units. Each bit in the mask corresponds to one logical drive. Bit 0 represents drive A, bit 1 represents drive B, and so on.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume_Reserved">Reserved</a></td><td>
Reserved parameter; do not use this.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of DevBroadcastVolume)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume_Type">Type</a></td><td>
Set to DBT_DEVTYP_VOLUME (2).</td></tr></table>&nbsp;
<a href="#devbroadcastvolume-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevBroadcastVolume">DevBroadcastVolume Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />