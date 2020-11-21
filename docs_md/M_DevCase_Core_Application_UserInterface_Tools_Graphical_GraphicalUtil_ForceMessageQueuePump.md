# GraphicalUtil.ForceMessageQueuePump Method 
 

This method allows the current thread to perform long-running operations while continuing to perform standard COM and SendMessage pumping. 

 Calling this method during a long-running operation will prevent the Managed Debugging Assistant (MDA) 'ContextSwitchDeadlock' error to occur while debugging your solution. 

 This error may occur when the thread that owns the destination context/apartment is processing a very long-running operation without pumping Windows messages for a specific period of time. 

 For example, you will use this method while performing a long-running operation with COM objects (eg. inside a "infinite" loop) that is blocking the UI thread, 

 so it is unabling the UI thread to pump window messages as they arrive, causing the 'ContextSwitchDeadlock' error to occur in the Visual Studio debugger after 60 seconds.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void ForceMessageQueuePump()
```

**VB**<br />
``` VB
Public Shared Sub ForceMessageQueuePump
```

**VB Usage**<br />
``` VB Usage

GraphicalUtil.ForceMessageQueuePump()
```

**C++**<br />
``` C++
public:
static void ForceMessageQueuePump()
```

**F#**<br />
``` F#
static member ForceMessageQueuePump : unit -> unit 

```


## Examples
This is a code example. 
**VB**<br />
``` VB
Do While True
    ' Intensive work here...

    ForceMessageQueuePump()
Loop
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />