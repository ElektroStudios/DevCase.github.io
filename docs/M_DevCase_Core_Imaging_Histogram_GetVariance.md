# Histogram.GetVariance Method 
 

Gets the variance between two different <a href="T_DevCase_Core_Imaging_Histogram">Histogram</a> as a percentage of the maximum possible variance: 256 (for a white image compared to a black image).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual float GetVariance(
	Histogram histogram
)
```

**VB**<br />
``` VB
Public Overridable Function GetVariance ( 
	histogram As Histogram
) As Single
```

**VB Usage**<br />
``` VB Usage
Dim instance As Histogram
Dim histogram As Histogram
Dim returnValue As Single

returnValue = instance.GetVariance(histogram)
```

**C++**<br />
``` C++
public:
virtual float GetVariance(
	Histogram^ histogram
)
```

**F#**<br />
``` F#
abstract GetVariance : 
        histogram : Histogram -> float32 
override GetVariance : 
        histogram : Histogram -> float32 
```


#### Parameters
&nbsp;<dl><dt>histogram</dt><dd>Type: <a href="T_DevCase_Core_Imaging_Histogram">DevCase.Core.Imaging.Histogram</a><br />Another <a href="T_DevCase_Core_Imaging_Histogram">Histogram</a> to compare with this <a href="T_DevCase_Core_Imaging_Histogram">Histogram</a>.</dd></dl>

#### Return Value
Type: Single<br />A percentage value indicating how different the two <a href="T_DevCase_Core_Imaging_Histogram">Histogram</a> are.

## Remarks
<a href="http://en.wikipedia.org/wiki/Variance" target="_blank">http://en.wikipedia.org/wiki/Variance</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Imaging_Histogram">Histogram Class</a><br /><a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />