# CaptchaGenerator Class
 

A Captcha generator for applications.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.CaptchaGenerator<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class CaptchaGenerator : AestheticObject
```

**VB**<br />
``` VB
Public Class CaptchaGenerator
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As CaptchaGenerator
```

**C++**<br />
``` C++
public ref class CaptchaGenerator : public AestheticObject
```

**F#**<br />
``` F#
type CaptchaGenerator =  
    class
        inherit AestheticObject
    end
```

The CaptchaGenerator type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_CaptchaGenerator__ctor">CaptchaGenerator</a></td><td>
Initializes a new instance of the CaptchaGenerator class.</td></tr></table>&nbsp;
<a href="#captchagenerator-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_BackgroundColor1">BackgroundColor1</a></td><td>
Gets or sets the first background color.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_BackgroundColor2">BackgroundColor2</a></td><td>
Gets or sets the second background color.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_Characters">Characters</a></td><td>
Gets or sets the character set to build the captcha text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_CurveColor">CurveColor</a></td><td>
Gets or sets the color of the curve.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_CurveEnabled">CurveEnabled</a></td><td>
Gets or sets a value indicating whether curve drawing is enabled in the captcha image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_CurveTension">CurveTension</a></td><td>
Gets or sets the curve tension.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_CurveWidth">CurveWidth</a></td><td>
Gets or sets the width of the curve.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_Fonts">Fonts</a></td><td>
Gets or sets the fonts to use in the captcha generation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_FontStyle">FontStyle</a></td><td>
Gets or sets the font style of the captcha text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_GridColor">GridColor</a></td><td>
Gets or sets the color of the grid.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_GridEnabled">GridEnabled</a></td><td>
Gets or sets a value indicating whether grid drawing is enabled in the captcha image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_GridSpacing">GridSpacing</a></td><td>
Gets or sets the grid spacing.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_GridWidth">GridWidth</a></td><td>
Gets or sets the width of the grid.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_Size">Size</a></td><td>
Gets or sets the size of the captcha image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_TextAlignmentEnabled">TextAlignmentEnabled</a></td><td>
Gets or sets a value indicating whether text alignment is enabled in the captcha image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_TextColor">TextColor</a></td><td>
Gets or sets the color of the captcha text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_CaptchaGenerator_TextLength">TextLength</a></td><td>
Gets or sets the length of the captcha text.</td></tr></table>&nbsp;
<a href="#captchagenerator-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_CaptchaGenerator_Generate">Generate</a></td><td>
Generates the <a href="T_DevCase_Core_Application_UserInterface_Captcha">Captcha</a>.</td></tr></table>&nbsp;
<a href="#captchagenerator-class">Back to Top</a>

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
<a href="#captchagenerator-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rng As New Random

Dim captchaGen As New CaptchaGenerator
With captchaGen

    .Size = Me.PictureBox1.Size

    .TextLength = 5
    .TextColor = Color.White
    .TextAlignmentEnabled = True

    .Fonts = {SystemFonts.DefaultFont.FontFamily}
    .FontStyle = FontStyle.Bold

    .BackgroundColor1 = Color.FromKnownColor(DirectCast(rng.Next([Enum].GetValues(GetType(KnownColor)).Length), KnownColor))
    .BackgroundColor2 = Color.FromKnownColor(DirectCast(rng.Next([Enum].GetValues(GetType(KnownColor)).Length), KnownColor))

    .GridEnabled = True
    .GridColor = Color.DimGray

    .GridWidth = 1.0F
    .GridSpacing = 3

    .CurveEnabled = True
    .CurveColor = Color.Black
    .CurveWidth = 2.5F
    .CurveTension = 8.0F

End With

Dim captcha As Captcha = captchaGen.Generate
Me.PictureBox1.BackgroundImage = captcha.Image
' captcha.Dispose()
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />