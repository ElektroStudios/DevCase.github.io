# GIF.EndOfFrames Property 
 

Gets a value indicating whether the frame count is at EOF, this means there is no more frames to advance in the GIF image.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool EndOfFrames { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property EndOfFrames As Boolean
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As GIF
Dim value As Boolean

value = instance.EndOfFrames

```

**C++**<br />
``` C++
public:
property bool EndOfFrames {
	bool get ();
}
```

**F#**<br />
``` F#
member EndOfFrames : bool with get

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if there is no more frames to advance in the GIF image; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_GIF">GIF Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />