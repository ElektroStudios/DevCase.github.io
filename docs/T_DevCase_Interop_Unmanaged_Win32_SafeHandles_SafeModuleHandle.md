# SafeModuleHandle Class
 

Represents a handle to a module returned by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibrary">LoadLibrary(String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadLibraryEx">LoadLibraryEx(String, IntPtr, LoadLibraryFlags)</a> functions.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.Runtime.ConstrainedExecution.CriticalFinalizerObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.Runtime.InteropServices.SafeHandle<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Microsoft.Win32.SafeHandles.SafeHandleZeroOrMinusOneIsInvalid<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Interop.Unmanaged.Win32.SafeHandles.SafeModuleHandle<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_SafeHandles">DevCase.Interop.Unmanaged.Win32.SafeHandles</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SafeModuleHandle : SafeHandleZeroOrMinusOneIsInvalid
```

**VB**<br />
``` VB
Public NotInheritable Class SafeModuleHandle
	Inherits SafeHandleZeroOrMinusOneIsInvalid
```

**VB Usage**<br />
``` VB Usage
Dim instance As SafeModuleHandle
```

**C++**<br />
``` C++
public ref class SafeModuleHandle sealed : public SafeHandleZeroOrMinusOneIsInvalid
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SafeModuleHandle =  
    class
        inherit SafeHandleZeroOrMinusOneIsInvalid
    end
```

The SafeModuleHandle type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeModuleHandle__ctor">SafeModuleHandle()</a></td><td>
Initializes a new instance of the SafeModuleHandle class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_SafeHandles_SafeModuleHandle__ctor_1">SafeModuleHandle(IntPtr)</a></td><td>
Initializes a new instance of the SafeModuleHandle class.</td></tr></table>&nbsp;
<a href="#safemodulehandle-class">Back to Top</a>

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
<a href="#safemodulehandle-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_SafeHandles">DevCase.Interop.Unmanaged.Win32.SafeHandles Namespace</a><br />