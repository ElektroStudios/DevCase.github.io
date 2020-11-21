# UIAutomationUtil.GetToolbarButtons Method 
 

Gets the buttons of a Toolbar control (a window with "ToolbarWin32" class name).

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<NativeToolBarButton> GetToolbarButtons(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
Public Shared Function GetToolbarButtons ( 
	hWnd As IntPtr
) As ReadOnlyCollection(Of NativeToolBarButton)
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As ReadOnlyCollection(Of NativeToolBarButton)

returnValue = UIAutomationUtil.GetToolbarButtons(hWnd)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<NativeToolBarButton>^ GetToolbarButtons(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
static member GetToolbarButtons : 
        hWnd : IntPtr -> ReadOnlyCollection<NativeToolBarButton> 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the Toolbar control (a window with "ToolbarWin32" class name).</dd></dl>

#### Return Value
Type: ReadOnlyCollection(<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeToolBarButton">NativeToolBarButton</a>)<br />The toolbar buttons.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim hWnd As IntPtr = NotificationAreaUtil.VisibleHwnd
Dim buttons As ReadOnlyCollection(Of NativeToolBarButton) = UIAutomationUtil.GetToolbarButtons(hWnd)

For Each ntb As NativeToolBarButton In buttons
    Dim sb As New StringBuilder()
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.ProcessId), ntb.ProcessId))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.ImageListHandle), ntb.ImageListHandle.ToString()))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.ButtonIndex), ntb.ButtonIndex))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.BitmapIndex), ntb.BitmapIndex))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.CommandId), ntb.CommandId))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.State), ntb.State.ToString()))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.Style), ntb.Style.ToString()))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.ToolTipText), ntb.ToolTipText))
    sb.AppendLine(String.Format("{0}: {1}", NameOf(ntb.Bounds), ntb.Bounds.ToString()))

    Console.WriteLine(sb.ToString())
Next ntb
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_UIAutomationUtil">UIAutomationUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />