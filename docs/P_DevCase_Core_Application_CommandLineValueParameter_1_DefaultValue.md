# CommandLineValueParameter(*T*).DefaultValue Property 
 

Gets or sets the default parameter's value. 

 This value should be take into account if, after parsing the command-line arguments of the application, <a href="P_DevCase_Core_Application_CommandLineValueParameter_1_Value">Value</a> is a null reference (`Nothing` in Visual Basic), meaning that the end-user did not assigned any value to this parameter.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public T DefaultValue { get; set; }
```

**VB**<br />
``` VB
Public Property DefaultValue As T
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameter
Dim value As T

value = instance.DefaultValue

instance.DefaultValue = value
```

**C++**<br />
``` C++
public:
property T DefaultValue {
	T get ();
	void set (T value);
}
```

**F#**<br />
``` F#
member DefaultValue : 'T with get, set

```


#### Property Value
Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">*T*</a><br />The default parameter's value.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T) Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />