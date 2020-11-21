# Amount.IConvertible.GetTypeCode Method 
 

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
TypeCodeIConvertible.GetTypeCode()
```

**VB**<br />
``` VB
Private Function IConvertible_GetTypeCode As TypeCode
	Implements IConvertible.GetTypeCode
```

**VB Usage**<br />
``` VB Usage
Dim instance As Amount
Dim returnValue As TypeCode

returnValue = CType(instance, IConvertible).GetTypeCode()
```

**C++**<br />
``` C++
private:
virtual TypeCode IConvertible_GetTypeCode() sealed = IConvertible::GetTypeCode
```

**F#**<br />
``` F#
private abstract IConvertible_GetTypeCode : unit -> TypeCode 
private override IConvertible_GetTypeCode : unit -> TypeCode 
```


#### Return Value
Type: TypeCode<br />\[Missing <returns> documentation for "M:DevCase.Core.Maths.Amount.System#IConvertible#GetTypeCode"\]

#### Implements
IConvertible.GetTypeCode()<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_Amount">Amount Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />