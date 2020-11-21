# ValueChangedEventArgs(*T*).NewValue Property 
 

Gets the value.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual T NewValue { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property NewValue As T
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ValueChangedEventArgs
Dim value As T

value = instance.NewValue

```

**C++**<br />
``` C++
public:
virtual property T NewValue {
	T get ();
}
```

**F#**<br />
``` F#
abstract NewValue : 'T with get
override NewValue : 'T with get
```


#### Property Value
Type: <a href="T_DevCase_Controls_Eventing_ValueChangedEventArgs_1">*T*</a><br />The value.

## See Also


#### Reference
<a href="T_DevCase_Controls_Eventing_ValueChangedEventArgs_1">ValueChangedEventArgs(T) Class</a><br /><a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing Namespace</a><br />