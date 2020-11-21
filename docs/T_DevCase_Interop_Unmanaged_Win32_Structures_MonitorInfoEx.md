# MonitorInfoEx Structure
 

Contains information about a display monitor. 

 The <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMonitorInfo">GetMonitorInfo(IntPtr, MonitorInfo)</a> function stores information into a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfo">MonitorInfo</a> structure or a MonitorInfoEx structure. 

 The MonitorInfoEx structure is a superset of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfo">MonitorInfo</a> structure. The MonitorInfoEx structure adds a string member to contain a name for the display monitor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct MonitorInfoEx
```

**VB**<br />
``` VB
Public Structure MonitorInfoEx
```

**VB Usage**<br />
``` VB Usage
Dim instance As MonitorInfoEx
```

**C++**<br />
``` C++
public value class MonitorInfoEx
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MonitorInfoEx =  struct end
```

The MonitorInfoEx type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx__ctor">MonitorInfoEx</a></td><td>
Initializes a new instance of the MonitorInfoEx structure.</td></tr></table>&nbsp;
<a href="#monitorinfoex-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Bounds">Bounds</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the display monitor rectangle, expressed in virtual-screen coordinates. 

 Note that if the monitor is not the primary display monitor, some of the rectangle's coordinates may be negative values.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_DeviceName">DeviceName</a></td><td>
A string that specifies the device name of the monitor being used. 

 Most applications have no use for a display monitor name, and so can save some bytes by using a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfo">MonitorInfo</a> structure.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Flags">Flags</a></td><td>
The attributes of the display monitor.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size, in bytes, of the structure. 

 This member must be set to `Marshal.SizeOf(Of MonitorInfoEx)` before calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMonitorInfo">GetMonitorInfo(IntPtr, MonitorInfo)</a> function. Doing so lets the function determine the type of structure you are passing to it.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_WorkingArea">WorkingArea</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">NativeRectangle</a> structure that specifies the work area rectangle of the display monitor that can be used by applications, expressed in virtual-screen coordinates. 

 Windows uses this rectangle to maximize an application on the monitor. The rest of the area in <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MonitorInfoEx_Bounds">Bounds</a> contains system windows such as the task bar and side bars. 

 Note that if the monitor is not the primary display monitor, some of the rectangle's coordinates may be negative values.</td></tr></table>&nbsp;
<a href="#monitorinfoex-structure">Back to Top</a>

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
<a href="#monitorinfoex-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145066(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145066(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />