# ChangeFilter Structure
 

Contains extended result information obtained by calling the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ChangeFilter
```

**VB**<br />
``` VB
Public Structure ChangeFilter
```

**VB Usage**<br />
``` VB Usage
Dim instance As ChangeFilter
```

**C++**<br />
``` C++
public value class ChangeFilter
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ChangeFilter =  struct end
```

The ChangeFilter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter__ctor">ChangeFilter</a></td><td>
Initializes a new instance of the ChangeFilter structure.</td></tr></table>&nbsp;
<a href="#changefilter-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter_ExtStatus">ExtStatus</a></td><td>
If the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function succeeds, this field contains information about the success.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ChangeFilter_SizeOfStruct">SizeOfStruct</a></td><td>
The size of this structure, In bytes. 

 Set this member to `Marshal.SizeOf(Of ChangeFilter)`, otherwise the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ChangeWindowMessageFilterEx">ChangeWindowMessageFilterEx(IntPtr, EditControlMessages, ChangeWindowMessageFilterExAction, ChangeFilter)</a> function fails with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">E_INVALIDARG</a>.</td></tr></table>&nbsp;
<a href="#changefilter-structure">Back to Top</a>

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
<a href="#changefilter-structure">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd388197%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd388197%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />