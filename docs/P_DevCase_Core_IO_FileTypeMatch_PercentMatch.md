# FileTypeMatch.PercentMatch Property 
 

Gets the percentage match of the matched file type on the source file header, from `0%` to `100%`. 

 This value determines the success percentage, for example a value of `100%` indicates that all the file type signatures were found in the file header; a value of `50%` would indicate that only half of the file type signatures were found in the file header.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public double PercentMatch { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property PercentMatch As Double
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileTypeMatch
Dim value As Double

value = instance.PercentMatch

```

**C++**<br />
``` C++
public:
property double PercentMatch {
	double get ();
}
```

**F#**<br />
``` F#
member PercentMatch : float with get

```


#### Property Value
Type: Double<br />The percentage match of the matched file type on the source file header, from `0%` to `100%`.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_FileTypeMatch">FileTypeMatch Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />