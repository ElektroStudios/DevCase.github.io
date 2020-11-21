# Filesize Class
 

Defines a filesize. 

 Provides methods to round or convert a filesize between different units of size.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.Filesize<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("Filesize")]
public sealed class Filesize : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("Filesize")>
Public NotInheritable Class Filesize
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As Filesize
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"Filesize")]
public ref class Filesize sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("Filesize")>]
type Filesize =  
    class
        inherit AestheticObject
    end
```

The Filesize type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_Filesize__ctor">Filesize</a></td><td>
Initializes a new instance of the Filesize class.</td></tr></table>&nbsp;
<a href="#filesize-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_Size">Size(SizeUnits)</a></td><td>
Gets the filesize, in the specified unit of size.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_Size_1">Size(SizeUnits, Int32, NumberFormatInfo)</a></td><td>
Gets the filesize, in the specified unit of size, using the specified numeric format.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_SizeRounded">SizeRounded</a></td><td>
Gets the filesize, rounded using the most approximated unit of size.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_SizeRounded_1">SizeRounded(Int32, NumberFormatInfo)</a></td><td>
Gets the filesize, rounded using the most approximated unit of size, with the specified decimal precision.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_SizeUnit">SizeUnit</a></td><td>
Gets the <a href="T_DevCase_Core_IO_SizeUnits">SizeUnits</a> used to round the <a href="P_DevCase_Core_IO_Filesize_Size">Size(SizeUnits)</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_SizeUnitNameLong">SizeUnitNameLong</a></td><td>
Gets the long name of the <a href="T_DevCase_Core_IO_SizeUnits">SizeUnits</a> used to round the <a href="P_DevCase_Core_IO_Filesize_Size">Size(SizeUnits)</a>.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_Filesize_SizeUnitNameShort">SizeUnitNameShort</a></td><td>
Gets the short name of the <a href="T_DevCase_Core_IO_SizeUnits">SizeUnits</a> used to round the <a href="P_DevCase_Core_IO_Filesize_Size">Size(SizeUnits)</a>.</td></tr></table>&nbsp;
<a href="#filesize-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_Filesize_ToString">ToString()</a></td><td>
Returns a String that represents this filesize.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_Filesize_ToString_1">ToString(IFormatProvider)</a></td><td>
Returns a String that represents this filesize.</td></tr></table>&nbsp;
<a href="#filesize-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#filesize-class">Back to Top</a>

## Examples
This is a code example that performs a simple conversion between units of size. 
**VB**<br />
``` VB
Dim fs As New Filesize(1073741824, Filesize.SizeUnits.Byte)

Dim b As Double = fs.Size(Filesize.SizeUnits.Byte)
Dim kb As Double = fs.Size(Filesize.SizeUnits.KiloByte)
Dim mb As Double = fs.Size(Filesize.SizeUnits.MegaByte)
Dim gb As Double = fs.Size(Filesize.SizeUnits.GigaByte)
Dim tb As Double = fs.Size(Filesize.SizeUnits.TeraByte)
Dim pb As Double = fs.Size(Filesize.SizeUnits.PetaByte)
```


## Examples
This is a code example that rounds a filesize in bytes, to its most approximated unit of size. 
**VB**<br />
``` VB
For Each sizeUnit As Filesize.SizeUnits In [Enum].GetValues(GetType(Filesize.SizeUnits))

    Dim fsize As New Filesize(sizeUnit, Filesize.SizeUnits.Byte)

    Dim stringFormat As String =
        String.Format("{0} Bytes rounded to {1} {2}.",
                      fsize.Size(Filesize.SizeUnits.Byte, CultureInfo.CurrentCulture.NumberFormat),
                      fsize.SizeRounded(decimalPrecision:=2, numberFormatInfo:=Nothing),
                      fsize.SizeUnitNameLong)

    Console.WriteLine(stringFormat)

Next sizeUnit
```


## Examples
This is a code example that converts a Terabyte (1099511627776 Bytes) to other units of size. 
**VB**<br />
``` VB
Dim fsize As New Filesize(Filesize.SizeUnits.TeraByte, Filesize.SizeUnits.Byte)

For Each sizeUnit As Filesize.SizeUnits In [Enum].GetValues(GetType(Filesize.SizeUnits))

    Dim stringFormat As String =
        String.Format("{0} Bytes equals to {1} {2}.",
                      fsize.Size(Filesize.SizeUnits.Byte, Nothing, CultureInfo.CurrentCulture.NumberFormat),
                      fsize.Size(sizeUnit, 2, CultureInfo.CurrentCulture.NumberFormat),
                      sizeUnit.ToString())

    Console.WriteLine(stringFormat)

Next sizeUnit
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />