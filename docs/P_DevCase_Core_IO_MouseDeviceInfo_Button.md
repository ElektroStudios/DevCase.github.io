# MouseDeviceInfo.Button Property 
 

Gets the mouse button.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public RawMouseButtons Button { get; set; }
```

**VB**<br />
``` VB
Public Property Button As RawMouseButtons
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseDeviceInfo
Dim value As RawMouseButtons

value = instance.Button

instance.Button = value
```

**C++**<br />
``` C++
public:
property RawMouseButtons Button {
	RawMouseButtons get ();
	void set (RawMouseButtons value);
}
```

**F#**<br />
``` F#
member Button : RawMouseButtons with get, set

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RawMouseButtons">RawMouseButtons</a><br />The mouse button.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseDeviceInfo">MouseDeviceInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />