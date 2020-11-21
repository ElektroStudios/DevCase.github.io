# DiskStress.Filesize Property 
 

Gets the size of the files being read and written.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int Filesize { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property Filesize As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DiskStress
Dim value As Integer

value = instance.Filesize

```

**C++**<br />
``` C++
public:
property int Filesize {
	int get ();
}
```

**F#**<br />
``` F#
member Filesize : int with get

```


#### Property Value
Type: Int32<br />The size of the files being read and written.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DiskStress">DiskStress Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />