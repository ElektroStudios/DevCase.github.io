# IconInfo Structure
 

Contains information about an icon or a cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct IconInfo
```

**VB**<br />
``` VB
Public Structure IconInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As IconInfo
```

**C++**<br />
``` C++
public value class IconInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type IconInfo =  struct end
```

The IconInfo type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_Color">Color</a></td><td>
A handle to the icon color bitmap. 

 This member can be optional if this structure defines a black and white icon. 

 The `AND` bitmask of <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_Mask">Mask</a> member is applied with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">SrcAnd</a> flag to the destination; subsequently, the color bitmap is applied (using `XOR`) to the destination by using the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_TernaryRasterOperations">SrcInvert</a> flag.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_IsIcon">IsIcon</a></td><td>
Specifies whether this structure defines an icon or a cursor. 

 A value of `true` (`True` in Visual Basic) specifies an icon; `false` (`False` in Visual Basic) specifies a cursor.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_Mask">Mask</a></td><td>
The icon bitmask bitmap. 

 If this structure defines a black and white icon, this bitmask is formatted so that the upper half is the icon `AND` bitmask and the lower half is the icon `XOR` bitmask. 

 Under this condition, the height should be an even multiple of two. 

 If this structure defines a color icon, this mask only defines the `AND` bitmask of the icon.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_X">X</a></td><td>
The x-coordinate of a cursor's hot spot. 

 If this structure defines an icon, the hot spot is always in the center of the icon, and this member is ignored.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo_Y">Y</a></td><td>
The y-coordinate of the cursor's hot spot. 

 If this structure defines an icon, the hot spot is always in the center of the icon, and this member is ignored</td></tr></table>&nbsp;
<a href="#iconinfo-structure">Back to Top</a>

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
<a href="#iconinfo-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648052%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648052%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />