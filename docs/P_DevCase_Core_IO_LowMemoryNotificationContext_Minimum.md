# LowMemoryNotificationContext.Minimum Property 
 

Gets or sets the minimum required memory, in bytes. 

 If the total amount of free physical memory for the computer is lower than this value, the Action specified in <a href="P_DevCase_Core_IO_LowMemoryNotificationContext_Action">Action</a> will be invoked once.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ulong Minimum { get; set; }
```

**VB**<br />
``` VB
Public Property Minimum As ULong
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As LowMemoryNotificationContext
Dim value As ULong

value = instance.Minimum

instance.Minimum = value
```

**C++**<br />
``` C++
public:
property unsigned long long Minimum {
	unsigned long long get ();
	void set (unsigned long long value);
}
```

**F#**<br />
``` F#
member Minimum : uint64 with get, set

```


#### Property Value
Type: UInt64<br />\[Missing <value> documentation for "P:DevCase.Core.IO.LowMemoryNotificationContext.Minimum"\]

## See Also


#### Reference
<a href="T_DevCase_Core_IO_LowMemoryNotificationContext">LowMemoryNotificationContext Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />