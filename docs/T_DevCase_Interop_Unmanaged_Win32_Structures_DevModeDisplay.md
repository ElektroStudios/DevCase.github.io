# DevModeDisplay Structure
 

Contains information about a display device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct DevModeDisplay
```

**VB**<br />
``` VB
Public Structure DevModeDisplay
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevModeDisplay
```

**C++**<br />
``` C++
public value class DevModeDisplay
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DevModeDisplay =  struct end
```

The DevModeDisplay type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay_DisplayFixedOutput">DisplayFixedOutput</a></td><td>
For fixed-resolution display devices only, how the display presents a low-resolution mode on a higher-resolution display. 

 For example, if a display device's resolution is fixed at 1024 x 768 pixels but its mode is set to 640x480 pixels, the device can either display a 640x480 image somewhere in the interior of the 1024x768 screen space or stretch the 640x480 image to fill the larger screen space. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">DisplayFixedOutput</a> is not set, this member must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay_DisplayOrientation">DisplayOrientation</a></td><td>
For display devices only, the orientation at which images should be presented. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeFields">DisplayOrientation</a> is not set, this member must be <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DeviceModeDisplayOrientation">Default</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModeDisplay_Position">Position</a></td><td>
For display devices only, a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">NativePoint</a> struct that indicates the positional coordinates of the display device in reference to the desktop area. 

 The primary display device is always located at coordinates (0,0).</td></tr></table>&nbsp;
<a href="#devmodedisplay-structure">Back to Top</a>

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
<a href="#devmodedisplay-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183565%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183565%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />