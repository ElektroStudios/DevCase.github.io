# NativeWindowState Enumeration
 

Controls how a window is to be shown.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum NativeWindowState
```

**VB**<br />
``` VB
Public Enumeration NativeWindowState
```

**VB Usage**<br />
``` VB Usage
Dim instance As NativeWindowState
```

**C++**<br />
``` C++
public enum class NativeWindowState
```

**F#**<br />
``` F#
type NativeWindowState
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.Hide">**Hide**</td><td>0</td><td>Hides the window and activates another window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.Normal">**Normal**</td><td>1</td><td>Activates and displays a window. If the window is minimized or maximized, the system restores it to its original size and position. An application should specify this flag when displaying the window for the first time.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ShowMinimized">**ShowMinimized**</td><td>2</td><td>Activates the window and displays it as a minimized window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.Maximize">**Maximize**</td><td>3</td><td>Maximizes the specified window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ShowMaximized">**ShowMaximized**</td><td>3</td><td>Activates the window and displays it as a maximized window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ShowNoActivate">**ShowNoActivate**</td><td>4</td><td>Displays a window in its most recent size and position. This value is similar to Normal, except the window is not actived.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.Show">**Show**</td><td>5</td><td>Activates the window and displays it in its current size and position.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.Minimize">**Minimize**</td><td>6</td><td>Minimizes the specified window and activates the next top-level window in the Z order.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ShowMinNoActive">**ShowMinNoActive**</td><td>7</td><td>Displays the window as a minimized window. This value is similar to ShowMinimized, except the window is not activated.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ShowNA">**ShowNA**</td><td>8</td><td>Displays the window in its current size and position. This value is similar to Show, except the window is not activated.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.Restore">**Restore**</td><td>9</td><td>Activates and displays the window. If the window is minimized or maximized, the system restores it to its original size and position. An application should specify this flag when restoring a minimized window.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ShowDefault">**ShowDefault**</td><td>10</td><td>Sets the show state based on the SW_* value specified in the `STARTUPINFO` structure passed to the `CreateProcess` function by the program that started the application.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.NativeWindowState.ForceMinimize">**ForceMinimize**</td><td>11</td><td><b>Windows 2000/XP:</b> Minimizes a window, even if the thread that owns the window is not responding. This flag should only be used when minimizing windows from a different thread.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633548%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633548%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />