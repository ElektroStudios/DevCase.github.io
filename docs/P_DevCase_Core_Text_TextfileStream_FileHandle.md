# TextfileStream.FileHandle Property 
 

Gets a SafeFileHandle object that represents the operating system file handle of the textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual SafeFileHandle FileHandle { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property FileHandle As SafeFileHandle
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextfileStream
Dim value As SafeFileHandle

value = instance.FileHandle

```

**C++**<br />
``` C++
public:
virtual property SafeFileHandle^ FileHandle {
	SafeFileHandle^ get ();
}
```

**F#**<br />
``` F#
abstract FileHandle : SafeFileHandle with get
override FileHandle : SafeFileHandle with get
```


#### Property Value
Type: SafeFileHandle<br />A SafeFileHandle object that represents the operating system file handle of the textfile.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TextfileStream">TextfileStream Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />