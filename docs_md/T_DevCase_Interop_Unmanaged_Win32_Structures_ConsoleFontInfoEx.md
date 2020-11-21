# ConsoleFontInfoEx Structure
 

Contains extended information for a console font.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ConsoleFontInfoEx
```

**VB**<br />
``` VB
Public Structure ConsoleFontInfoEx
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleFontInfoEx
```

**C++**<br />
``` C++
public value class ConsoleFontInfoEx
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ConsoleFontInfoEx =  struct end
```

The ConsoleFontInfoEx type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx__ctor">ConsoleFontInfoEx</a></td><td>
Initializes a new instance of the ConsoleFontInfoEx structure.</td></tr></table>&nbsp;
<a href="#consolefontinfoex-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FaceName">FaceName</a></td><td>
The name of the font typeface (such as Arial, Courier or Consolas).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontFamily">FontFamily</a></td><td>
The font pitch and family.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontIndex">FontIndex</a></td><td>
The index of the font in the system's console font table.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontSize">FontSize</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate">ConsoleCoordinate</a> structure that contains the width and height of each character in the font, in logical units. 

 The <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_X">X</a> member contains the width, while the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleCoordinate_Y">Y</a> member contains the height.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_FontWeight">FontWeight</a></td><td>
The font weight. 

 The weight can range from 100 to 1000, in multiples of 100. For example, the normal weight is 400, while 700 is bold.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ConsoleFontInfoEx_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of ConsoleFontInfoEx)` before calling any function.</td></tr></table>&nbsp;
<a href="#consolefontinfoex-structure">Back to Top</a>

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
<a href="#consolefontinfoex-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/console/console-font-infoex" target="_blank">https://docs.microsoft.com/en-us/windows/console/console-font-infoex</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />