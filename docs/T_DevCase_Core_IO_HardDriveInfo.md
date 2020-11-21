# HardDriveInfo Class
 

Provides access to information on a hard drive.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.HardDriveInfo<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[TypeConverterAttribute(typeof(ExpandableObjectConverter))]
public class HardDriveInfo : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<TypeConverterAttribute(GetType(ExpandableObjectConverter))>
Public Class HardDriveInfo
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As HardDriveInfo
```

**C++**<br />
``` C++
[SerializableAttribute]
[TypeConverterAttribute(typeof(ExpandableObjectConverter))]
public ref class HardDriveInfo : public AestheticObject
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<TypeConverterAttribute(typeof(ExpandableObjectConverter))>]
type HardDriveInfo =  
    class
        inherit AestheticObject
    end
```

The HardDriveInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_HardDriveInfo__ctor">HardDriveInfo(Char)</a></td><td>
Initializes a new instance of the HardDriveInfo class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_HardDriveInfo__ctor_1">HardDriveInfo(DriveInfo)</a></td><td>
Initializes a new instance of the HardDriveInfo class.</td></tr></table>&nbsp;
<a href="#harddriveinfo-class">Back to Top</a>

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
<a href="#harddriveinfo-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_HardDriveInfo_GetDrives">GetDrives</a></td><td>
Gets all the hard drives of the current machine.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_HardDriveInfo_Refresh">Refresh</a></td><td>
Refreshes the hard drive properties of this instance.</td></tr></table>&nbsp;
<a href="#harddriveinfo-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#harddriveinfo-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hdds As IEnumerable(Of HardDriveInfo) = HardDriveInfo.GetDrives()

For Each hdd As HardDriveInfo In hdds

    ' System.IO.DriveInfo properties
    Console.WriteLine("{0}: {1}", NameOf(hdd.Name), hdd.Name)
    Console.WriteLine("{0}: {1}", NameOf(hdd.RootDirectory), hdd.RootDirectory.FullName)
    Console.WriteLine("{0}: {1}", NameOf(hdd.VolumeLabel), hdd.VolumeLabel)
    Console.WriteLine("{0}: {1}", NameOf(hdd.DriveFormat), hdd.DriveFormat)
    Console.WriteLine("{0}: {1}", NameOf(hdd.IsReady), hdd.IsReady)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TotalSize), hdd.TotalSize)
    Console.WriteLine("{0}: {1}", NameOf(hdd.AvailableFreeSpace), hdd.AvailableFreeSpace)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TotalFreeSpace), hdd.TotalFreeSpace)

    ' Win32_DiskDrive properties
    Console.WriteLine("{0}: {1}", NameOf(hdd.BytesPerSector), hdd.BytesPerSector)
    Console.WriteLine("{0}: {1}", NameOf(hdd.Capabilities), String.Join(", ", hdd.Capabilities))
    Console.WriteLine("{0}: {1}", NameOf(hdd.DeviceId), hdd.DeviceId)
    Console.WriteLine("{0}: {1}", NameOf(hdd.FirmwareRevision), hdd.FirmwareRevision)
    Console.WriteLine("{0}: {1}", NameOf(hdd.Index), hdd.PhysicalIndex)
    Console.WriteLine("{0}: {1}", NameOf(hdd.InterfaceType), hdd.InterfaceType)
    Console.WriteLine("{0}: {1}", NameOf(hdd.MediaType), hdd.MediaType.ToString())
    Console.WriteLine("{0}: {1}", NameOf(hdd.Model), hdd.Model)
    Console.WriteLine("{0}: {1}", NameOf(hdd.Partitions), hdd.Partitions)
    Console.WriteLine("{0}: {1}", NameOf(hdd.PnpDeviceId), hdd.PnpDeviceId)
    Console.WriteLine("{0}: {1}", NameOf(hdd.SectorsPerTrack), hdd.SectorsPerTrack)
    Console.WriteLine("{0}: {1}", NameOf(hdd.SerialNumber), hdd.SerialNumber)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TotalCylinders), hdd.TotalCylinders)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TotalHeads), hdd.TotalHeads)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TotalSectors), hdd.TotalSectors)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TotalTracks), hdd.TotalTracks)
    Console.WriteLine("{0}: {1}", NameOf(hdd.TracksPerCylinder), hdd.TracksPerCylinder)

    ' S.M.A.R.T. Attributes
    Console.WriteLine()
    Console.WriteLine("S.M.A.R.T. Attributes:")
    Dim sb As New StringBuilder()
    For Each attr As SmartAttribute In hdd.SMART.Attributes

        sb.AppendFormat("Id: {0:X2}, Name: {1,-30}, Current: {2,3}, Worst: {3,3}, Threshold: {4,3}, RAW: {5,12:X12}, IsHealthOk?: {6}",
                        attr.Id, attr.Name,
                        attr.CurrentValue, attr.WorstValue, attr.Threshold, attr.RawValue32,
                        attr.IsHealthOk)
        sb.AppendLine()

    Next
    Console.WriteLine(sb.ToString())
    Console.WriteLine()

Next hdd
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />