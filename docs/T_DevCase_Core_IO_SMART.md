# SMART Class
 

Represents the S.M.A.R.T. information of a hard drive.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.SMART<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[BrowsableAttribute(true)]
[TypeConverterAttribute(typeof(ExpandableObjectConverter))]
public sealed class SMART : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<BrowsableAttribute(true)>
<TypeConverterAttribute(GetType(ExpandableObjectConverter))>
Public NotInheritable Class SMART
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SMART
```

**C++**<br />
``` C++
[SerializableAttribute]
[BrowsableAttribute(true)]
[TypeConverterAttribute(typeof(ExpandableObjectConverter))]
public ref class SMART sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<BrowsableAttribute(true)>]
[<TypeConverterAttribute(typeof(ExpandableObjectConverter))>]
type SMART =  
    class
        inherit AestheticObject
    end
```

The SMART type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_SMART__ctor">SMART(Char)</a></td><td>
Initializes a new instance of the SMART class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_SMART__ctor_1">SMART(DriveInfo)</a></td><td>
Initializes a new instance of the SMART class.</td></tr></table>&nbsp;
<a href="#smart-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_SMART_Attributes">Attributes</a></td><td>
Gets the S.M.A.R.T. attributes of the hard drive.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_SMART_IsHealthOk">IsHealthOk</a></td><td>
Gets a value that determine whether the health status of the hard drive is ok.</td></tr></table>&nbsp;
<a href="#smart-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_SMART_Refresh">Refresh</a></td><td>
Refreshes the hard drive properties of this instance.</td></tr></table>&nbsp;
<a href="#smart-class">Back to Top</a>

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
<a href="#smart-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim SMART As New SMART("C"c)

Dim sb As New StringBuilder()
For Each attr As SmartAttribute In SMART.Attributes

    sb.AppendFormat("Id: {0:X2}, Name: {1,-30}, Current: {2,3}, Worst: {3,3}, Threshold: {4,3}, RAW: {5,12:X12}, IsHealthOk?: {6}",
                    attr.Id, attr.Name,
                    attr.CurrentValue, attr.WorstValue, attr.Threshold, attr.RawValue32,
                    attr.IsHealthOk)
    sb.AppendLine()

Next attr

Console.WriteLine(sb.ToString())
```


## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />