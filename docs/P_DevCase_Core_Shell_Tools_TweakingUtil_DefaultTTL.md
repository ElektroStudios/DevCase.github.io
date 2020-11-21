# TweakingUtil.DefaultTTL Property 
 

Gets or sets a value that specifies the default Time to Live (TTL) value in the header of outgoing IP packets. 

 The TTL determines how long an IP packet that has not reached its destination can remain on the network before it is discarded.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte DefaultTTL { get; set; }
```

**VB**<br />
``` VB
Public Shared Property DefaultTTL As Byte
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Byte

value = TweakingUtil.DefaultTTL

TweakingUtil.DefaultTTL = value
```

**C++**<br />
``` C++
public:
static property unsigned char DefaultTTL {
	unsigned char get ();
	void set (unsigned char value);
}
```

**F#**<br />
``` F#
static member DefaultTTL : byte with get, set

```


#### Property Value
Type: Byte<br />The default Time to Live (TTL) value in the header of outgoing IP packets.

## Remarks
<a href="http://technet.microsoft.com/en-us/library/cc957530.aspx" target="_blank">http://technet.microsoft.com/en-us/library/cc957530.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_TweakingUtil">TweakingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />