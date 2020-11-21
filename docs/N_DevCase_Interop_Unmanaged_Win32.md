# DevCase.Interop.Unmanaged.Win32 Namespace
 




## Classes
&nbsp;<table><tr><th></th><th>Class</th><th>Description</th></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates">Delegates</a></td><td /></tr><tr><td>![Public class](media/pubclass.gif "Public class")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods</a></td><td>
Platform Invocation methods (P/Invoke), access unmanaged code. 

 This class does not suppress stack walks for unmanaged code permission. SuppressUnmanagedCodeSecurityAttribute must not be applied to this class. 

 This class is for methods that can be used anywhere because a stack walk will be performed.</td></tr></table>

## Delegates
&nbsp;<table><tr><th></th><th>Delegate</th><th>Description</th></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_ApplicationRecoveryCallback">Delegates.ApplicationRecoveryCallback</a></td><td>
Application-defined callback function used to save data and application state information in the event the application encounters an unhandled exception or becomes unresponsive.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_CopyProgressRoutine">Delegates.CopyProgressRoutine</a></td><td>
An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CopyFileEx">CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags)</a>, `MoveFileTransacted`, and `MoveFileWithProgress` functions. 

 It is called when a portion of a copy or move operation is completed. 

 The `LPPROGRESS_ROUTINE` type defines a pointer to this callback function. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_CopyProgressRoutine">Delegates.CopyProgressRoutine</a> is a placeholder for the application-defined function name.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumChildWindowsProc">Delegates.EnumChildWindowsProc</a></td><td>
An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumChildWindows">EnumChildWindows(IntPtr, Delegates.EnumChildWindowsProc, IntPtr)</a> function. 

 It receives the child window handles. 

 The `WNDENUMPROC` type defines a pointer to this callback function. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumChildWindowsProc">Delegates.EnumChildWindowsProc</a> is a placeholder for the application-defined function name.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumCodePagesProc">Delegates.EnumCodePagesProc</a></td><td>
An application-defined callback function that processes enumerated code page information provided by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumSystemCodePages">EnumSystemCodePages(Delegates.EnumCodePagesProc, EnumSystemCodePagesFlags)</a> function.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumDesktopProc">Delegates.EnumDesktopProc</a></td><td>
An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDesktops">EnumDesktops(IntPtr, Delegates.EnumDesktopProc, IntPtr)</a> function. It receives a desktop name. 

 The DESKTOPENUMPROC type defines a pointer to this callback function. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumDesktopProc">Delegates.EnumDesktopProc</a> is a placeholder for the application-defined function name.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumLocalesProc">Delegates.EnumLocalesProc</a></td><td>
An application-defined callback function that processes enumerated locale information provided by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumSystemLocales">EnumSystemLocales(Delegates.EnumLocalesProc, EnumSystemLocalesFlags)</a> function.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumMonitorProc">Delegates.EnumMonitorProc</a></td><td>
An application-defined callback function that is called by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDisplayMonitors">EnumDisplayMonitors(IntPtr, IntPtr, Delegates.EnumMonitorProc, IntPtr)</a> function.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumThreadWindowsProc">Delegates.EnumThreadWindowsProc</a></td><td>
An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumThreadWindows">EnumThreadWindows(UInt32, Delegates.EnumThreadWindowsProc, IntPtr)</a> function. 

 It receives the window handles associated with a thread. 

 The `WNDENUMPROC` type defines a pointer to this callback function. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumThreadWindowsProc">Delegates.EnumThreadWindowsProc</a> is a placeholder for the application-defined function name.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumUILanguagesProc">Delegates.EnumUILanguagesProc</a></td><td>
An application-defined callback function that processes enumerated user interface language information provided by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumUILanguages">EnumUILanguages(Delegates.EnumUILanguagesProc, MuiLanguageMode, IntPtr)</a> function.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumWindowsProc">Delegates.EnumWindowsProc</a></td><td>
An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumWindows">EnumWindows(Delegates.EnumWindowsProc, IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumDesktopWindows">EnumDesktopWindows(IntPtr, Delegates.EnumWindowsProc, IntPtr)</a> function. 

 It receives top-level window handles. 

 The `WNDENUMPROC` type defines a pointer to this callback function. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumWindowsProc">Delegates.EnumWindowsProc</a> is a placeholder for the application-defined function name.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_HookProc">Delegates.HookProc</a></td><td>
A <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_HookProc">Delegates.HookProc</a> delegate representing a hook procedure method. 

 ( for parameter `hookProc` of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowsHookEx">SetWindowsHookEx(HookType, Delegates.HookProc, IntPtr, UInt32)</a> function. )</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_MiniDumpCallbackRoutine">Delegates.MiniDumpCallbackRoutine</a></td><td>
An application-defined callback function used with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_MiniDumpWriteDump">MiniDumpWriteDump(IntPtr, Int32, SafeHandle, MiniDumpType, MiniDumpExceptionInformation, IntPtr, IntPtr)</a>. It receives extended minidump information.</td></tr><tr><td>![Public delegate](media/pubdelegate.gif "Public delegate")</td><td><a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_SymEnumSymbolsProc">Delegates.SymEnumSymbolsProc</a></td><td>
An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SymEnumSymbols">SymEnumSymbols(IntPtr, UInt64, String, Delegates.SymEnumSymbolsProc, IntPtr)</a>, `SymEnumTypes`, and `SymEnumTypesByName` functions.</td></tr></table>&nbsp;
