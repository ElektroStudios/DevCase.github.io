# NativeUtil.FailIfFalse Method 
 

Evaluates the supplied unmanaged return value and, if it is equal to `false` (`False` in Visual Basic), throws the corresponding Win32Exception. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool FailIfFalse(
	bool returnValue
)
```

**VB**<br />
``` VB
Public Shared Function FailIfFalse ( 
	returnValue As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Boolean
Dim returnValue As Boolean

returnValue = NativeUtil.FailIfFalse(returnValue)
```

**C++**<br />
``` C++
public:
static bool FailIfFalse(
	bool returnValue
)
```

**F#**<br />
``` F#
static member FailIfFalse : 
        returnValue : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>returnValue</dt><dd>Type: System.Boolean<br />The return value to test.</dd></dl>

#### Return Value
Type: Boolean<br />The supplied return value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />