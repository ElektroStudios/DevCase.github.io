# DeviceUtil Class
 

Contains devices related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.Tools.DeviceUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class DeviceUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class DeviceUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As DeviceUtil
```

**C++**<br />
``` C++
public ref class DeviceUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DeviceUtil =  
    class
        inherit AestheticObject
    end
```

The DeviceUtil type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_IO_Tools_DeviceUtil_BiosVersion">BiosVersion</a></td><td>
Gets the version of the motherboard BIOS.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_IO_Tools_DeviceUtil_MotherboardId">MotherboardId</a></td><td>
Gets the identifier of the current motherboard.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_IO_Tools_DeviceUtil_PrinterNames">PrinterNames</a></td><td>
Gets the names of all the printers installed on this computer.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_IO_Tools_DeviceUtil_ProcessorId">ProcessorId</a></td><td>
Gets the identifier of the current CPU.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_IO_Tools_DeviceUtil_ProcessorMaxSpeed">ProcessorMaxSpeed</a></td><td>
Gets the maximum speed of the current CPU, in Mhz.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="P_DevCase_Core_IO_Tools_DeviceUtil_ProcessorSpeed">ProcessorSpeed</a></td><td>
Gets the current speed of the current CPU, in Mhz.</td></tr></table>&nbsp;
<a href="#deviceutil-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_BlockInput">BlockInput</a></td><td>
Blocks the keyboard and mouse input events. 

 When blocked, the user cannot send keystrokes or use the mouse.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_FormatDrive">FormatDrive</a></td><td>
Formats a drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetDriveFreeSpace">GetDriveFreeSpace</a></td><td>
Gets the free disk space, in bytes, of the specified drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetDriveInfo">GetDriveInfo</a></td><td>
Returns the corresponding DriveInfo for the specified drive letter.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetDrivesInfoOf">GetDrivesInfoOf</a></td><td>
Gets all the drives of the specified DriveType.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetDriveSize">GetDriveSize</a></td><td>
Gets the total size, in bytes, of the specified drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetHardDriveHandle">GetHardDriveHandle(Char)</a></td><td>
Gets a handle to the specified hard drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetHardDriveHandle_1">GetHardDriveHandle(DriveInfo)</a></td><td>
Gets a handle to the specified hard drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetWin32DiskDrive">GetWin32DiskDrive(Char)</a></td><td>
Gets a ManagementObject which wraps a instance of 'Win32_DiskDrive' WMI class for the specified drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetWin32DiskDrive_1">GetWin32DiskDrive(DriveInfo)</a></td><td>
Gets a ManagementObject which wraps a instance of 'Win32_DiskDrive' WMI class for the specified drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetWin32LogicalDisk">GetWin32LogicalDisk(Char)</a></td><td>
Gets a ManagementObject which wraps a instance of 'Win32_LogicalDisk' WMI class for the specified drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_GetWin32LogicalDisk_1">GetWin32LogicalDisk(DriveInfo)</a></td><td>
Gets a ManagementObject which wraps a instance of 'Win32_LogicalDisk' WMI class for the specified drive.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_SetPrimaryScreenResolution">SetPrimaryScreenResolution(Size)</a></td><td>
Sets the resolution of the primary screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_SetPrimaryScreenResolution_1">SetPrimaryScreenResolution(Int32, Int32)</a></td><td>
Sets the resolution of the primary screen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_TryGetDriveInfo">TryGetDriveInfo</a></td><td>
Tries to get the corresponding DriveInfo for the specified drive letter.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_IO_Tools_DeviceUtil_UnblockInput">UnblockInput</a></td><td>
Blocks the keyboard and mouse input. 

 When blocked, the user cannot send keystrokes or use the mouse.</td></tr></table>&nbsp;
<a href="#deviceutil-class">Back to Top</a>

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
<a href="#deviceutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO_Tools">DevCase.Core.IO.Tools Namespace</a><br />