# CombinationCollection(*T*) Class
 

Combinations defines a meta-collection, typically a list of lists, of all possible subsets of a particular size from the set of values. 

 This list is enumerable and allows the scanning of all possible combinations using a simple `For Each` loop. 

 Within the returned set, there is no prescribed order. This follows the mathematical concept of choose. 

 For example, put 10 dominoes in a hat and pick 5. The number of possible combinations is defined as "`10 choose 5`", which is calculated as `(10!) / ((10 - 5)! * 5!)`.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Collections.CombinationCollection(T)<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Collections">DevCase.Core.Collections</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CombinationCollection<T> : IMetaCollection<T>

```

**VB**<br />
``` VB
Public NotInheritable Class CombinationCollection(Of T)
	Implements IMetaCollection(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim instance As CombinationCollection(Of T)
```

**C++**<br />
``` C++
generic<typename T>
public ref class CombinationCollection sealed : IMetaCollection<T>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CombinationCollection<'T> =  
    class
        interface IMetaCollection<'T>
    end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type of the values within the list.</dd></dl>&nbsp;
The CombinationCollection(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_CombinationCollection_1__ctor">CombinationCollection(T)(IList(T), Int32)</a></td><td>
Initializes a new instance of the CombinationCollection(T) class. 

 Create a combination set from the provided list of values. 

 The upper index is calculated as `values.Count`, the lower index is user specified. 

 Collection type defaults to <a href="T_DevCase_Core_Collections_MetaCollectionType">WithoutRepetition</a></td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_CombinationCollection_1__ctor_1">CombinationCollection(T)(IList(T), Int32, MetaCollectionType)</a></td><td>
Initializes a new instance of the CombinationCollection(T) class. 

 Create a combination set from the provided list of values. 

 The upper index is calculated as `values.Count`, the lower index is user specified.</td></tr></table>&nbsp;
<a href="#combinationcollection(*t*)-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_CombinationCollection_1_Count">Count</a></td><td>
Gets the number of unique combinations that are defined in this meta-collection. 

 This value is mathematically defined as `Choose(M, N)` where `M` is the set size and `N` is the subset size. 

 This is, `M! / (N! * (M-N)!)`.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_CombinationCollection_1_LowerIndex">LowerIndex</a></td><td>
Gets the lower index of the meta-collection, equal to the number of items returned each iteration.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_CombinationCollection_1_Type">Type</a></td><td>
Gets the type of Combinations set that is generated.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Collections_CombinationCollection_1_UpperIndex">UpperIndex</a></td><td>
Gets the upper index of the meta-collection, equal to the number of items in the initial set.</td></tr></table>&nbsp;
<a href="#combinationcollection(*t*)-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Collections_CombinationCollection_1_GetEnumerator">GetEnumerator</a></td><td>
Gets an enumerator for collecting the list of combinations.</td></tr></table>&nbsp;
<a href="#combinationcollection(*t*)-class">Back to Top</a>

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
<a href="#combinationcollection(*t*)-class">Back to Top</a>

## Explicit Interface Implementations
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Explicit interface implementation](media/pubinterface.gif "Explicit interface implementation")![Private method](media/privmethod.gif "Private method")</td><td><a href="M_DevCase_Core_Collections_CombinationCollection_1_System_Collections_IEnumerable_GetEnumerator">IEnumerable.GetEnumerator</a></td><td /></tr></table>&nbsp;
<a href="#combinationcollection(*t*)-class">Back to Top</a>

## Remarks
When given a input collect `{A, B, C}` and lower index of `2`, the following sets are generated: 

`MetaCollectionType.WithRepetition => {A, A}, {A, B}, {A, C}, {B, B}, {B, C}, {C, C}`

`MetaCollectionType.WithoutRepetition => {A, B}, {A, C}, {B, C}`



 Input sets with multiple equal values will generate redundant combinations in proprotion to the likelyhood of outcome. 

 For example, `{A, A, B, B}` and a lower index of `3` will generate: 

`{A, A, B}, {A, A, B}, {A, B, B}, {A, B, B}`

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim combinations As New CombinationCollection(Of String)({"a", "b", "c"}, 3, MetaCollectionType.WithRepetition)

For Each combination As List(Of String) In combinations
    Console.WriteLine(String.Join(", ", combination))
Next permutation
```


## See Also


#### Reference
<a href="N_DevCase_Core_Collections">DevCase.Core.Collections Namespace</a><br />