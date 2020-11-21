# DevWebBrowser Class
 

A extended WebBrowser control.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.Control<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.WebBrowserBase<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.Windows.Forms.WebBrowser<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Controls.DevWebBrowser<br />
**Namespace:**&nbsp;<a href="N_DevCase_Controls">DevCase.Controls</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(WebBrowser), "WebBrowser.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultPropertyAttribute("Url")]
[DefaultEventAttribute("DocumentCompleted")]
[DockingAttribute(DockingBehavior.Ask)]
public class DevWebBrowser : WebBrowser
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(WebBrowser), "WebBrowser.bmp")>
<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>
<ComVisibleAttribute(true)>
<DefaultPropertyAttribute("Url")>
<DefaultEventAttribute("DocumentCompleted")>
<DockingAttribute(DockingBehavior.Ask)>
Public Class DevWebBrowser
	Inherits WebBrowser
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevWebBrowser
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(WebBrowser), L"WebBrowser.bmp")]
[ClassInterfaceAttribute(ClassInterfaceType::AutoDispatch)]
[ComVisibleAttribute(true)]
[DefaultPropertyAttribute(L"Url")]
[DefaultEventAttribute(L"DocumentCompleted")]
[DockingAttribute(DockingBehavior::Ask)]
public ref class DevWebBrowser : public WebBrowser
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(WebBrowser), "WebBrowser.bmp")>]
[<ClassInterfaceAttribute(ClassInterfaceType.AutoDispatch)>]
[<ComVisibleAttribute(true)>]
[<DefaultPropertyAttribute("Url")>]
[<DefaultEventAttribute("DocumentCompleted")>]
[<DockingAttribute(DockingBehavior.Ask)>]
type DevWebBrowser =  
    class
        inherit WebBrowser
    end
```

The DevWebBrowser type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser__ctor">DevWebBrowser</a></td><td>
Initializes a new instance of the DevWebBrowser class.</td></tr></table>&nbsp;
<a href="#devwebbrowser-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Controls_DevWebBrowser_MouseButtonMiddleEnabled">MouseButtonMiddleEnabled</a></td><td>
Gets or sets a value indicating whether middle mouse button events are handled. 

 In case of you want to prevent the user from using middle mouse button to scroll the page, then set this property to `false` (`False` in Visual Basic).</td></tr></table>&nbsp;
<a href="#devwebbrowser-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_Navigate_1">Navigate(String, CookieCollection)</a></td><td>
Navigates to the specified url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_Navigate_3">Navigate(Uri, CookieCollection)</a></td><td>
Navigates to the specified url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_Navigate">Navigate(String, Boolean, CookieCollection)</a></td><td>
Navigates to the specified url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_Navigate_2">Navigate(Uri, Boolean, CookieCollection)</a></td><td>
Navigates to the specified url.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait">NavigateAndWait(String)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_4">NavigateAndWait(Uri)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_1">NavigateAndWait(String, Boolean)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_3">NavigateAndWait(String, CookieCollection)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_5">NavigateAndWait(Uri, Boolean)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_7">NavigateAndWait(Uri, CookieCollection)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_2">NavigateAndWait(String, Boolean, CookieCollection)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_NavigateAndWait_6">NavigateAndWait(Uri, Boolean, CookieCollection)</a></td><td>
Navigates to the specified url and waits the page to be loaded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_SetCookies">SetCookies(String, Boolean, Cookie[])</a></td><td>
Sets one or more cookies for the specified URL.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_SetCookies_1">SetCookies(String, Boolean, CookieCollection)</a></td><td>
Sets one or more cookies for the specified URL.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_SetCookies_2">SetCookies(Uri, Boolean, Cookie[])</a></td><td>
Sets one or more cookies for the specified URI.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Controls_DevWebBrowser_SetCookies_3">SetCookies(Uri, Boolean, CookieCollection)</a></td><td>
Sets one or more cookies for the specified URI.</td></tr></table>&nbsp;
<a href="#devwebbrowser-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevWebBrowser_BodyClick">BodyClick</a></td><td>
Occurs when the user clicks a mouse button on the current html body.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevWebBrowser_BodyMouseDown">BodyMouseDown</a></td><td>
Occurs when the user clicks a mouse button on the current html body.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevWebBrowser_BodyMouseUp">BodyMouseUp</a></td><td>
Occurs when the user releases a mouse button on the current html body.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevWebBrowser_DocumentClick">DocumentClick</a></td><td>
Occurs when the user clicks a mouse button on the current html document.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevWebBrowser_DocumentMouseDown">DocumentMouseDown</a></td><td>
Occurs when the user clicks a mouse button on the current html document.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")![Code example](media/CodeExample.png "Code example")</td><td><a href="E_DevCase_Controls_DevWebBrowser_DocumentMouseUp">DocumentMouseUp</a></td><td>
Occurs when the user releases a mouse button on the current html document.</td></tr></table>&nbsp;
<a href="#devwebbrowser-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl">ForEachControl(Boolean, Action(Control))</a></td><td>Overloaded.  
Iterate through all the controls in the source Control and performs the specified action on each one.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ForEachControl__1">ForEachControl(T)(Boolean, Action(Control))</a></td><td>Overloaded.  
Iterate through all the controls of the specified type in the source Control and performs the specified action on each one.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetBoundsRelativeToForm">GetBoundsRelativeToForm</a></td><td>
Gets the bounds of the source Control relatively to its parent Form.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetControlStyle">GetControlStyle</a></td><td>
Gets the value of the specified ControlStyles bit for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_GetCookieCollection">GetCookieCollection</a></td><td>
Gets a CookieCollection containing the stored cookies for the active website in the source WebBrowser. (that is, the active opened document in the Document property).
 (Defined by <a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_GetCookieContainer">GetCookieContainer</a></td><td>
Gets a CookieContainer containing the stored cookies for the active website in the source WebBrowser. (that is, the active opened document in the Document property).
 (Defined by <a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_GetEventHandlers">GetEventHandlers(String)</a></td><td>Overloaded.  
Gets all the delegates associated to the specified event raised by the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers(String)</a></td><td>Overloaded.  
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_InvokeWhenHandleValid">InvokeWhenHandleValid</a></td><td>
Performs an action on the specified Control after its handle has been created (that is, when HandleCreated event is fired). 

 If the handle has already been created, the action is executed immediately.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_IsInDesignMode">IsInDesignMode</a></td><td>
Determines whether the source Control is in design mode.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_IsInRuntimeMode">IsInRuntimeMode</a></td><td>
Determines whether the source Control is in runtime mode.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_NavigateAndWait">NavigateAndWait(String)</a></td><td>Overloaded.  
Navigates to the specified url and waits the page to be loaded.
 (Defined by <a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_NavigateAndWait_2">NavigateAndWait(Uri)</a></td><td>Overloaded.  
Navigates to the specified url and waits the page to be loaded.
 (Defined by <a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_NavigateAndWait_1">NavigateAndWait(String, Boolean)</a></td><td>Overloaded.  
Navigates to the specified url and waits the page to be loaded.
 (Defined by <a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions_NavigateAndWait_3">NavigateAndWait(Uri, Boolean)</a></td><td>Overloaded.  
Navigates to the specified url and waits the page to be loaded.
 (Defined by <a href="T_DevCase_Core_Extensions_WebBrowser_WebBrowserExtensions">WebBrowserExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing">ResumeDrawing()</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_ResumeDrawing_1">ResumeDrawing(Boolean)</a></td><td>Overloaded.  
Allow the source Control to be redrawn. 

 By calling this method, it will allow painting events to be fired on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey_1">SendKey(Keys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendKey">SendKey(VirtualKeys, KeyBehavior)</a></td><td>Overloaded.  
Sends a keystroke to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton">SendMouseButton(MouseButton)</a></td><td>Overloaded.  
Sends a mouse button click to the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SendMouseButton_1">SendMouseButton(MouseButton, Point)</a></td><td>Overloaded.  
Sends a mouse button click to the specified coordinates on the specified control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle</a></td><td>
Sets a specified ControlStyles flag to either `true` (`True` in Visual Basic) or `false` (`False` in Visual Basic) for the source control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetDoubleBuffer">SetDoubleBuffer</a></td><td>
Sets the value of DoubleBuffered property for the source Control. 

 You should call this method to set double buffer for a control, instead of calling <a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetControlStyle">SetControlStyle(Control, ControlStyles, Boolean)</a> method with OptimizedDoubleBuffer flag.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SetVisualStyle">SetVisualStyle</a></td><td>
Changes the color appearance of the source Control using the specified style.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")</td><td><a href="M_DevCase_Core_Extensions_Control_ControlExtensions_SuspendDrawing">SuspendDrawing</a></td><td>
Prevents the source Control from being redrawn. 

 By calling this method, it will disallow painting events from firing on the source Control.
 (Defined by <a href="T_DevCase_Core_Extensions_Control_ControlExtensions">ControlExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devwebbrowser-class">Back to Top</a>

## Examples
This is a code example that demonstrates how to login to a website, and navigate to the page using the cookie that contains the login data. 
**VB**<br />
``` VB
Dim uri As New Uri("https://foro.elhacker.net/index.php?action=login2", UriKind.Absolute)
Dim cred As New NetworkCredential("USERNAME", "PASSWORD")
Dim query As String = HttpUtility.ParseQueryString($"cookielength=90&user={cred.UserName}&passwrd={cred.Password}").ToString()

Using client As New DevWebClient() With {.CookiesEnabled = True}
    client.Headers.Add(HttpRequestHeader.ContentType, "application/x-www-form-urlencoded")

    Dim response As String = client.UploadString(uri, "POST", query)
    ' Console.WriteLine(response)

    Dim cookies As CookieCollection = client.CookieContainer.GetCookies(uri)
    DevWebBrowser1.Navigate("https://foro.elhacker.net", cookies)
End Using
```


## See Also


#### Reference
<a href="N_DevCase_Controls">DevCase.Controls Namespace</a><br />