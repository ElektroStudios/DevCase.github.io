# WindowStylesEx Enumeration
 

Extended window styles.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum WindowStylesEx
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration WindowStylesEx
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowStylesEx
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class WindowStylesEx
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type WindowStylesEx
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.None">**None**</td><td>0</td><td>No style.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.AcceptFiles">**AcceptFiles**</td><td>16</td><td>Specifies a window that accepts drag-drop files.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.AppWindow">**AppWindow**</td><td>262144</td><td>Forces a top-level window onto the taskbar when the window is visible.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.ClientEdge">**ClientEdge**</td><td>512</td><td>Specifies a window that has a border with a sunken edge.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.Composited">**Composited**</td><td>33554432</td><td>Specifies a window that paints all descendants in bottom-to-top painting order using double-buffering. 

 This cannot be used if the window has a class style of either `CS_OWNDC` or `CS_CLASSDC`. 

 With Composited set, all descendants of a window get bottom-to-top painting order using double-buffering. 

 Bottom-to-top painting order allows a descendent window to have translucency (alpha) and transparency (color-key) effects, but only if the descendent window also has theTransparent bit set. 

 Double-buffering allows the window and its descendents to be painted without flicker.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.ContextHelp">**ContextHelp**</td><td>1024</td><td>Specifies a window that includes a question mark in the title bar. 

 When the user clicks the question mark, the cursor changes to a question mark with a pointer. 

 If the user then clicks a child window, the child receives a `WM_HELP` message. 

 The child window should pass the message to the parent window procedure, which should call the `WinHelp` function using the `HELP_WM_HELP` command. 

 The Help application displays a pop-up window that typically contains help for the child window. 

ContextHelp cannot be used with the `WS_MAXIMIZEBOX` or `WS_MINIMIZEBOX` styles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.ControlParent">**ControlParent**</td><td>65536</td><td>Specifies a window which contains child windows that should take part in dialog box navigation. 

 If this style is specified, the dialog manager recurses into children of this window when performing navigation operations such as handling the `TAB` key, an arrow key, or a keyboard mnemonic.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.DlgModalFrame">**DlgModalFrame**</td><td>1</td><td>Specifies a window that has a double border.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.Layered">**Layered**</td><td>524288</td><td>Specifies a window that is a layered window. 

 This cannot be used for child windows or if the window has a class style of either `CS_OWNDC` or `CS_CLASSDC`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.LayoutRtl">**LayoutRtl**</td><td>4194304</td><td>Specifies a window with the horizontal origin on the right edge. 

 Increasing horizontal values advance to the left. 

 The shell language must support reading-order alignment for this to take effect.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.Left">**Left**</td><td>0</td><td>Specifies a window that has generic left-aligned properties. 

 This is the default.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.LeftScrollbar">**LeftScrollbar**</td><td>16384</td><td>Specifies a window with the vertical scroll bar (if present) to the left of the client area. 

 The shell language must support reading-order alignment for this to take effect.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.LtrReading">**LtrReading**</td><td>0</td><td>Specifies a window that displays text using left-to-right reading-order properties. 

 This is the default.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.MdiChild">**MdiChild**</td><td>64</td><td>Specifies a multiple-document interface (MDI) child window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.NoActivate">**NoActivate**</td><td>134217728</td><td>Specifies a top-level window created with this style does not become the foreground window when the user clicks it. 

 The system does not bring this window to the foreground when the user minimizes or closes the foreground window. 

 The window does not appear on the taskbar by default. 

 To force the window to appear on the taskbar, use the AppWindow style. 

 To activate the window, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetActiveWindow">SetActiveWindow(IntPtr)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetForegroundWindow">SetForegroundWindow(IntPtr)</a> function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.NoInheritLayout">**NoInheritLayout**</td><td>1048576</td><td>Specifies a window which does not pass its window layout to its child windows.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.NoParentNotify">**NoParentNotify**</td><td>4</td><td>Specifies that a child window created with this style does not send the `WM_PARENTNOTIFY` message to its parent window when it is created or destroyed.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.OverlappedWindow">**OverlappedWindow**</td><td>768</td><td>Specifies an overlapped window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.PaletteWindow">**PaletteWindow**</td><td>392</td><td>Specifies a palette window, which is a modeless dialog box that presents an array of commands.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.Right">**Right**</td><td>4096</td><td>Specifies a window that has generic "right-aligned" properties. This depends on the window class. 

 The shell language must support reading-order alignment for this to take effect. 

 Using the Right style has the same effect as using the `SS_RIGHT` (static), `ES_RIGHT` (edit), and `BS_RIGHT`/`BS_RIGHTBUTTON` (button) control styles.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.RightScrollbar">**RightScrollbar**</td><td>0</td><td>Specifies a window with the vertical scroll bar (if present) to the right of the client area. 

 This is the default.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.RtlReading">**RtlReading**</td><td>8192</td><td>Specifies a window that displays text using right-to-left reading-order properties. 

 The shell language must support reading-order alignment for this to take effect.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.StaticEdge">**StaticEdge**</td><td>131072</td><td>Specifies a window with a three-dimensional border style intended to be used for items that do not accept user input.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.ToolWindow">**ToolWindow**</td><td>128</td><td>Specifies a window that is intended to be used as a floating toolbar. 

 A tool window has a title bar that is shorter than a normal title bar, and the window title is drawn using a smaller font. 

 A tool window does not appear in the taskbar or in the dialog that appears when the user presses `ALT`+`TAB`. 

 If a tool window has a system menu, its icon is not displayed on the title bar. 

 However, you can display the system menu by right-clicking or by typing `ALT`+`SPACE`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.TopMost">**TopMost**</td><td>8</td><td>Specifies a window that should be placed above all non-topmost windows and should stay above them, even when the window is deactivated. 

 To add or remove this style, use the `SetWindowPos` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.Transparent">**Transparent**</td><td>32</td><td>Specifies a window that should not be painted until siblings beneath the window (that were created by the same thread) have been painted. 

 The window appears transparent because the bits of underlying sibling windows have already been painted. 

 To achieve transparency without these restrictions, use the `SetWindowRgn` function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.WindowStylesEx.WindowEdge">**WindowEdge**</td><td>256</td><td>Specifies a window that has a border with a raised edge.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/ff700543%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/ff700543%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />