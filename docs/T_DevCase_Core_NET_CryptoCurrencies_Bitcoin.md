# Bitcoin Class
 

Represents the Bitcoin (symbol: BTC) cryptocurrency.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;DevCase.Core.NET.CryptoCurrencies.Bitcoin<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class Bitcoin : ICryptoCurrency
```

**VB**<br />
``` VB
Public Class Bitcoin
	Implements ICryptoCurrency
```

**VB Usage**<br />
``` VB Usage
Dim instance As Bitcoin
```

**C++**<br />
``` C++
public ref class Bitcoin : ICryptoCurrency
```

**F#**<br />
``` F#
type Bitcoin =  
    class
        interface ICryptoCurrency
    end
```

The Bitcoin type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_CryptoCurrencies_Bitcoin__ctor">Bitcoin</a></td><td>
Initializes a new instance of the Bitcoin class.</td></tr></table>&nbsp;
<a href="#bitcoin-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_CryptoCurrencies_Bitcoin_Name">Name</a></td><td>
Gets the canonical name of the Bitcoin cryptocurrency.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_NET_CryptoCurrencies_Bitcoin_Symbol">Symbol</a></td><td>
Gets the symbol of the Bitcoin cryptocurrency.</td></tr></table>&nbsp;
<a href="#bitcoin-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_CryptoCurrencies_Bitcoin_GetPrice">GetPrice(Currencies)</a></td><td>
Gets the price for 1 Bitcoins converted to the specified currency.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_CryptoCurrencies_Bitcoin_GetPrice_1">GetPrice(Double, Currencies)</a></td><td>
Gets the price for the specified amount of Bitcoins converted to the specified currency.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_CryptoCurrencies_Bitcoin_GetPriceAsync">GetPriceAsync(Currencies)</a></td><td>
Asynchronously gets the price for 1 Bitcoins converted to the specified currency.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_NET_CryptoCurrencies_Bitcoin_GetPriceAsync_1">GetPriceAsync(Double, Currencies)</a></td><td>
Asynchronously gets the price for the specified amount of Bitcoins converted to the specified currency.</td></tr></table>&nbsp;
<a href="#bitcoin-class">Back to Top</a>

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
<a href="#bitcoin-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_NET_CryptoCurrencies">DevCase.Core.NET.CryptoCurrencies Namespace</a><br />