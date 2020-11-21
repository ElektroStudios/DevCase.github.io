# FormattableString.FormatProvider Property 
 

Gets or sets the culture-specific formatting provider.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Text">DevCase.Core.Text</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public IFormatProvider FormatProvider { get; set; }
```

**VB**<br />
``` VB
Public Property FormatProvider As IFormatProvider
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FormattableString
Dim value As IFormatProvider

value = instance.FormatProvider

instance.FormatProvider = value
```

**C++**<br />
``` C++
public:
property IFormatProvider^ FormatProvider {
	IFormatProvider^ get ();
	void set (IFormatProvider^ value);
}
```

**F#**<br />
``` F#
member FormatProvider : IFormatProvider with get, set

```


#### Property Value
Type: IFormatProvider<br />The culture-specific formatting provider.

## See Also


#### Reference
<a href="T_DevCase_Core_Text_FormattableString">FormattableString Class</a><br /><a href="N_DevCase_Core_Text">DevCase.Core.Text Namespace</a><br />