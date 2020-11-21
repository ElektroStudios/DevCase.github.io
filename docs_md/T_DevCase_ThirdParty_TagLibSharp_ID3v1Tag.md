# ID3v1Tag Class
 

Represents the `ID3v1` tag for a MP3 file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.TagLibSharp.ID3v1Tag<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="T_DevCase_ThirdParty_TagLibSharp_ID3v2Tag">DevCase.ThirdParty.TagLibSharp.ID3v2Tag</a><br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ID3v1Tag : AestheticObject
```

**VB**<br />
``` VB
Public Class ID3v1Tag
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ID3v1Tag
```

**C++**<br />
``` C++
public ref class ID3v1Tag : public AestheticObject
```

**F#**<br />
``` F#
type ID3v1Tag =  
    class
        inherit AestheticObject
    end
```

The ID3v1Tag type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_ID3v1Tag__ctor">ID3v1Tag</a></td><td>
Initializes a new instance of the ID3v1Tag class.</td></tr></table>&nbsp;
<a href="#id3v1tag-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Album">Album</a></td><td>
Gets or sets the `Album` metatada field of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Artist">Artist</a></td><td>
Gets or sets the `Artist` metatada field of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Comment">Comment</a></td><td>
Gets or sets the `Comment` metatada field of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Genre">Genre</a></td><td>
Gets or sets the `Genre` metatada field of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_IsEmpty">IsEmpty</a></td><td>
Gets a value indicating whether the `ID3v1` tag is empty.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Tag">Tag</a></td><td>
Gets the `ID3v1` tag of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Title">Title</a></td><td>
Gets or sets the `Title` metatada field of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Track">Track</a></td><td>
Gets or sets the `Track` metatada field of the audio file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Year">Year</a></td><td>
Gets or sets the `Year` metatada field of the audio file.</td></tr></table>&nbsp;
<a href="#id3v1tag-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Clear">Clear</a></td><td>
Clears all the ID3v1 fields.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_TagLibSharp_ID3v1Tag_Remove">Remove</a></td><td>
Entirely removes the ID3v1 tag.</td></tr></table>&nbsp;
<a href="#id3v1tag-class">Back to Top</a>

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
<a href="#id3v1tag-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_TagLibSharp">DevCase.ThirdParty.TagLibSharp Namespace</a><br />