# ColorString Class
 

Defines a Color with an unique string-format representation in the specified string-syntax.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.ColorString<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[XmlRootAttribute("ColorString")]
public sealed class ColorString : AestheticObject, 
	ISerializable, IXmlSerializable
```

**VB**<br />
``` VB
<SerializableAttribute>
<XmlRootAttribute("ColorString")>
Public NotInheritable Class ColorString
	Inherits AestheticObject
	Implements ISerializable, IXmlSerializable
```

**VB Usage**<br />
``` VB Usage
Dim instance As ColorString
```

**C++**<br />
``` C++
[SerializableAttribute]
[XmlRootAttribute(L"ColorString")]
public ref class ColorString sealed : public AestheticObject, 
	ISerializable, IXmlSerializable
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
[<XmlRootAttribute("ColorString")>]
type ColorString =  
    class
        inherit AestheticObject
        interface ISerializable
        interface IXmlSerializable
    end
```

The ColorString type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString__ctor">ColorString(Color)</a></td><td>
Initializes a new instance of the ColorString class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString__ctor_1">ColorString(Pen)</a></td><td>
Initializes a new instance of the ColorString class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString__ctor_2">ColorString(SolidBrush)</a></td><td>
Initializes a new instance of the ColorString class.</td></tr></table>&nbsp;
<a href="#colorstring-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Argb">Argb</a></td><td>
Gets the ARGB color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Color">Color</a></td><td>
Gets the Color.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_CSharp">CSharp</a></td><td>
Gets the C# color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Delphi">Delphi</a></td><td>
Gets the Delphi color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Hex">Hex</a></td><td>
Gets the Hexadecimal color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Hsl">Hsl</a></td><td>
Gets the HSL color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Rgb">Rgb</a></td><td>
Gets the RGB color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_VisualBasic">VisualBasic</a></td><td>
Gets the VisualBasic color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_VisualStudio">VisualStudio</a></td><td>
Gets the VisualStudio color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Web">Web</a></td><td>
Gets the Web color representation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_ColorString_Win32">Win32</a></td><td>
Gets the Win32 color representation.</td></tr></table>&nbsp;
<a href="#colorstring-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString_Equals_1">Equals(Object)</a></td><td>
Determines whether the specified Object is equal to this instance.
 (Overrides AestheticObject.Equals(Object).)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString_Equals">Equals(ColorString)</a></td><td>
Determines whether the specified ColorString is equal to this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides AestheticObject.GetHashCode().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_ColorString_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides AestheticObject.ToString().)</td></tr></table>&nbsp;
<a href="#colorstring-class">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_ColorString_op_Equality">Equality</a></td><td>
Implements the operator =.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_ColorString_op_Explicit">Explicit(Color to ColorString)</a></td><td>
Performs an implicit conversion from Color to ColorString.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_ColorString_op_Implicit">Implicit(ColorString to Color)</a></td><td>
Performs an implicit conversion from ColorString to Color.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_ColorString_op_Inequality">Inequality</a></td><td>
Implements the operator <>.</td></tr></table>&nbsp;
<a href="#colorstring-class">Back to Top</a>

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
<a href="#colorstring-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim colorString As New ColorString(color.FromArgb(255, 91, 146, 198))

Console.WriteLine(String.Format("ColorString Structure Size: {0}", Marshal.SizeOf(GetType(ColorString)).ToString()))
Console.WriteLine(String.Format("Color.Tostring()          : {0}", colorString.Color.ToString()))
Console.WriteLine(String.Format("ColorString.Tostring()    : {0}", colorString.ToString()))
Console.WriteLine()
Console.WriteLine(String.Format("ARGB: {0}", colorString.Argb))
Console.WriteLine(String.Format("RGB : {0}", colorString.Rgb))
Console.WriteLine()
Console.WriteLine(String.Format("Hex  : {0}", colorString.Hex))
Console.WriteLine(String.Format("Web  : {0}", colorString.Web))
Console.WriteLine(String.Format("HSL  : {0}", colorString.Hsl))
Console.WriteLine(String.Format("Win32: {0}", colorString.Win32))
Console.WriteLine()
Console.WriteLine(String.Format("Delphi: {0}", colorString.Delphi))
Console.WriteLine()
Console.WriteLine(String.Format("C# (Int): {0}", colorString.CSharp(CSharpColorFormat.Int)))
Console.WriteLine(String.Format("C# (Hex): {0}", colorString.CSharp(CSharpColorFormat.Hex)))
Console.WriteLine(String.Format("C# (Web): {0}", colorString.CSharp(CSharpColorFormat.Html)))
Console.WriteLine()
Console.WriteLine(String.Format("Vb.Net (Int): {0}", colorString.VisualBasic(VisualBasicColorFormat.Int)))
Console.WriteLine(String.Format("Vb.Net (Hex): {0}", colorString.VisualBasic(VisualBasicColorFormat.Hex)))
Console.WriteLine(String.Format("Vb.Net (Web): {0}", colorString.VisualBasic(VisualBasicColorFormat.Html)))
Console.WriteLine()
Console.WriteLine(String.Format("Visual Studio (Int): {0}", colorString.VisualStudio(VisualStudioColorFormat.Int)))
Console.WriteLine(String.Format("Visual Studio (Hex): {0}", colorString.VisualStudio(VisualStudioColorFormat.Hex)))
```


## See Also


#### Reference
<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />