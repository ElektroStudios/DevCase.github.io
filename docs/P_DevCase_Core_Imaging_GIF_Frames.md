# GIF.Frames Property 
 

Gets the frame at the specified index.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Bitmap this[
	int index
] { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Frames ( 
	index As Integer
) As Bitmap
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As GIF
Dim index As Integer
Dim value As Bitmap

value = instance.Frames(index)

```

**C++**<br />
``` C++
public:
virtual property Bitmap^ Frames[int index] {
	Bitmap^ get (int index);
}
```

**F#**<br />
``` F#
abstract Frames : Bitmap with get
override Frames : Bitmap with get
```


#### Parameters
&nbsp;<dl><dt>index</dt><dd>Type: System.Int32<br /></dd></dl>

#### Property Value
Type: Bitmap<br />The frame index.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_GIF">GIF Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />