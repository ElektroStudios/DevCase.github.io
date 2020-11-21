# HookType Enumeration
 

Specifies a type of hook procedure to be installed. 

`hookType` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowsHookEx">SetWindowsHookEx(HookType, Delegates.HookProc, IntPtr, UInt32)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum HookType
```

**VB**<br />
``` VB
Public Enumeration HookType
```

**VB Usage**<br />
``` VB Usage
Dim instance As HookType
```

**C++**<br />
``` C++
public enum class HookType
```

**F#**<br />
``` F#
type HookType
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.MsgFilter">**MsgFilter**</td><td>-1</td><td>Installs a hook procedure that monitors messages generated as a result of an input event in a dialog box, message box, menu, or scroll bar. 

 For more information, see the `MessageProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644987(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644987(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.JournalRecord">**JournalRecord**</td><td>0</td><td>Installs a hook procedure that records input messages posted to the system message queue. 

 This hook is useful for recording macros. 

 For more information, see the `JournalRecordProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644983(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644983(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.JournalPlayback">**JournalPlayback**</td><td>1</td><td>Installs a hook procedure that posts messages previously recorded by a `WH_JOURNALRECORD` hook procedure. 

 For more information, see the `JournalPlaybackProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644982(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644982(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.Keyboard">**Keyboard**</td><td>2</td><td>Installs a hook procedure that monitors keystroke messages. 

 For more information, see the `KeyboardProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644984(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644984(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.GetMessage">**GetMessage**</td><td>3</td><td>Installs a hook procedure that monitors messages posted to a message queue. 

 For more information, see the `GetMsgProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644981(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644981(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.CallWndProc">**CallWndProc**</td><td>4</td><td>Installs a hook procedure that monitors messages before the system sends them to the destination window procedure. 

 For more information, see the `CallWndProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644975(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644975(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.Cbt">**Cbt**</td><td>5</td><td>Installs a hook procedure that receives notifications useful to a `CBT` application. 

 For more information, see the `CBTProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644977(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644977(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.SysMsgFilter">**SysMsgFilter**</td><td>6</td><td>Installs a hook procedure that monitors messages generated as a result of an input event in a dialog box, message box, menu, or scroll bar. 

 The hook procedure monitors these messages for all applications in the same desktop as the calling thread. 

 For more information, see the `SysMsgProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644992(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644992(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.Mouse">**Mouse**</td><td>7</td><td>Installs a hook procedure that monitors mouse messages. 

 For more information, see the `MouseProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644988(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644988(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.Hardware">**Hardware**</td><td>8</td><td>Hoot type not documented.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.Debug">**Debug**</td><td>9</td><td>Installs a hook procedure useful for debugging other hook procedures. 

 For more information, see the `DebugProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644978(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644978(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.Shell">**Shell**</td><td>10</td><td>Installs a hook procedure that receives notifications useful to shell applications. 

 For more information, see the `ShellProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644991(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644991(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.ForegroundIdle">**ForegroundIdle**</td><td>11</td><td>Installs a hook procedure that will be called when the application's foreground thread is about to become idle. 

 This hook is useful for performing low priority tasks during idle time. 

 For more information, see the `ForegroundIdleProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644980(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644980(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.CallWndProcRet">**CallWndProcRet**</td><td>12</td><td>Installs a hook procedure that monitors messages after they have been processed by the destination window procedure. 

 For more information, see the `CallWndRetProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644976(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644976(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.KeyboardLL">**KeyboardLL**</td><td>13</td><td>Installs a hook procedure that monitors low-level keyboard input events. 

 For more information, see the `LowLevelKeyboardProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644985(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644985(v=vs.85).aspx</a></td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.HookType.MouseLL">**MouseLL**</td><td>14</td><td>Installs a hook procedure that monitors low-level mouse input events. 

 For more information, see the `LowLevelMouseProc` hook procedure: <a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644986(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644986(v=vs.85).aspx</a></td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms644990%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms644990%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />