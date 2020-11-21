# DwmBlurBehind Structure
 

Contains Desktop Window Manager (DWM) blur-behind properties. 

 Used by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmEnableBlurBehindWindow">DwmEnableBlurBehindWindow(IntPtr, DwmBlurBehind)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct DwmBlurBehind
```

**VB**<br />
``` VB
Public Structure DwmBlurBehind
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmBlurBehind
```

**C++**<br />
``` C++
public value class DwmBlurBehind
```

**F#**<br />
``` F#
[<SealedAttribute>]
type DwmBlurBehind =  struct end
```

The DwmBlurBehind type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind__ctor">DwmBlurBehind</a></td><td>
Initializes a new instance of the DwmBlurBehind struct.</td></tr></table>&nbsp;
<a href="#dwmblurbehind-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_Region">Region</a></td><td>
Gets the region.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_TransitionOnMaximized">TransitionOnMaximized</a></td><td>
Gets or sets a value indicating whether the window's colorization should transition to match the maximized windows.</td></tr></table>&nbsp;
<a href="#dwmblurbehind-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_SetRegion">SetRegion</a></td><td>
Sets the region.</td></tr></table>&nbsp;
<a href="#dwmblurbehind-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_BlurRegion">BlurRegion</a></td><td>
The region within the client area where the blur behind will be applied. 

 A value of Zero will apply the blur behind the entire client area.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_Enable">Enable</a></td><td>
`true` (`True` in Visual Basic) to register the window handle to DWM blur behind; `false` (`False` in Visual Basic) to unregister the window handle from DWM blur behind.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_Flags">Flags</a></td><td>
A combination of <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmBlurBehindFlags">DwmBlurBehindFlags</a> values that indicates which of the members of this structure have been set.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind_TransitionOnMaximized_">TransitionOnMaximized_</a></td><td>
`true` (`True` in Visual Basic) if the window's colorization should transition to match the maximized windows; otherwise, `false` (`False` in Visual Basic).</td></tr></table>&nbsp;
<a href="#dwmblurbehind-structure">Back to Top</a>

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
<a href="#dwmblurbehind-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/ns-dwmapi-_dwm_blurbehind" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/dwmapi/ns-dwmapi-_dwm_blurbehind</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />