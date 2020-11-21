# ProgressBarValueChangedEventArgs.NewValue Property 
 

Gets the value.

**Namespace:**&nbsp;<a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public override int NewValue { get; }
```

**VB**<br />
``` VB
Public Overrides ReadOnly Property NewValue As Integer
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ProgressBarValueChangedEventArgs
Dim value As Integer

value = instance.NewValue

```

**C++**<br />
``` C++
public:
virtual property int NewValue {
	int get () override;
}
```

**F#**<br />
``` F#
abstract NewValue : int with get
override NewValue : int with get
```


#### Property Value
Type: Int32<br />The value.

## See Also


#### Reference
<a href="T_DevCase_Controls_Eventing_ProgressBarValueChangedEventArgs">ProgressBarValueChangedEventArgs Class</a><br /><a href="N_DevCase_Controls_Eventing">DevCase.Controls.Eventing Namespace</a><br />