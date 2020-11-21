# Histogram.Visualize Method 
 

Gets a Bitmap with the RGB histograms.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Bitmap Visualize()
```

**VB**<br />
``` VB
Public Overridable Function Visualize As Bitmap
```

**VB Usage**<br />
``` VB Usage
Dim instance As Histogram
Dim returnValue As Bitmap

returnValue = instance.Visualize()
```

**C++**<br />
``` C++
public:
virtual Bitmap^ Visualize()
```

**F#**<br />
``` F#
abstract Visualize : unit -> Bitmap 
override Visualize : unit -> Bitmap 
```


#### Return Value
Type: Bitmap<br />Returns three histograms for Red, Green and Blue values in the <a href="T_DevCase_Core_Imaging_Histogram">Histogram</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Histogram">Histogram Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />