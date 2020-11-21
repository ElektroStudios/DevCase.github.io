# ChemicalElement Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Maths_ChemicalElement">ChemicalElement</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Maths">DevCase.Core.Maths</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ChemicalElement(
	int atomicNumber,
	string symbol,
	string name,
	decimal atomicWeight
)
```

**VB**<br />
``` VB
Public Sub New ( 
	atomicNumber As Integer,
	symbol As String,
	name As String,
	atomicWeight As Decimal
)
```

**VB Usage**<br />
``` VB Usage
Dim atomicNumber As Integer
Dim symbol As String
Dim name As String
Dim atomicWeight As Decimal

Dim instance As New ChemicalElement(atomicNumber, 
	symbol, name, atomicWeight)
```

**C++**<br />
``` C++
public:
ChemicalElement(
	int atomicNumber, 
	String^ symbol, 
	String^ name, 
	Decimal atomicWeight
)
```

**F#**<br />
``` F#
new : 
        atomicNumber : int * 
        symbol : string * 
        name : string * 
        atomicWeight : decimal -> ChemicalElement
```


#### Parameters
&nbsp;<dl><dt>atomicNumber</dt><dd>Type: System.Int32<br />The atomic number of this <a href="T_DevCase_Core_Maths_ChemicalElement">ChemicalElement</a>.</dd><dt>symbol</dt><dd>Type: System.String<br />The symbol of this <a href="T_DevCase_Core_Maths_ChemicalElement">ChemicalElement</a>.</dd><dt>name</dt><dd>Type: System.String<br />The name of this <a href="T_DevCase_Core_Maths_ChemicalElement">ChemicalElement</a>.</dd><dt>atomicWeight</dt><dd>Type: System.Decimal<br />The atomic weight of this <a href="T_DevCase_Core_Maths_ChemicalElement">ChemicalElement</a>.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Maths_ChemicalElement">ChemicalElement Class</a><br /><a href="N_DevCase_Core_Maths">DevCase.Core.Maths Namespace</a><br />