# ProcessStartupInfo Structure
 

Specifies the window station, desktop, standard handles, and appearance of the main window for a process at creation time.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct ProcessStartupInfo
```

**VB**<br />
``` VB
Public Structure ProcessStartupInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProcessStartupInfo
```

**C++**<br />
``` C++
public value class ProcessStartupInfo
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ProcessStartupInfo =  struct end
```

The ProcessStartupInfo type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo__ctor">ProcessStartupInfo</a></td><td>
Initializes a new instance of the ProcessStartupInfo structure.</td></tr></table>&nbsp;
<a href="#processstartupinfo-structure">Back to Top</a>

## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_CountCharsX">CountCharsX</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseCountChars</a>, if a new console window is created in a console process, this member specifies the screen buffer width, in character columns. Otherwise, this member is ignored..</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_CountCharsY">CountCharsY</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseCountChars</a>, if a new console window is created in a console process, this member specifies the screen buffer height, in character rows. Otherwise, this member is ignored..</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Desktop">Desktop</a></td><td>
The name of the desktop, or the name of both the desktop and window station for this process. 

 A backslash in the string indicates that the string includes both the desktop and window station names.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_FillAttribute">FillAttribute</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseFillAttribute</a>, this member is the initial text and background colors if a new console window is created in a console application. Otherwise, this member is ignored.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a></td><td>
A bitfield that determines whether certain ProcessStartupInfo members are used when the process creates a window.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_PositionX">PositionX</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">usePosition</a>, this member is the x offset of the upper left corner of a window if a new window is created, in pixels. Otherwise, this member is ignored. 

 The offset is from the upper left corner of the screen. For GUI processes, the specified position is used the first time the new process calls CreateWindow to create an overlapped window if the x parameter of CreateWindow is CW_USEDEFAULT.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_PositionY">PositionY</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">usePosition</a>, this member is the y offset of the upper left corner of a window if a new window is created, in pixels. Otherwise, this member is ignored. 

 The offset is from the upper left corner of the screen. For GUI processes, the specified position is used the first time the new process calls CreateWindow to create an overlapped window if the y parameter of CreateWindow is CW_USEDEFAULT.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Reserved">Reserved</a></td><td>
Reserved; must be NULL.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Reserved2">Reserved2</a></td><td>
Reserved for use by the C Run-time; must be zero.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Reserved3">Reserved3</a></td><td>
Reserved for use by the C Run-time; must be NULL.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_ShowWindow">ShowWindow</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseShowWindow</a>, this member can be any of the values that can be specified in the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">NativeWindowState</a> enumeration, except for <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">ShowDefault</a>. Otherwise, this member is ignored. 

 For GUI processes, the first time ShowWindow is called, its nCmdShow parameter is ignored <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_ShowWindow">ShowWindow</a> specifies the default value. In subsequent calls to <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow(IntPtr, NativeWindowState)</a>, the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_ShowWindow">ShowWindow</a> member is used if the nCmdShow parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_ShowWindow">ShowWindow(IntPtr, NativeWindowState)</a> is set to <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_NativeWindowState">ShowDefault</a>.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_SizeOfStruct">SizeOfStruct</a></td><td>
The size of the structure, in bytes. 

 This member must be set to `Marshal.SizeOf(Of AppbarData)` before calling any function.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_SizeX">SizeX</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseSize</a>, this member is the width of the window if a new window is created, in pixels. Otherwise, this member is ignored. 

 For GUI processes, this is used only the first time the new process calls CreateWindow to create an overlapped window if the nWidth parameter of CreateWindow is CW_USEDEFAULT.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_SizeY">SizeY</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseSize</a>, this member is the height of the window if a new window is created, in pixels. Otherwise, this member is ignored.. 

 For GUI processes, this is used only the first time the new process calls CreateWindow to create an overlapped window if the nHeight parameter of CreateWindow is CW_USEDEFAULT.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdError">StdError</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a>, this member is the standard error handle for the process. Otherwise, this member is ignored and the default for standard error is the console window's buffer.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdInput">StdInput</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a>, this member is the standard input handle for the process. 

 If <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a> is not specified, the default for standard input is the keyboard buffer. 

 If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseHotkey</a>, this member specifies a hotkey value that is sent as the wParam parameter of a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_SetHotkey</a> message to the first eligible top-level window created by the application that owns the process. If the window is created with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStyles">Popup</a> window style, it is not eligible unless the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowStylesEx">AppWindow</a> extended window style is also set.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_StdOutput">StdOutput</a></td><td>
If <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Flags">Flags</a> specifies <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ProcessStartupInfoFlags">UseStdHandles</a>, this member is the standard output handle for the process. Otherwise, this member is ignored and the default for standard output is the console window's buffer. 

 If a process is launched from the taskbar or jump list, the system sets hStdOutput to a handle to the monitor that contains the taskbar or jump list used to launch the process.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_ProcessStartupInfo_Title">Title</a></td><td>
For console processes, this is the title displayed in the title bar if a new console window is created. 

 If NULL, the name of the executable file is used as the window title instead. 

 This parameter must be NULL for GUI or console processes that do not create a new console window.</td></tr></table>&nbsp;
<a href="#processstartupinfo-structure">Back to Top</a>

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
<a href="#processstartupinfo-structure">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/ns-processthreadsapi-_startupinfoa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/ns-processthreadsapi-_startupinfoa</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />