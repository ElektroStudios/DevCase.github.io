# AppUtil.CreateMutex Method (MutexScope, String, Boolean, Boolean, MutexSecurity)
 

Initializes a new instance of the Mutex class with a Boolean value that indicates whether the calling thread should have initial ownership of the Mutex, a String that is the name of the mutex, a Boolean variable that, when the method returns, indicates whether the calling thread was granted initial ownership of the Mutex, and the access control security to be applied to the Mutex.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Mutex CreateMutex(
	MutexScope scope,
	string name,
	bool initiallyOwned,
	ref bool refCreatedNew,
	MutexSecurity mutexSecurity
)
```

**VB**<br />
``` VB
Public Shared Function CreateMutex ( 
	scope As MutexScope,
	name As String,
	initiallyOwned As Boolean,
	ByRef refCreatedNew As Boolean,
	mutexSecurity As MutexSecurity
) As Mutex
```

**VB Usage**<br />
``` VB Usage
Dim scope As MutexScope
Dim name As String
Dim initiallyOwned As Boolean
Dim refCreatedNew As Boolean
Dim mutexSecurity As MutexSecurity
Dim returnValue As Mutex

returnValue = AppUtil.CreateMutex(scope, 
	name, initiallyOwned, refCreatedNew, 
	mutexSecurity)
```

**C++**<br />
``` C++
public:
static Mutex^ CreateMutex(
	MutexScope scope, 
	String^ name, 
	bool initiallyOwned, 
	bool% refCreatedNew, 
	MutexSecurity^ mutexSecurity
)
```

**F#**<br />
``` F#
static member CreateMutex : 
        scope : MutexScope * 
        name : string * 
        initiallyOwned : bool * 
        refCreatedNew : bool byref * 
        mutexSecurity : MutexSecurity -> Mutex 

```


#### Parameters
&nbsp;<dl><dt>scope</dt><dd>Type: <a href="T_DevCase_Core_Application_MutexScope">DevCase.Core.Application.MutexScope</a><br />The visibility scope for the Mutex object to be created.</dd><dt>name</dt><dd>Type: System.String<br />The name of the system mutex. 

 If the value is a null reference (`Nothing` in Visual Basic), the Mutex is unnamed.</dd><dt>initiallyOwned</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to give the calling thread initial ownership of the named system mutex if the named system mutex is created as a result of this call; otherwise, `false` (`False` in Visual Basic).</dd><dt>refCreatedNew</dt><dd>Type: System.Boolean<br />When this method returns, contains a Boolean that is `true` (`True` in Visual Basic) if a local mutex was created (that is, if name is null or an empty string) or if the specified named system mutex was created; `false` (`False` in Visual Basic) if the specified named system mutex already existed.</dd><dt>mutexSecurity</dt><dd>Type: System.Security.AccessControl.MutexSecurity<br />A MutexSecurity object that represents the access control security to be applied to the named system mutex.</dd></dl>

#### Return Value
Type: Mutex<br />The resulting Mutex object.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim mutexName As String = Guid.NewGuid().ToString()
Dim initiallyOwned As Boolean = True
Dim createdNew As Boolean

Dim allowEveryoneRule As New MutexAccessRule(New SecurityIdentifier(WellKnownSidType.WorldSid, Nothing), MutexRights.FullControl, AccessControlType.Allow)
Dim mutexSecurity As New MutexSecurity()
mutexSecurity.AddAccessRule(allowEveryoneRule)

Dim mutex As Mutex = CreateMutex(MutexScope.Global, mutexName, initiallyOwned, createdNew, mutexSecurity)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="Overload_DevCase_Core_Application_Tools_AppUtil_CreateMutex">CreateMutex Overload</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />