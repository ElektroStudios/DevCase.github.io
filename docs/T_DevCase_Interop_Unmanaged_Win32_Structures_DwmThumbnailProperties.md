# DwmThumbnailProperties Structure
 

Specifies Desktop Window Manager (DWM) thumbnail properties. 

 Used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmUpdateThumbnailProperties">DwmUpdateThumbnailProperties(IntPtr, DwmThumbnailProperties)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct DwmThumbnailProperties
```

**VB**<br />
``` VB
Public Structure DwmThumbnailProperties
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmThumbnailProperties
```

**C++**<br />
``` C++
public value class DwmThumbnailProperties
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DwmThumbnailProperties =  struct end
```

The DwmThumbnailProperties type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties_DstRectangle">DstRectangle</a></td><td>
The area in the destination window where the thumbnail will be rendered.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties_Flags">Flags</a></td><td>
A bitwise combination of DWM thumbnail constant values that indicates which members of this structure are set.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties_Opacity">Opacity</a></td><td>
The opacity with which to render the thumbnail. 

 0 is fully transparent while 255 is fully opaque. 

 The default value is 255.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties_SourceClientAreaOnly">SourceClientAreaOnly</a></td><td>
`true` (`True` in Visual Basic) to use only the thumbnail source's client area; otherwise, `false` (`False` in Visual Basic). 

 The default is `false` (`False` in Visual Basic).</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties_SrcRectangle">SrcRectangle</a></td><td>
The region of the source window to use as the thumbnail. By default, the entire window is used as the thumbnail.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmThumbnailProperties_Visible">Visible</a></td><td>
`true` (`True` in Visual Basic) to make the thumbnail visible; otherwise, `false` (`False` in Visual Basic). 

 The default is `false` (`False` in Visual Basic).</td></tr></table>&nbsp;
<a href="#dwmthumbnailproperties-structure">Back to Top</a>

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
<a href="#dwmthumbnailproperties-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/ns-dwmapi-_dwm_thumbnail_properties" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/ns-dwmapi-_dwm_thumbnail_properties</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />