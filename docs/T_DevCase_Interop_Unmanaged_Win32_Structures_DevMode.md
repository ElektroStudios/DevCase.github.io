# DevMode Structure
 

Contains information about the initialization and environment of a display device or a printer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct DevMode
```

**VB**<br />
``` VB
Public Structure DevMode
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
```

**C++**<br />
``` C++
public value class DevMode
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DevMode =  struct end
```

The DevMode type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_DevMode__ctor">DevMode</a></td><td>
Initializes a new instance of the DevMode structure.</td></tr></table>&nbsp;
<a href="#devmode-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_BitsPerPixel">BitsPerPixel</a></td><td>
Specifies the color resolution, in bits per pixel, of the display device (for example: 4 bits for 16 colors, 8 bits for 256 colors, or 16 bits for 65,536 colors). 

 Display drivers use this member, for example, in the `ChangeDisplaySettings` function. 

 Printer drivers do not use this member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Collate">Collate</a></td><td>
Specifies whether collation should be used when printing multiple copies. 

 This member is ignored unless the printer driver indicates support for collation by setting the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Fields">Fields</a> member to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">Collate</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Color">Color</a></td><td>
Switches between color and monochrome on color printers.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DeviceName">DeviceName</a></td><td>
A zero-terminated character array that specifies the "friendly" name of the printer or display; for example, "`PCL/HP LaserJet`" in the case of PCL/HP LaserJet. This string is unique among device drivers. 

 Note that this name may be truncated to fit in the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DeviceName">DeviceName</a> array.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DisplayFrequency">DisplayFrequency</a></td><td>
Only for Display drivers, specifies the frequency, in hertz (cycles per second), of the display device in a particular mode. 

 This value is also known as the display device's vertical refresh rate. 

 It is used, for example, in the `ChangeDisplaySettings` function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DitherType">DitherType</a></td><td>
Specifies how dithering is to be done. 

 The member can be one of the following predefined values, or a driver-defined value greater than or equal to the value of `DMDITHER_USER`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DriverExtra">DriverExtra</a></td><td>
Contains the number of bytes of private driver-data that follow this structure. 

 If a device driver does not use device-specific information, set this member to zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_DriverVersion">DriverVersion</a></td><td>
The driver version number assigned by the driver developer.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Duplex">Duplex</a></td><td>
Selects duplex or double-sided printing for printers capable of duplex printing.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Fields">Fields</a></td><td>
Specifies whether certain members of the DevMode structure have been initialized. 

 If a member is initialized, its corresponding bit is set, otherwise the bit is clear. 

 A driver supports only those DevMode members that are appropriate for the printer or display technology.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Flags">Flags</a></td><td>
Specifies the device's flags.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_FormName">FormName</a></td><td>
A zero-terminated character array that specifies the name of the form to use; for example, "`Letter`" or "`Legal`". A complete set of names can be retrieved by using the `EnumForms` function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_IcmIntent">IcmIntent</a></td><td>
Specifies which color matching method, or intent, should be used by default. 

 This member is primarily for non-ICM applications. 

 ICM applications can establish intents by using the ICM functions. 

 This member can be one of the following predefined values, or a driver defined value greater than or equal to the value of `DMICM_USER`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_IcmMethod">IcmMethod</a></td><td>
Specifies how ICM is handled. 

 For a non-ICM application, this member determines if ICM is enabled or disabled. 

 For ICM applications, the system examines this member to determine how to handle ICM support. 

 This member can be one of the following predefined values, or a driver-defined value greater than or equal to the value of `DMICMMETHOD_USER`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_LogPixels">LogPixels</a></td><td>
The number of pixels per logical inch. Printer drivers do not use this member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_MediaType">MediaType</a></td><td>
Specifies the type of media being printed on. 

 The member can be one of the following predefined values, or a driver-defined value greater than or equal to the value of `DMMEDIA_USER`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Mode">Mode</a></td><td>
Contains information about a device.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_PanningHeight">PanningHeight</a></td><td>
This member must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_PanningWidth">PanningWidth</a></td><td>
This member must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_PixelsHeight">PixelsHeight</a></td><td>
Specifies the height, in pixels, of the visible device surface. 

 Display drivers use this member, for example, in the `ChangeDisplaySettings` function. 

 Printer drivers do not use this member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_PixelsWidth">PixelsWidth</a></td><td>
Specifies the width, in pixels, of the visible device surface. 

 Display drivers use this member, for example, in the `ChangeDisplaySettings` function. 

 Printer drivers do not use this member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Reserved1">Reserved1</a></td><td>
Not used; must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_Reserved2">Reserved2</a></td><td>
Not used; must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_SizeOfStruct">SizeOfStruct</a></td><td>
Specifies the size, in bytes, of the DevMode structure, not including any private driver-specific data that might follow the structure's public members. 

 This member must be set to `Marshal.SizeOf(Of DevMode)` before calling any function, to indicate the version of the DevMode structure being used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_SpecVersion">SpecVersion</a></td><td>
The version number of the initialization data specification on which the structure is based. 

 To ensure the correct version is used for any operating system, use `DM_SPECVERSION`.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_TTOption">TTOption</a></td><td>
Specifies how TrueType fonts should be printed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevMode_YResolution">YResolution</a></td><td>
Specifies the y-resolution, in dots per inch, of the printer. 

 If the printer initializes this member, the `PrintQuality` member specifies the x-resolution, in dots per inch, of the printer.</td></tr></table>&nbsp;
<a href="#devmode-structure">Back to Top</a>

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
<a href="#devmode-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183565%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183565%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />