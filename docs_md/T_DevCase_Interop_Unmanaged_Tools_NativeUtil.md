# NativeUtil Class
 

Contains win32 related utilites.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Interop.Unmanaged.Tools.NativeUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class NativeUtil
```

**VB**<br />
``` VB
Public NotInheritable Class NativeUtil
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeUtil
```

**C++**<br />
``` C++
public ref class NativeUtil sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
type NativeUtil =  class end
```

The NativeUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_CallNativeFunction__2">CallNativeFunction(TResult, TDelegate)</a></td><td>
Executes a function exported in a native dll and returns the result value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailFastIfFalse">FailFastIfFalse</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to `false` (`False` in Visual Basic), immediately terminates the calling process after writing the corresponding Win32 error message to the Windows Application event log. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailFastIfZero">FailFastIfZero(Int32)</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to zero, immediately terminates the calling process after writing the corresponding Win32 error message to the Windows Application event log. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailFastIfZero_1">FailFastIfZero(IntPtr)</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to Zero, immediately terminates the calling process after writing the corresponding Win32 error message to the Windows Application event log. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailFastIfZero_2">FailFastIfZero(UInt32)</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to zero, immediately terminates the calling process after writing the corresponding Win32 error message to the Windows Application event log. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailIfFalse">FailIfFalse</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to `false` (`False` in Visual Basic), throws the corresponding Win32Exception. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailIfZero">FailIfZero(Int32)</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to zero, throws the corresponding Win32Exception. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailIfZero_1">FailIfZero(IntPtr)</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to Zero, throws the corresponding Win32Exception. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailIfZero_2">FailIfZero(UInt32)</a></td><td>
Evaluates the supplied unmanaged return value and, if it is equal to zero, throws the corresponding Win32Exception. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetHiByte">GetHiByte</a></td><td>
Gets the high-order byte of a WORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetHiDWord">GetHiDWord</a></td><td>
Gets the high-order DWORD of a DWORDLONG value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetHiWord">GetHiWord(IntPtr)</a></td><td>
Gets the high-order WORD of a DWORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetHiWord_1">GetHiWord(UInt32)</a></td><td>
Gets the high-order WORD of a DWORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetLoByte">GetLoByte</a></td><td>
Gets the low-order byte of a WORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetLoDWord">GetLoDWord</a></td><td>
Gets the low-order DWORD of a DWORDLONG value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetLoWord">GetLoWord(IntPtr)</a></td><td>
Gets the low-order WORD of a DWORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetLoWord_1">GetLoWord(UInt32)</a></td><td>
Gets the low-order WORD of a DWORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetNativeFunction__1">GetNativeFunction(TDelegate)</a></td><td>
Gets a function exported in a native dll.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeDWord">MakeDWord</a></td><td>
Creates a (32-Bit Unsigned Integer) DWORD value from a LOWORD and a HIWORD.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeDWordLong">MakeDWordLong</a></td><td>
Creates a (64-Bit Unsigned Integer) DWORDLONG value from a LODWORD and a HIDWORD.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeLParam">MakeLParam(Int32, Int32)</a></td><td>
Creates a lParam value from two Int32 values. 

 You must call this method overload if you need to use negative values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeLParam_1">MakeLParam(UInt16, UInt16)</a></td><td>
Creates a lParam value from two UInt16 values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeWord">MakeWord</a></td><td>
Creates a (16-Bit Unsigned Integer) WORD value from a LOBYTE and a HIBYTE.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeWParam">MakeWParam(Int32, Int32)</a></td><td>
Creates a wParam value from two Int32 values. 

 You must call this method overload if you need to use negative values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeWParam_1">MakeWParam(UInt16, UInt16)</a></td><td>
Creates a wParam value from two UInt16 values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SafePInvoke__1">SafePInvoke(T)(Expression(Func(T)), Boolean)</a></td><td>
Invokes a platform invoke encapsulated function, providing a higher safety level for error-handling. 

 If the function that was called using platform invoke has the SetLastError, then it checks the exit code returned by the function, and, if is not same as *successValue*, throws the corresponding Win32Exception.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SafePInvoke__1_1">SafePInvoke(T)(Expression(Func(T)), Int32)</a></td><td>
Invokes a platform invoke encapsulated function, providing a higher safety level for error-handling. 

 If the function that was called using platform invoke has the SetLastError, then it checks the exit code returned by the function, and, if is not same as *successValue*, throws the corresponding Win32Exception.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SetHiByte">SetHiByte</a></td><td>
Sets the high-order byte of an WORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SetHiDword">SetHiDword</a></td><td>
Sets the high-order DWORD of a DWORDLONG value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SetHiWord">SetHiWord</a></td><td>
Sets the high-order WORD of a DWORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SetLoByte">SetLoByte</a></td><td>
Sets the low-order byte of a WORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SetLoDword">SetLoDword</a></td><td>
Sets the low-order DWORD of an DWORDLONG value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_SetLoWord">SetLoWord</a></td><td>
Sets the low-order WORD of a DWORD value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_UnmanagedTypeToManagedType">UnmanagedTypeToManagedType</a></td><td>
Translates a value of the UnmanagedType enumeration to an appropriated .NET managed type equivalent.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Interop_Unmanaged_Tools_NativeUtil_WindowsGuidToManagedGuid">WindowsGuidToManagedGuid</a></td><td>
Translates a GUID that is defined in a Windows C++ header file using the `DEFINE_GUID` macro, to a managed Guid.</td></tr></table>&nbsp;
<a href="#nativeutil-class">Back to Top</a>

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
<a href="#nativeutil-class">Back to Top</a>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa383751%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa383751%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />