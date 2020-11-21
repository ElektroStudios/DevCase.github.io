# KeyboardInput Structure
 

Contains information about a simulated keyboard event.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct KeyboardInput
```

**VB**<br />
``` VB
Public Structure KeyboardInput
```

**VB Usage**<br />
``` VB Usage
Dim instance As KeyboardInput
```

**C++**<br />
``` C++
public value class KeyboardInput
```

**F#**<br />
``` F#
[<SealedAttribute>]
type KeyboardInput =  struct end
```

The KeyboardInput type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ExtraInfo">ExtraInfo</a></td><td>
An additional value associated with the keystroke. 

 Use the `GetMessageExtraInfo` function to obtain this information.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a></td><td>
Specifies various aspects of a keystroke.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ScanCode">ScanCode</a></td><td>
A hardware scan code for the key. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardInputFlags">Unicode</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_ScanCode">ScanCode</a> specifies a Unicode character which is to be sent to the foreground application.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Time">Time</a></td><td>
The time stamp for the event, in milliseconds. 

 If this parameter is `0`, the system will provide its own time stamp.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_VirtualKey">VirtualKey</a></td><td>
A virtual-key code. 

 The code must be a value in the range `1` to `254`. 

 If the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_Flags">Flags</a> member specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_KeyboardInputFlags">Unicode</a>, <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_KeyboardInput_VirtualKey">VirtualKey</a> must be `0`.</td></tr></table>&nbsp;
<a href="#keyboardinput-structure">Back to Top</a>

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
<a href="#keyboardinput-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646271%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646271%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />