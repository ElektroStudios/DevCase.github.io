# GraphicalUtil.EnableDoubleBufferedOnControl(*T*) Method 
 

Enables double buffering on the specified control. 

 Double buffering indicates whether a control should redraw its surface using a secondary buffer to reduce or prevent flicker.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void EnableDoubleBufferedOnControl<T>(
	T ctrl
)
where T : Control

```

**VB**<br />
``` VB
Public Shared Sub EnableDoubleBufferedOnControl(Of T As Control) ( 
	ctrl As T
)
```

**VB Usage**<br />
``` VB Usage
Dim ctrl As T

GraphicalUtil.EnableDoubleBufferedOnControl(ctrl)
```

**C++**<br />
``` C++
public:
generic<typename T>
where T : Control
static void EnableDoubleBufferedOnControl(
	T ctrl
)
```

**F#**<br />
``` F#
static member EnableDoubleBufferedOnControl : 
        ctrl : 'T -> unit  when 'T : Control

```


#### Parameters
&nbsp;<dl><dt>ctrl</dt><dd>Type: *T*<br />The control.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the control.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />