# ArrayExtensions Class
 

Contains custom extension methods to use with an Array.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.Extensions.Array.ArrayExtensions<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[HideModuleNameAttribute]
public sealed class ArrayExtensions
```

**VB**<br />
``` VB
<ExtensionAttribute>
<HideModuleNameAttribute>
Public NotInheritable Class ArrayExtensions
```

**VB Usage**<br />
``` VB Usage
Dim instance As ArrayExtensions
```

**C++**<br />
``` C++
[ExtensionAttribute]
[HideModuleNameAttribute]
public ref class ArrayExtensions sealed
```

**F#**<br />
``` F#
[<SealedAttribute>]
[<ExtensionAttribute>]
[<HideModuleNameAttribute>]
type ArrayExtensions =  class end
```

The ArrayExtensions type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_DeinitializeAll__1">DeinitializeAll(T)(T[])</a></td><td>
Deinitializes all the elements of the specified Array. 

 This method just turns to a null reference (`Nothing` in Visual Basic) all the elements, 

 if you also need to dispose them, call <a href="M_DevCase_Core_Extensions_IDisposable_IDisposableExtensions_DisposeAll__1">DisposeAll(T)(T[])</a> method instead.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_DeinitializeAll__1_1">DeinitializeAll(T)(T[][])</a></td><td>
Deinitializes all the elements of the specified jagged Array. 

 This method just turns to a null reference (`Nothing` in Visual Basic) all the elements, 

 if you also need to dispose them, call <a href="M_DevCase_Core_Extensions_IDisposable_IDisposableExtensions_DisposeAll__1">DisposeAll(T)(T[])</a> method instead.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FillBounds__1">FillBounds(T)</a></td><td>
Fills the indices (or columns) of the specified index bound (or row) of the source array, using the given collection of elements.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_Find__1">Find(T)(T[,,,], Predicate(T))</a></td><td>
Searches for an element in the source four-dimensional array that matches the conditions defined by the specified predicate, and returns its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_Find__1_1">Find(T)(T[,,], Predicate(T))</a></td><td>
Searches for an element in the source three-dimensional array that matches the conditions defined by the specified predicate, and returns its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_Find__1_2">Find(T)(T[,], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional array that matches the conditions defined by the specified predicate, and returns its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_Find__1_3">Find(T)(T[][], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional jagged array that matches the conditions defined by the specified predicate, and returns its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindAll__1">FindAll(T)(T[,,,], Predicate(T))</a></td><td>
Searches for all the elements in the source four-dimensional array that matches the conditions defined by the specified predicate.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindAll__1_1">FindAll(T)(T[,,], Predicate(T))</a></td><td>
Searches for all the elements in the source three-dimensional array that matches the conditions defined by the specified predicate.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindAll__1_2">FindAll(T)(T[,], Predicate(T))</a></td><td>
Searches for all the elements in the source two-dimensional array that matches the conditions defined by the specified predicate.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindAll__1_3">FindAll(T)(T[][], Predicate(T))</a></td><td>
Searches for all the elements in the source two-dimensional jagged array that matches the conditions defined by the specified predicate.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindIndex__1">FindIndex(T)(T[,,,], Predicate(T))</a></td><td>
Searches for an element in the source four-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindIndex__1_1">FindIndex(T)(T[,,], Predicate(T))</a></td><td>
Searches for an element in the source three-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindIndex__1_2">FindIndex(T)(T[,], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindIndex__1_3">FindIndex(T)(T[][], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional jagged array that matches the conditions defined by the specified predicate, and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLast__1">FindLast(T)(T[,,,], Predicate(T))</a></td><td>
Searches for an element in the source four-dimensional array that matches the conditions defined by the specified predicate, and returns its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLast__1_1">FindLast(T)(T[,,], Predicate(T))</a></td><td>
Searches for an element in the source three-dimensional array that matches the conditions defined by the specified predicate, and returns its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLast__1_2">FindLast(T)(T[,], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional array that matches the conditions defined by the specified predicate, and returns its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLast__1_3">FindLast(T)(T[][], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional jagged array that matches the conditions defined by the specified predicate, and returns its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLastIndex__1">FindLastIndex(T)(T[,,,], Predicate(T))</a></td><td>
Searches for an element in the source four-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLastIndex__1_1">FindLastIndex(T)(T[,,], Predicate(T))</a></td><td>
Searches for an element in the source three-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLastIndex__1_2">FindLastIndex(T)(T[,], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional array that matches the conditions defined by the specified predicate, and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_FindLastIndex__1_3">FindLastIndex(T)(T[][], Predicate(T))</a></td><td>
Searches for an element in the source two-dimensional jagged array that matches the conditions defined by the specified predicate, and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_ForEach__1">ForEach(T)(T[,,,], Action(T))</a></td><td>
Performs the specified action on each element of the specified four-dimensional array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_ForEach__1_1">ForEach(T)(T[,,], Action(T))</a></td><td>
Performs the specified action on each element of the specified three-dimensional array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_ForEach__1_2">ForEach(T)(T[,], Action(T))</a></td><td>
Performs the specified action on each element of the specified two-dimensional array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_ForEach__1_3">ForEach(T)(T[], Action(T))</a></td><td>
Performs the specified action on each element of the source collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_ForEach__1_4">ForEach(T)(T[][], Action(T))</a></td><td>
Performs the specified action on each element of the specified two-dimensional jagged array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_GetRandomItem__1">GetRandomItem(T)</a></td><td>
Gets a random element from the source array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndexOf__1">IndexOf(T)(T[,,,], T)</a></td><td>
Searches for the specified object in the source four-dimensional array and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndexOf__1_1">IndexOf(T)(T[,,], T)</a></td><td>
Searches for the specified object in the source three-dimensional array and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndexOf__1_2">IndexOf(T)(T[,], T)</a></td><td>
Searches for the specified object in the source two-dimensional array and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndexOf__1_3">IndexOf(T)(T[][], T)</a></td><td>
Searches for the specified object in the source two-dimensional jagged array and returns the index of its first occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndicesOf__1">IndicesOf(T)(T[,,,], T)</a></td><td>
Searches for the specified object in the source four-dimensional array and returns the index of all its occurrences.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndicesOf__1_1">IndicesOf(T)(T[,,], T)</a></td><td>
Searches for the specified object in the source three-dimensional array and returns the index of all its occurrences.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndicesOf__1_2">IndicesOf(T)(T[,], T)</a></td><td>
Searches for the specified object in the source two-dimensional array and returns the index of all its occurrences.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_IndicesOf__1_3">IndicesOf(T)(T[][], T)</a></td><td>
Searches for the specified object in the source two-dimensional jagged array and returns the index of all its occurrences.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_InitializeAll__1">InitializeAll(T)(T[])</a></td><td>
Initializes all the elements (that aren't already initialized) of the specified Array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_InitializeAll__1_1">InitializeAll(T)(T[][])</a></td><td>
Initializes all the elements (that aren't already initialized) of the specified jagged Array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_LastIndexOf__1">LastIndexOf(T)(T[,,,], T)</a></td><td>
Searches for the specified object in the source four-dimensional array and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_LastIndexOf__1_1">LastIndexOf(T)(T[,,], T)</a></td><td>
Searches for the specified object in the source three-dimensional array and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_LastIndexOf__1_2">LastIndexOf(T)(T[,], T)</a></td><td>
Searches for the specified object in the source two-dimensional array and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_LastIndexOf__1_3">LastIndexOf(T)(T[][], T)</a></td><td>
Searches for the specified object in the source two-dimensional jagged array and returns the index of its last occurrence.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Array_ArrayExtensions_Resize__1">Resize(T)</a></td><td>
Resizes the number of elements of the source collection.</td></tr></table>&nbsp;
<a href="#arrayextensions-class">Back to Top</a>

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
<a href="#arrayextensions-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />