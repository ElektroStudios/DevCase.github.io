# CommandLineValueParameter(*T*).Value Property 
 

Gets or sets the parameter's value defined by the end-user. 

 This value should be initially a null reference (`Nothing` in Visual Basic) before parsing the commandline arguments of the application. 

 The value of the parameter should be assigned by the end-user when passing an argument to the application. 

 To set a default value for this parameter, use <a href="P_DevCase_Core_Application_CommandLineValueParameter_1_DefaultValue">DefaultValue</a> property instead.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public T Value { get; set; }
```

**VB**<br />
``` VB
Public Property Value As T
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameter
Dim value As T

value = instance.Value

instance.Value = value
```

**C++**<br />
``` C++
public:
property T Value {
	T get ();
	void set (T value);
}
```

**F#**<br />
``` F#
member Value : 'T with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">*T*</a><br />The parameter's value defined by the end-user.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T) Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />