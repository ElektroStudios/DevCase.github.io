# TextfileStream.FileStream Property 
 

Gets the FileStream instance that exposes a Stream around the textfile.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual FileStream FileStream { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property FileStream As FileStream
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As TextfileStream
Dim value As FileStream

value = instance.FileStream

```

**C++**<br />
``` C++
public:
virtual property FileStream^ FileStream {
	FileStream^ get ();
}
```

**F#**<br />
``` F#
abstract FileStream : FileStream with get
override FileStream : FileStream with get
```


#### Property Value
Type: FileStream<br />The FileStream instance.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_TextfileStream">TextfileStream Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />