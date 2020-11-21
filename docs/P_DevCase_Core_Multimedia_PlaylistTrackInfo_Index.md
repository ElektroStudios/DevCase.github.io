# PlaylistTrackInfo.Index Property 
 

Gets the track index. 

 Don't set this value manually. 

 This value is automatically set by some of the <a href="T_DevCase_Core_Multimedia_PlaylistEditor">PlaylistEditor</a> methods, and has any effect for other purposes.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Index { get; set; }
```

**VB**<br />
``` VB
Public Property Index As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As PlaylistTrackInfo
Dim value As Integer

value = instance.Index

instance.Index = value
```

**C++**<br />
``` C++
public:
property int Index {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
member Index : int with get, set

```


#### Property Value
Type: Int32<br />The track index.

## See Also


#### Reference
<a href="T_DevCase_Core_Multimedia_PlaylistTrackInfo">PlaylistTrackInfo Class</a><br /><a href="N_DevCase_Core_Multimedia">DevCase.Core.Multimedia Namespace</a><br />