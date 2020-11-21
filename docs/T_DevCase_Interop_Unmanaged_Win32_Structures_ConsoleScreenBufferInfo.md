# ConsoleScreenBufferInfo Structure
 

Contains information about a console screen buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ConsoleScreenBufferInfo
```

**VB**<br />
``` VB
Public Structure ConsoleScreenBufferInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleScreenBufferInfo
```

**C++**<br />
``` C++
public value class ConsoleScreenBufferInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ConsoleScreenBufferInfo =  struct end
```

The ConsoleScreenBufferInfo type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleScreenBufferInfo_Attributes">Attributes</a></td><td>
The attributes of the characters written or echoed to a screen buffer.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleScreenBufferInfo_CursorPosition">CursorPosition</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that contains the column and row coordinates of the cursor in the console screen buffer.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleScreenBufferInfo_MaximumWindowSize">MaximumWindowSize</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that contains the maximum size of the console window, in character columns and rows, given the current screen buffer size and font and the screen size.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleScreenBufferInfo_Size">Size</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that contains the size of the console screen buffer, in character columns and rows.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleScreenBufferInfo_Window">Window</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangleSmall">NativeRectangleSmall</a> structure that contains the console screen buffer coordinates of the upper-left and lower-right corners of the display window.</td></tr></table>&nbsp;
<a href="#consolescreenbufferinfo-structure">Back to Top</a>

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
<a href="#consolescreenbufferinfo-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/console-screen-buffer-info-str" target="_blank">https://docs.microsoft.com/en-us/windows/console/console-screen-buffer-info-str</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />