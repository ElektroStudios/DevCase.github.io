# AestheticException Constructor (String, Exception)
 

Initializes a new instance of the <a href="T_DevCase_Core_Design_AestheticException">AestheticException</a> class.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Design">DevCase.Core.Design</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public AestheticException(
	string message,
	Exception innerException
)
```

**VB**<br />
``` VB
Public Sub New ( 
	message As String,
	innerException As Exception
)
```

**VB Usage**<br />
``` VB Usage
Dim message As String
Dim innerException As Exception

Dim instance As New AestheticException(message, 
	innerException)
```

**C++**<br />
``` C++
public:
AestheticException(
	String^ message, 
	Exception^ innerException
)
```

**F#**<br />
``` F#
new : 
        message : string * 
        innerException : Exception -> AestheticException
```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: System.String<br />The message that describes the error.</dd><dt>innerException</dt><dd>Type: System.Exception<br />The exception that is the cause of the current exception, or a null reference (a null reference (`Nothing` in Visual Basic) in `Visual Basic`) if no inner exception is specified.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_Design_AestheticException">AestheticException Class</a><br /><a href="Overload_DevCase_Core_Design_AestheticException__ctor">AestheticException Overload</a><br /><a href="N_DevCase_Core_Design">DevCase.Core.Design Namespace</a><br />