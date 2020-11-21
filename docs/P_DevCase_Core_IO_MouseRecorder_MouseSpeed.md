# MouseRecorder.MouseSpeed Property 
 

Gets or sets the speed of recording/playing the mouse actions. 

 Default value is `30`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int MouseSpeed { get; set; }
```

**VB**<br />
``` VB
Public Property MouseSpeed As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseRecorder
Dim value As Integer

value = instance.MouseSpeed

instance.MouseSpeed = value
```

**C++**<br />
``` C++
public:
property int MouseSpeed {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member MouseSpeed : int with get, set

```


#### Property Value
Type: Int32<br />The mouse speed.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_MouseRecorder">MouseRecorder Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />