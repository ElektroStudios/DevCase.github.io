# DriveWatcher.Drives Property 
 

Gets the connected drives on this computer.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IEnumerable<DriveInfo> Drives { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Drives As IEnumerable(Of DriveInfo)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveWatcher
Dim value As IEnumerable(Of DriveInfo)

value = instance.Drives

```

**C++**<br />
``` C++
public:
virtual property IEnumerable<DriveInfo^>^ Drives {
	IEnumerable<DriveInfo^>^ get ();
}
```

**F#**<br />
``` F#
abstract Drives : IEnumerable<DriveInfo> with get
override Drives : IEnumerable<DriveInfo> with get
```


#### Property Value
Type: IEnumerable(DriveInfo)<br />\[Missing <value> documentation for "P:DevCase.Core.IO.DriveWatcher.Drives"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_DriveWatcher">DriveWatcher Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />