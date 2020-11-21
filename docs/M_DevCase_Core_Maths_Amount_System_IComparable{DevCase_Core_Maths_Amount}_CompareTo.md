# Amount.IComparable(Amount).CompareTo Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
int IComparable<Amount>.CompareTo(
	Amount otherAmount
)
```

**VB**<br />
``` VB
Private Function IComparable_CompareTo ( 
	otherAmount As Amount
) As Integer Implements IComparable(Of Amount).CompareTo
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim otherAmount As Amount
Dim returnValue As Integer

returnValue = CType(instance, IComparable(Of Amount)).CompareTo(otherAmount)
```

**C++**<br />
``` C++
private:
virtual int IComparable_CompareTo(
	Amount^ otherAmount
) sealed = IComparable<Amount^>::CompareTo
```

**F#**<br />
``` F#
private abstract IComparable_CompareTo : 
        otherAmount : Amount -> int 
private override IComparable_CompareTo : 
        otherAmount : Amount -> int 
```


#### Parameters
&nbsp;<dl><dt>otherAmount</dt><dd>Type: <a href="T_DevCase_Core_Maths_Amount">DevCase.Core.Maths.Amount</a><br />\[Missing <param name="otherAmount"/> documentation for "M:DevCase.Core.Maths.Amount.System#IComparable{DevCase#Core#Maths#Amount}#CompareTo(DevCase.Core.Maths.Amount)"\]</dd></dl>

#### Return Value
Type: Int32<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IComparable{DevCase#Core#Maths#Amount}#CompareTo(DevCase.Core.Maths.Amount)"\]

#### Implements
IComparable(T).CompareTo(T)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />