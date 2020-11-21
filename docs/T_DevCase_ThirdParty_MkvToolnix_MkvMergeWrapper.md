# MkvMergeWrapper Class
 

A wrapper of `MkvMerge.exe` application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.ThirdParty.MkvToolnix.MkvMergeWrapper<br />
**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class MkvMergeWrapper : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class MkvMergeWrapper
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As MkvMergeWrapper
```

**C++**<br />
``` C++
public ref class MkvMergeWrapper sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type MkvMergeWrapper =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The MkvMergeWrapper type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper__ctor">MkvMergeWrapper</a></td><td>
Initializes a new instance of the MkvMergeWrapper class.</td></tr></table>&nbsp;
<a href="#mkvmergewrapper-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_Exists">Exists</a></td><td>
Gets a value indicating whether the `MkvMerge.exe` file Exists.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_FilePath">FilePath</a></td><td>
Gets the `MkvMerge.exe` filepath.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_Process">Process</a></td><td>
Gets the `MkvMerge.exe`<a href="P_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_Process">Process</a> instance.</td></tr></table>&nbsp;
<a href="#mkvmergewrapper-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_VideoContainsTrackType">VideoContainsTrackType</a></td><td>
Determines whether the source video file contains the specified type of track.</td></tr></table>&nbsp;
<a href="#mkvmergewrapper-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_Exited">Exited</a></td><td>
Event raised when the `MkvMerge.exe` process has exited.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_ThirdParty_MkvToolnix_MkvMergeWrapper_Started">Started</a></td><td>
Event raised when the `MkvMerge.exe` process has been started.</td></tr></table>&nbsp;
<a href="#mkvmergewrapper-class">Back to Top</a>

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
<a href="#mkvmergewrapper-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mkvMerge As New MkvMergeWrapper("C:\Program Files\MKV Toolnix\mkvmerge.exe")

MsgBox(mkvMerge.VideoContainsTrackType("C:\File.mkv", MkvTrackType.Audio))
```


## See Also


#### Reference
<a href="N_DevCase_ThirdParty_MkvToolnix">DevCase.ThirdParty.MkvToolnix Namespace</a><br />