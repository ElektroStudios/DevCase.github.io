# MouseLowLevelHookStruct Structure
 

Contains information about a low-level mouse input event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct MouseLowLevelHookStruct
```

**VB**<br />
``` VB
Public Structure MouseLowLevelHookStruct
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseLowLevelHookStruct
```

**C++**<br />
``` C++
public value class MouseLowLevelHookStruct
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MouseLowLevelHookStruct =  struct end
```

The MouseLowLevelHookStruct type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_ExtraInfo">ExtraInfo</a></td><td>
Additional information associated with the message.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Flags">Flags</a></td><td>
The extended-key flag, event-injected flags, context code, and transition-state flag. 

 This member is specified as follows. An application can use the following values to test the mouse flags. 

 Testing `LLKHF_INJECTED` (bit 4) will tell you whether the event was injected. If it was, then testing `LLKHF_LOWER_IL_INJECTED` (bit 1) will tell you whether or not the event was injected from a process running at lower integrity level.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_MouseData">MouseData</a></td><td>
If the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_MouseWheel</a>, the high-order word of this member is the wheel delta. 

 ( The low-order word is reserved. ) 

 A positive value indicates that the wheel was rotated forward, away from the user; a negative value indicates that the wheel was rotated backward, toward the user. 

 One wheel click is defined as `WHEEL_DELTA`, which is `120`. 





 If the message is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonUp</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_XButtonDblClk</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonDown</a>, <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonUp</a>, or <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_NcXButtonDblClk</a>, the high-order word specifies which X button was pressed or released, and the low-order word is reserved. 

 This value can be one or more of the following values. Otherwise, mouseData is not used.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Point">Point</a></td><td>
The x- and y-coordinates of the cursor, in screen coordinates.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_MouseLowLevelHookStruct_Time">Time</a></td><td>
The time stamp for this message, equivalent to what `GetMessageTime` would return for this message.</td></tr></table>&nbsp;
<a href="#mouselowlevelhookstruct-structure">Back to Top</a>

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
<a href="#mouselowlevelhookstruct-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms644970(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms644970(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />