# TextMetricA Structure
 

Contains basic information about a physical font. 

 All sizes are specified in logical units; that is, they depend on the current mapping mode of the display context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct TextMetricA
```

**VB**<br />
``` VB
Public Structure TextMetricA
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextMetricA
```

**C++**<br />
``` C++
public value class TextMetricA
```

**F#**<br />
``` F#
[<SealedAttribute>]
type TextMetricA =  struct end
```

The TextMetricA type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Ascent">Ascent</a></td><td>
The ascent (units above the base line) of characters.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_AveCharWidth">AveCharWidth</a></td><td>
The average width of characters in the font (generally defined as the width of the letter x).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_BreakChar">BreakChar</a></td><td>
The value of the character that will be used to define word breaks for text justification</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_CharSet">CharSet</a></td><td>
The character set of the font.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_DefaultChar">DefaultChar</a></td><td>
The value of the character to be substituted for characters not in the font.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Descent">Descent</a></td><td>
The descent (units below the base line) of characters</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_DigitizedAspectX">DigitizedAspectX</a></td><td>
The horizontal aspect of the device for which the font was designed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_DigitizedAspectY">DigitizedAspectY</a></td><td>
The vertical aspect of the device for which the font was designed.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_ExternalLeading">ExternalLeading</a></td><td>
The amount of extra leading (space) that the application adds between rows.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_FirstChar">FirstChar</a></td><td>
The value of the first character defined in the font.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Height">Height</a></td><td>
The height (ascent + descent) of characters.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_InternalLeading">InternalLeading</a></td><td>
The amount of leading (space) inside the bounds set by the tmHeight member.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Italic">Italic</a></td><td>
Specifies an italic font if it is nonzero</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_LastChar">LastChar</a></td><td>
The value of the last character defined in the font.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_MaxCharWidth">MaxCharWidth</a></td><td>
The width of the widest character in the font.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Overhang">Overhang</a></td><td>
The extra width per string that may be added to some synthesized fonts.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_PitchAndFamily">PitchAndFamily</a></td><td>
Specifies information about the pitch, the technology, and the family of a physical font.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_StruckOut">StruckOut</a></td><td>
A strikeout font if it is nonzero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Underlined">Underlined</a></td><td>
Specifies an underlined font if it is nonzero</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_TextMetricA_Weight">Weight</a></td><td>
The weight of the font.</td></tr></table>&nbsp;
<a href="#textmetrica-structure">Back to Top</a>

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
<a href="#textmetrica-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd145132(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd145132(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />