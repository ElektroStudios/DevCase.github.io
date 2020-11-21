# SetWindowPosFlags Enumeration
 

The window sizing and positioning flags. 

 Flags combination for `uFlags` parameter of <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetWindowPos">SetWindowPos(IntPtr, IntPtr, Int32, Int32, Int32, Int32, SetWindowPosFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SetWindowPosFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SetWindowPosFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As SetWindowPosFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SetWindowPosFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SetWindowPosFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.None">**None**</td><td>0</td><td>Indicates any flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.AsyncWindowPos">**AsyncWindowPos**</td><td>16384</td><td>If the calling thread and the thread that owns the window are attached to different input queues, the system posts the request to the thread that owns the window. 

 This prevents the calling thread from blocking its execution while other threads process the request.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DeferErase">**DeferErase**</td><td>8192</td><td>Prevents generation of the `WM_SYNCPAINT` message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DrawFrame">**DrawFrame**</td><td>32</td><td>Draws a frame (defined in the window's class description) around the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.FrameChanged">**FrameChanged**</td><td>32</td><td>Applies new frame styles set using the SetWindowLong function. 

 Sends a `WM_NCCALCSIZE` message to the window, even if the window's size is not being changed. 

 If this flag is not specified, `WM_NCCALCSIZE` is sent only when the window's size is being changed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.HideWindow">**HideWindow**</td><td>128</td><td>Hides the window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DontActivate">**DontActivate**</td><td>16</td><td>Does not activate the window. If this flag is not set, the window is activated and moved to the top of either the topmost or non-topmost group (depending on the setting of the hWndInsertAfter parameter).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DontCopyBits">**DontCopyBits**</td><td>256</td><td>Discards the entire contents of the client area. 

 If this flag is not specified, the valid contents of the client area are saved and copied back into the client area after the window is sized or repositioned.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.IgnoreMove">**IgnoreMove**</td><td>2</td><td>Retains the current position (ignores X and Y parameters).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DontChangeOwnerZOrder">**DontChangeOwnerZOrder**</td><td>512</td><td>Does not change the owner window's position in the Z order.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DontRedraw">**DontRedraw**</td><td>8</td><td>Does not redraw changes. 

 If this flag is set, no repainting of any kind occurs. 

 This applies to the client area, the nonclient area (including the title bar and scroll bars), and any part of the parent window uncovered as a result of the window being moved. 

 When this flag is set, the application must explicitly invalidate or redraw any parts of the window and parent window that need redrawing.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DontReposition">**DontReposition**</td><td>512</td><td>Same as the DontChangeOwnerZOrder flag.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.DontSendChangingEvent">**DontSendChangingEvent**</td><td>1024</td><td>Prevents the window from receiving the `WM_WINDOWPOSCHANGING` message.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.IgnoreResize">**IgnoreResize**</td><td>1</td><td>Retains the current size (ignores the cx and cy parameters).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.IgnoreZOrder">**IgnoreZOrder**</td><td>4</td><td>Retains the current Z order (ignores the `hwndInsertAfter` parameter).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SetWindowPosFlags.ShowWindow">**ShowWindow**</td><td>64</td><td>Displays the window.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ms633545%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ms633545%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />