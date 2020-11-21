# AudioPlayer.Handle Property 
 

Gets the handle for the NativeWindow that owns this <a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer</a> instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IntPtr Handle { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Handle As IntPtr
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As AudioPlayer
Dim value As IntPtr

value = instance.Handle

```

**C++**<br />
``` C++
public:
virtual property IntPtr Handle {
	IntPtr get ();
}
```

**F#**<br />
``` F#
abstract Handle : IntPtr with get
override Handle : IntPtr with get
```


#### Property Value
Type: IntPtr<br />The handle.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_AudioPlayer">AudioPlayer Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />