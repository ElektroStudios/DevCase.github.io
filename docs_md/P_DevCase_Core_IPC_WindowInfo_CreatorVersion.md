# WindowInfo.CreatorVersion Property 
 

Gets the Microsoft Windows version of the application that created the window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC">DevCase.Core.IPC</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ushort CreatorVersion { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property CreatorVersion As UShort
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As WindowInfo
Dim value As UShort

value = instance.CreatorVersion

```

**C++**<br />
``` C++
public:
property unsigned short CreatorVersion {
	unsigned short get ();
}
```

**F#**<br />
``` F#
member CreatorVersion : uint16 with get

```


#### Property Value
Type: UInt16<br />\[Missing <value> documentation for "P:DevCase.Core.IPC.WindowInfo.CreatorVersion"\]

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>Win32Exception</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_IPC_WindowInfo">WindowInfo Class</a><br /><a href="N_DevCase_Core_IPC">DevCase.Core.IPC Namespace</a><br />