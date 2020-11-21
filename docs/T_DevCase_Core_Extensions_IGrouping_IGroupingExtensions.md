# IGroupingExtensions Class
 

Contains custom extension methods to use with an IEnumerable(T).


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.IGrouping.IGroupingExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IGrouping">DevCase.Core.Extensions.IGrouping</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class IGroupingExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class IGroupingExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As IGroupingExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class IGroupingExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type IGroupingExtensions =  class end
```

The IGroupingExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IGrouping_IGroupingExtensions_JoinByFirstGroupElement__2">JoinByFirstGroupElement(T, TKey)(IEnumerable(IGrouping(TKey, T)))</a></td><td>
Takes the first element of each group and joins them into a new IEnumerable(T).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_IGrouping_IGroupingExtensions_JoinByFirstGroupElement__2_1">JoinByFirstGroupElement(T, TKey)(IEnumerable(IGrouping(TKey, T)), Func(T, Boolean))</a></td><td>
Takes the first element that satisfies the specified condition of each group and joins them into a new IEnumerable(T).</td></tr></table>&nbsp;
<a href="#igroupingextensions-class">Back to Top</a>

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
<a href="#igroupingextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_IGrouping">DevCase.Core.Extensions.IGrouping Namespace</a><br />