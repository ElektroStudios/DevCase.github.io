# BroadcastSystemMessageExInfo Structure
 

Contains additional information of a message when calling <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct BroadcastSystemMessageExInfo
```

**VB**<br />
``` VB
Public Structure BroadcastSystemMessageExInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As BroadcastSystemMessageExInfo
```

**C++**<br />
``` C++
public value class BroadcastSystemMessageExInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type BroadcastSystemMessageExInfo =  struct end
```

The BroadcastSystemMessageExInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo__ctor">BroadcastSystemMessageExInfo</a></td><td>
Initializes a new instance of the BroadcastSystemMessageExInfo structure.</td></tr></table>&nbsp;
<a href="#broadcastsystemmessageexinfo-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Hdesk">Hdesk</a></td><td>
A desktop handle to the window specified by <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Hwnd">Hwnd</a>. 

 This value is returned only if <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">ReturnHDesk</a> and <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Hwnd">Hwnd</a></td><td>
A handle to the window that denied the request. 

 This value is returned only if <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_BroadcastSystemMessageEx">BroadcastSystemMessageEx(BroadcastSystemMessageFlags, BroadcastSystemMessageInfo, WindowMessages, IntPtr, IntPtr, BroadcastSystemMessageExInfo)</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_BroadcastSystemMessageFlags">Query</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_Luid">Luid</a></td><td>
A locally unique identifier (LUID) for the window.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_BroadcastSystemMessageExInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of BroadcastSystemMessageExInfo)` before calling any function.</td></tr></table>&nbsp;
<a href="#broadcastsystemmessageexinfo-structure">Back to Top</a>

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
<a href="#broadcastsystemmessageexinfo-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-broadcastsystemmessageexa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />