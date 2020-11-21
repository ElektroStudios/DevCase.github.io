# NumericSequenceFormatter.GetFormat Method 
 

Returns an object that provides formatting services for the specified type.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Object GetFormat(
	Type formatType
)
```

**VB**<br />
``` VB
Public Function GetFormat ( 
	formatType As Type
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As NumericSequenceFormatter
Dim formatType As Type
Dim returnValue As Object

returnValue = instance.GetFormat(formatType)
```

**C++**<br />
``` C++
public:
virtual Object^ GetFormat(
	Type^ formatType
) sealed
```

**F#**<br />
``` F#
abstract GetFormat : 
        formatType : Type -> Object 
override GetFormat : 
        formatType : Type -> Object 
```


#### Parameters
&nbsp;<dl><dt>formatType</dt><dd>Type: System.Type<br />An object that specifies the type of format object to return.</dd></dl>

#### Return Value
Type: Object<br />An instance of the object specified by *formatType* if the IFormatProvider implementation can supply that type of object; otherwise, a null reference (`Nothing` in Visual Basic).

#### Implements
IFormatProvider.GetFormat(Type)<br />

## See Also


#### Reference
<a href="T_DevCase_Core_Application_NumericSequenceFormatter">NumericSequenceFormatter Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />