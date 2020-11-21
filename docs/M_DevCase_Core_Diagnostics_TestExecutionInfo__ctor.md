# TestExecutionInfo Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Core_Diagnostics_TestExecutionInfo">TestExecutionInfo</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public TestExecutionInfo(
	TimeSpan elapsed,
	MethodInfo method,
	bool success,
	Exception exception
)
```

**VB**<br />
``` VB
Public Sub New ( 
	elapsed As TimeSpan,
	method As MethodInfo,
	success As Boolean,
	exception As Exception
)
```

**VB Usage**<br />
``` VB Usage
Dim elapsed As TimeSpan
Dim method As MethodInfo
Dim success As Boolean
Dim exception As Exception

Dim instance As New TestExecutionInfo(elapsed, 
	method, success, exception)
```

**C++**<br />
``` C++
public:
TestExecutionInfo(
	TimeSpan elapsed, 
	MethodInfo^ method, 
	bool success, 
	Exception^ exception
)
```

**F#**<br />
``` F#
new : 
        elapsed : TimeSpan * 
        method : MethodInfo * 
        success : bool * 
        exception : Exception -> TestExecutionInfo
```


#### Parameters
&nbsp;<dl><dt>elapsed</dt><dd>Type: System.TimeSpan<br />The elapsed execution time.</dd><dt>method</dt><dd>Type: System.Reflection.MethodInfo<br />The method metadata.</dd><dt>success</dt><dd>Type: System.Boolean<br />A value indicating whether the execution of the method was successful.</dd><dt>exception</dt><dd>Type: System.Exception<br />The <a href="P_DevCase_Core_Diagnostics_TestExecutionInfo_Exception">Exception</a> that occured during method execution, if any.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Diagnostics_TestExecutionInfo">TestExecutionInfo Class</a><br /><a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />