# SafeHandleZeroIsInvalid Class
 

Base class for Windows Interop Safe handles with null IntPtr as invalid.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Runtime.ConstrainedExecution.CriticalFinalizerObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Runtime.InteropServices.SafeHandle<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeHandleZeroIsInvalid<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeBitmapHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeBitmapHandle</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeCursorHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeCursorHandle</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeIconHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeIconHandle</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeRegionHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeRegionHandle</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeWindowHandle">DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeWindowHandle</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_SafeHandles">DevCase.Interop.Unmanaged.Win32.SafeHandles</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public abstract class SafeHandleZeroIsInvalid : SafeHandle
```

**VB**<br />
``` VB
Public MustInherit Class SafeHandleZeroIsInvalid
	Inherits SafeHandle
```

**VB Usage**<br />
``` VB Usage
Dim instance As SafeHandleZeroIsInvalid
```

**C++**<br />
``` C++
public ref class SafeHandleZeroIsInvalid abstract : public SafeHandle
```

**F#**<br />
``` F#
[<AbstractClassAttribute>]
type SafeHandleZeroIsInvalid =  
    class
        inherit SafeHandle
    end
```

The SafeHandleZeroIsInvalid type exposes the following members.


## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeHandleZeroIsInvalid_IsInvalid">IsInvalid</a></td><td>
Determines rhether this is a valid handle.
 (Overrides SafeHandle.IsInvalid.)</td></tr></table>&nbsp;
<a href="#safehandlezeroisinvalid-class">Back to Top</a>

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
<a href="#safehandlezeroisinvalid-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_SafeHandles">DevCase.Interop.Unmanaged.Win32.SafeHandles Namespace</a><br />