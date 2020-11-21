# HardDriveInfo Properties
 

The <a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo</a> type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_AvailableFreeSpace">AvailableFreeSpace</a></td><td>
Gets the amount of available free space on a drive, in bytes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_BytesPerSector">BytesPerSector</a></td><td>
Gets the mumber of bytes in each sector for the physical disk drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_CapabilitiesNames">CapabilitiesNames</a></td><td>
Gets the names of the capabilities (such as S.M.A.R.T. notification) of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_DeviceId">DeviceId</a></td><td>
Gets the unique identifier of the disk drive on the system.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_DriveFormat">DriveFormat</a></td><td>
Gets the name of the file system, such as NTFS or FAT32.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_FirmwareRevision">FirmwareRevision</a></td><td>
Gets the revision for the hard drive firmware that is assigned by the manufacturer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_Index">Index</a></td><td>
Gets the physical drive index of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_InterfaceType">InterfaceType</a></td><td>
Gets the interface type of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_IsReady">IsReady</a></td><td>
Gets a value that indicates whether a drive is ready.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_MediaType">MediaType</a></td><td>
Gets the type of hard drive media.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_Model">Model</a></td><td>
Gets the manufacturer's model number of the disk drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_Name">Name</a></td><td>
Gets the name of the hard drive, such as C:\.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_Partitions">Partitions</a></td><td>
Gets the number of partitions on this hard drive that are recognized by the operating system.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_PnpDeviceId">PnpDeviceId</a></td><td>
Gets the Windows Plug and Play (PNP) device identifier of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_RootDirectory">RootDirectory</a></td><td>
Gets the root directory of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_SectorsPerTrack">SectorsPerTrack</a></td><td>
Gets the number of sectors in each track for this hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_SerialNumber">SerialNumber</a></td><td>
Gets the number allocated by the manufacturer to identify the physical media.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_SMART">SMART</a></td><td>
Gets the S.M.A.R.T. information of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TotalCylinders">TotalCylinders</a></td><td>
Gets the total number of cylinders on the hard drive. 

 Note: the value for this property is obtained through extended functions of BIOS interrupt 13h. 

 The value may be inaccurate if the drive uses a translation scheme to support high-capacity disk sizes. 

 Consult the manufacturer for accurate drive specifications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TotalFreeSpace">TotalFreeSpace</a></td><td>
Gets the total amount of free space available on a drive, in bytes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TotalHeads">TotalHeads</a></td><td>
Gets the total number of heads on the hard drive. 

 Note: the value for this property is obtained through extended functions of BIOS interrupt 13h. 

 The value may be inaccurate if the drive uses a translation scheme to support high-capacity disk sizes. 

 Consult the manufacturer for accurate drive specifications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TotalSectors">TotalSectors</a></td><td>
Gets the total number of sectors on the physical disk drive. 

 Note: the value for this property is obtained through extended functions of BIOS interrupt 13h. 

 The value may be inaccurate if the drive uses a translation scheme to support high-capacity disk sizes. 

 Consult the manufacturer for accurate drive specifications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TotalSize">TotalSize</a></td><td>
Gets the total size of storage space on a drive, in bytes.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TotalTracks">TotalTracks</a></td><td>
Gets the total number of tracks on the physical disk drive. 

 Note: the value for this property is obtained through extended functions of BIOS interrupt 13h. 

 The value may be inaccurate if the drive uses a translation scheme to support high-capacity disk sizes. 

 Consult the manufacturer for accurate drive specifications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_TracksPerCylinder">TracksPerCylinder</a></td><td>
Gets the number of tracks in each cylinder on the physical disk drive. 

 Note: the value for this property is obtained through extended functions of BIOS interrupt 13h. 

 The value may be inaccurate if the drive uses a translation scheme to support high-capacity disk sizes. 

 Consult the manufacturer for accurate drive specifications.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_HardDriveInfo_VolumeLabel">VolumeLabel</a></td><td>
Gets or sets the volume label of the hard drive.</td></tr></table>&nbsp;
<a href="#harddriveinfo-properties">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_HardDriveInfo">HardDriveInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />