# StereoVolume Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Multimedia_StereoVolume">StereoVolume</a> structure.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public StereoVolume(
	int leftChannelVolume,
	int rightChannelVolume
)
```

**VB**<br />
``` VB
Public Sub New ( 
	leftChannelVolume As Integer,
	rightChannelVolume As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim leftChannelVolume As Integer
Dim rightChannelVolume As Integer

Dim instance As New StereoVolume(leftChannelVolume, 
	rightChannelVolume)
```

**C++**<br />
``` C++
public:
StereoVolume(
	int leftChannelVolume, 
	int rightChannelVolume
)
```

**F#**<br />
``` F#
new : 
        leftChannelVolume : int * 
        rightChannelVolume : int -> StereoVolume
```


#### Parameters
&nbsp;<dl><dt>leftChannelVolume</dt><dd>Type: System.Int32<br />The left channel valume, from range 0 to 100.</dd><dt>rightChannelVolume</dt><dd>Type: System.Int32<br />The right channel valume, from range 0 to 100.</dd></dl>

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentOutOfRangeException</td><td>leftChannelVolume;A value between 0 and 100 is required. or rightChannelVolume;A value between 0 and 100 is required.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_StereoVolume">StereoVolume Structure</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />