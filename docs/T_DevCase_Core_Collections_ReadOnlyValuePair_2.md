# ReadOnlyValuePair(*TValue1*, *TValue2*) Structure
 

Represents a read-only pair of values.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
public struct ReadOnlyValuePair<TValue1, TValue2>

```

**VB**<br />
``` VB
<SerializableAttribute>
Public Structure ReadOnlyValuePair(Of TValue1, TValue2)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ReadOnlyValuePair(Of TValue1, TValue2)
```

**C++**<br />
``` C++
[SerializableAttribute]
generic<typename TValue1, typename TValue2>
public value class ReadOnlyValuePair
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<SerializableAttribute>]
type ReadOnlyValuePair<'TValue1, 'TValue2> =  struct end
```


#### Type Parameters
&nbsp;<dl><dt>TValue1</dt><dd>The Type of the first value.</dd><dt>TValue2</dt><dd>The Type of the second value.</dd></dl>&nbsp;
The ReadOnlyValuePair(TValue1, TValue2) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_ReadOnlyValuePair_2__ctor">ReadOnlyValuePair(TValue1, TValue2)</a></td><td>
Initializes a new instance of the ReadOnlyValuePair(TValue1, TValue2) class.</td></tr></table>&nbsp;
<a href="#readonlyvaluepair(*tvalue1*,-*tvalue2*)-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_ReadOnlyValuePair_2_Value1">Value1</a></td><td>
Gets the first value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_ReadOnlyValuePair_2_Value2">Value2</a></td><td>
Gets the second value.</td></tr></table>&nbsp;
<a href="#readonlyvaluepair(*tvalue1*,-*tvalue2*)-structure">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_ReadOnlyValuePair_2_GetHashCode">GetHashCode</a></td><td>
Returns a hash code for this instance.
 (Overrides ValueType.GetHashCode().)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_ReadOnlyValuePair_2_ToString">ToString</a></td><td>
Returns a String that represents this instance.
 (Overrides ValueType.ToString().)</td></tr></table>&nbsp;
<a href="#readonlyvaluepair(*tvalue1*,-*tvalue2*)-structure">Back to Top</a>

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
<a href="#readonlyvaluepair(*tvalue1*,-*tvalue2*)-structure">Back to Top</a>

## Remarks
Original source: <a href="http://github.com/SolutionsDesign/Algorithmia" target="_blank">http://github.com/SolutionsDesign/Algorithmia</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pair As New ReadOnlyValuePair(Of Boolean, Boolean)(False, True)
Console.WriteLine(pair.ToString())
```


## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />