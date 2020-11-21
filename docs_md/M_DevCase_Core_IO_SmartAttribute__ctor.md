# SmartAttribute Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_IO_SmartAttribute">SmartAttribute</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public SmartAttribute(
	byte[] predictData,
	byte[] predictThresholds,
	int attributeIndex
)
```

**VB**<br />
``` VB
Public Sub New ( 
	predictData As Byte(),
	predictThresholds As Byte(),
	attributeIndex As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim predictData As Byte()
Dim predictThresholds As Byte()
Dim attributeIndex As Integer

Dim instance As New SmartAttribute(predictData, 
	predictThresholds, attributeIndex)
```

**C++**<br />
``` C++
public:
SmartAttribute(
	array<unsigned char>^ predictData, 
	array<unsigned char>^ predictThresholds, 
	int attributeIndex
)
```

**F#**<br />
``` F#
new : 
        predictData : byte[] * 
        predictThresholds : byte[] * 
        attributeIndex : int -> SmartAttribute
```


#### Parameters
&nbsp;<dl><dt>predictData</dt><dd>Type: System.Byte[]<br />The vendor-specific S.M.A.R.T. data from 'MSStorageDriver_FailurePredictData' WMI class.</dd><dt>predictThresholds</dt><dd>Type: System.Byte[]<br />The vendor-specific S.M.A.R.T. data from 'MSStorageDriver_FailurePredictThresholds' WMI class.</dd><dt>attributeIndex</dt><dd>Type: System.Int32<br />The index of the S.M.A.R.T. attribute to retrieve.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_SmartAttribute">SmartAttribute Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />