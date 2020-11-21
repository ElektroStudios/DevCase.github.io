# Histogram Class
 

A class that represents a RGB histogram of an image.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.Histogram<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("Histogram")]
public class Histogram : AestheticObject
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("Histogram")>
Public Class Histogram
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As Histogram
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"Histogram")]
public ref class Histogram : public AestheticObject
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<XmlRootAttribute("Histogram")>]
type Histogram =  
    class
        inherit AestheticObject
    end
```

The Histogram type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_Histogram__ctor">Histogram(Bitmap)</a></td><td>
Initializes a new instance of the Histogram class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_Histogram__ctor_1">Histogram(String)</a></td><td>
Initializes a new instance of the Histogram class.</td></tr></table>&nbsp;
<a href="#histogram-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_Histogram_Bitmap">Bitmap</a></td><td>
Gets the source image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_Histogram_Blue">Blue</a></td><td>
Gets the blue values in the source image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_Histogram_Green">Green</a></td><td>
Gets the green values in the source image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_Histogram_Red">Red</a></td><td>
Gets the red values in the source image.</td></tr></table>&nbsp;
<a href="#histogram-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_Histogram_GetVariance">GetVariance</a></td><td>
Gets the variance between two different Histogram as a percentage of the maximum possible variance: 256 (for a white image compared to a black image).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_Histogram_ToString">ToString</a></td><td>
Returns a human-readable representation of the RGB values in the histogram.
 (Overrides AestheticObject.ToString().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_Histogram_Visualize">Visualize</a></td><td>
Gets a Bitmap with the RGB histograms.</td></tr></table>&nbsp;
<a href="#histogram-class">Back to Top</a>

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
<a href="#histogram-class">Back to Top</a>

## Remarks
<a href="http://www.codeproject.com/Articles/374386/Simple-image-comparison-in-NET" target="_blank">http://www.codeproject.com/Articles/374386/Simple-image-comparison-in-NET</a>

## Examples
This is a code example. 
**VB**<br />
``` VB

```


## See Also


#### Reference
<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />