# PowerUtil.SendAwakeSignal Method 
 

Sends an Awake signal to prevent the system from turning off the display and entering into Sleep or Hibernation modes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool SendAwakeSignal()
```

**VB**<br />
``` VB
Public Shared Function SendAwakeSignal As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean

returnValue = PowerUtil.SendAwakeSignal()
```

**C++**<br />
``` C++
public:
static bool SendAwakeSignal()
```

**F#**<br />
``` F#
static member SendAwakeSignal : unit -> bool 

```


#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## Remarks
The Awake signal should be sent periodically.

## Examples
This is a code example that keeps the operating system active to avoid entering into IDLE state. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Private WithEvents awakeTimer As Threading.Timer
    Private ReadOnly awakeInterval As Integer = 30000 'ms

    Public Sub New()

        Me.InitializeComponent()
        Me.awakeTimer = New Threading.Timer(AddressOf Me.AwakeTimer_Callback, Nothing, Me.awakeInterval, 0)

    End Sub

    Private Sub AwakeTimer_Callback(ByVal stateInfo As Object)

        ' Send periodically an Awake signal to avoid the system entering into Sleep or Hibernation mode.
        PowerUtil.SendAwakeSignal()

        If (Me.awakeTimer IsNot Nothing) Then
            Me.awakeTimer.Change(Me.awakeInterval, 0)
        End If

    End Sub

    Private Sub Form1_FormClosing(sender As Object, e As FormClosingEventArgs) _
    Handles MyBase.FormClosing

        Me.awakeTimer.Dispose()
        Me.awakeTimer = Nothing
        PowerUtil.RemovedAwakeSignal()

    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_PowerUtil">PowerUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />