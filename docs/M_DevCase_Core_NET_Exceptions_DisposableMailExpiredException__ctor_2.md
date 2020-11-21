# DisposableMailExpiredException Constructor (String, Exception)
 

Initializes a new instance of the <a href="T_DevCase_Core_NET_Exceptions_DisposableMailExpiredException">DisposableMailExpiredException</a> class with a specified error message.

**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public DisposableMailExpiredException(
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

Dim instance As New DisposableMailExpiredException(message, 
	innerException)
```

**C++**<br />
``` C++
public:
DisposableMailExpiredException(
	String^ message, 
	Exception^ innerException
)
```

**F#**<br />
``` F#
new : 
        message : string * 
        innerException : Exception -> DisposableMailExpiredException
```


#### Parameters
&nbsp;<dl><dt>message</dt><dd>Type: System.String<br />The message that describes the error.</dd><dt>innerException</dt><dd>Type: System.Exception<br />The exception that is the cause of the current exception, or a null reference (a null reference (`Nothing` in Visual Basic) in Visual Basic) if no inner exception is specified.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_NET_Exceptions_DisposableMailExpiredException">DisposableMailExpiredException Class</a><br /><a href="Overload_DevCase_Core_NET_Exceptions_DisposableMailExpiredException__ctor">DisposableMailExpiredException Overload</a><br /><a href="N_DevCase_Core_NET_Exceptions">DevCase.Core.NET.Exceptions Namespace</a><br />