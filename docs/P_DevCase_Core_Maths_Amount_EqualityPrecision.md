# Amount.EqualityPrecision Property 
 

Gets or sets a value indicating the decimal precision to which two amounts are considered equal.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static int EqualityPrecision { get; set; }
```

**VB**<br />
``` VB
Public Shared Property EqualityPrecision As Integer
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim value As Integer

value = Amount.EqualityPrecision

Amount.EqualityPrecision = value
```

**C++**<br />
``` C++
public:
static property int EqualityPrecision {
	int get ();
	void set (int value);
}
```

**F#**<br />
``` F#
static member EqualityPrecision : int with get, set

```


#### Property Value
Type: Int32<br />A value indicating the decimal precision to which two amounts are considered equal.

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />