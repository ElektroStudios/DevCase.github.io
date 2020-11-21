# ControlIterator Class
 

Iterates a collection of controls to perform a specific task.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.Tools.Graphical.ControlIterator<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ControlIterator : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ControlIterator
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ControlIterator
```

**C++**<br />
``` C++
public ref class ControlIterator sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ControlIterator =  
    class
        inherit AestheticObject
    end
```

The ControlIterator type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncCheck">AsyncCheck(IEnumerable(Control))</a></td><td>
Asynchronously Check multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncCheck_1">AsyncCheck(Control)</a></td><td>
Asynchronously Check an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncCheck__1">AsyncCheck(T)(String)</a></td><td>
Asynchronously Check all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncCheck__1_1">AsyncCheck(T)(Control, String)</a></td><td>
Asynchronously Check all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncCheck__1_2">AsyncCheck(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Check all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDisable">AsyncDisable(IEnumerable(Control))</a></td><td>
Asynchronously Disable multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDisable_1">AsyncDisable(Control)</a></td><td>
Asynchronously Disable an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDisable__1">AsyncDisable(T)(String)</a></td><td>
Asynchronously Disable all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDisable__1_1">AsyncDisable(T)(Control, String)</a></td><td>
Asynchronously Disable all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDisable__1_2">AsyncDisable(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Disable all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDispose">AsyncDispose(IEnumerable(Control))</a></td><td>
Asynchronously Dispose multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDispose_1">AsyncDispose(Control)</a></td><td>
Asynchronously Dispose an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDispose__1">AsyncDispose(T)(String)</a></td><td>
Asynchronously Dispose all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDispose__1_1">AsyncDispose(T)(Control, String)</a></td><td>
Asynchronously Dispose all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncDispose__1_2">AsyncDispose(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Dispose all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncEnable">AsyncEnable(IEnumerable(Control))</a></td><td>
Asynchronously Enable multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncEnable_1">AsyncEnable(Control)</a></td><td>
Asynchronously Enable an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncEnable__1">AsyncEnable(T)(String)</a></td><td>
Asynchronously Enable all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncEnable__1_1">AsyncEnable(T)(Control, String)</a></td><td>
Asynchronously Enable all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncEnable__1_2">AsyncEnable(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Enable all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncHide">AsyncHide(IEnumerable(Control))</a></td><td>
Asynchronously Hide multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncHide_1">AsyncHide(Control)</a></td><td>
Asynchronously Hide an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncHide__1">AsyncHide(T)(String)</a></td><td>
Asynchronously Hide all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncHide__1_1">AsyncHide(T)(Control, String)</a></td><td>
Asynchronously Hide all the Controls of the specified Type on the specified Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncHide__1_2">AsyncHide(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Hide all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction">AsyncPerformAction(IEnumerable(Control), Delegate)</a></td><td>
Perform an asynchronous operation on multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction_1">AsyncPerformAction(Control, Delegate)</a></td><td>
Perform an asynchronous operation on a specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction__1">AsyncPerformAction(T)(Delegate, String)</a></td><td>
Perform an asynchronous operation on all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction__1_1">AsyncPerformAction(T)(Control, Delegate, String)</a></td><td>
Perform an asynchronous operation on all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncPerformAction__1_2">AsyncPerformAction(T)(Control.ControlCollection, Delegate, String)</a></td><td>
Perform an asynchronous operation on all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncShow">AsyncShow(IEnumerable(Control))</a></td><td>
Asynchronously Show multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncShow_1">AsyncShow(Control)</a></td><td>
Asynchronously Show an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncShow__1">AsyncShow(T)(String)</a></td><td>
Asynchronously Show all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncShow__1_1">AsyncShow(T)(Control, String)</a></td><td>
Asynchronously Show all the Controls of the specified Type on the specified Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncShow__1_2">AsyncShow(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Show all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleChecked">AsyncToggleChecked(IEnumerable(Control))</a></td><td>
Asynchronously Toggle the checked state of multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleChecked_1">AsyncToggleChecked(Control)</a></td><td>
Asynchronously Toggle the checked state of an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleChecked__1">AsyncToggleChecked(T)(String)</a></td><td>
Asynchronously Toggle the checked state of all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleChecked__1_1">AsyncToggleChecked(T)(Control, String)</a></td><td>
Asynchronously Toggle the checked state of all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleChecked__1_2">AsyncToggleChecked(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Toggle the checked state of all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleEnabled">AsyncToggleEnabled(IEnumerable(Control))</a></td><td>
Asynchronously Toggle the enabled state of multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleEnabled_1">AsyncToggleEnabled(Control)</a></td><td>
Asynchronously Toggle the enabled state of an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleEnabled__1">AsyncToggleEnabled(T)(String)</a></td><td>
Asynchronously Toggle the enabled state of all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleEnabled__1_1">AsyncToggleEnabled(T)(Control, String)</a></td><td>
Asynchronously Toggle the enabled state of all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleEnabled__1_2">AsyncToggleEnabled(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Toggle the enabled state of all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleVisible">AsyncToggleVisible(IEnumerable(Control))</a></td><td>
Asynchronously Toggle the visible state of multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleVisible_1">AsyncToggleVisible(Control)</a></td><td>
Asynchronously Toggle the visible state of an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleVisible__1">AsyncToggleVisible(T)(String)</a></td><td>
Asynchronously Toggle the visible state of all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleVisible__1_1">AsyncToggleVisible(T)(Control, String)</a></td><td>
Asynchronously Toggle the visible state of all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncToggleVisible__1_2">AsyncToggleVisible(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Toggle the visible state of all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncUncheck">AsyncUncheck(IEnumerable(Control))</a></td><td>
Asynchronously Uncheck multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncUncheck_1">AsyncUncheck(Control)</a></td><td>
Asynchronously Uncheck an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncUncheck__1">AsyncUncheck(T)(String)</a></td><td>
Asynchronously Uncheck all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncUncheck__1_1">AsyncUncheck(T)(Control, String)</a></td><td>
Asynchronously Uncheck all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_AsyncUncheck__1_2">AsyncUncheck(T)(Control.ControlCollection, String)</a></td><td>
Asynchronously Uncheck all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Check">Check(IEnumerable(Control))</a></td><td>
Check multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Check_1">Check(Control)</a></td><td>
Check an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Check__1">Check(T)(String)</a></td><td>
Check all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Check__1_1">Check(T)(Control, String)</a></td><td>
Check all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Check__1_2">Check(T)(Control.ControlCollection, String)</a></td><td>
Check all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Disable">Disable(IEnumerable(Control))</a></td><td>
Disable multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Disable_1">Disable(Control)</a></td><td>
Disable an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Disable__1">Disable(T)(String)</a></td><td>
Disable all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Disable__1_1">Disable(T)(Control, String)</a></td><td>
Disable all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Disable__1_2">Disable(T)(Control.ControlCollection, String)</a></td><td>
Disable all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Dispose">Dispose(IEnumerable(Control))</a></td><td>
Dispose multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Dispose_1">Dispose(Control)</a></td><td>
Dispose an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Dispose__1">Dispose(T)(String)</a></td><td>
Dispose all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Dispose__1_1">Dispose(T)(Control, String)</a></td><td>
Dispose all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Dispose__1_2">Dispose(T)(Control.ControlCollection, String)</a></td><td>
Dispose all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Enable">Enable(IEnumerable(Control))</a></td><td>
Enable multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Enable_1">Enable(Control)</a></td><td>
Enable an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Enable__1">Enable(T)(String)</a></td><td>
Enable all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Enable__1_1">Enable(T)(Control, String)</a></td><td>
Enable all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Enable__1_2">Enable(T)(Control.ControlCollection, String)</a></td><td>
Enable all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Hide">Hide(IEnumerable(Control))</a></td><td>
Hide multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Hide_1">Hide(Control)</a></td><td>
Hide an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Hide__1">Hide(T)(String)</a></td><td>
Hide all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Hide__1_1">Hide(T)(Control, String)</a></td><td>
Hide all the Controls of the specified Type on the specified Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Hide__1_2">Hide(T)(Control.ControlCollection, String)</a></td><td>
Hide all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction">PerformAction(IEnumerable(Control), Delegate)</a></td><td>
Perform an operation on multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction_1">PerformAction(Control, Delegate)</a></td><td>
Perform an operation on a specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction_2">PerformAction(Control.ControlCollection, Delegate, String)</a></td><td>
Perform an operation on all the Controls on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction__1">PerformAction(T)(Delegate, String)</a></td><td>
Perform an operation on all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction__1_1">PerformAction(T)(Control, Delegate, String)</a></td><td>
Perform an operation on all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_PerformAction__1_2">PerformAction(T)(Control.ControlCollection, Delegate, String)</a></td><td>
Perform an operation on all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Show">Show(IEnumerable(Control))</a></td><td>
Show multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Show_1">Show(Control)</a></td><td>
Show an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Show__1">Show(T)(String)</a></td><td>
Show all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Show__1_1">Show(T)(Control, String)</a></td><td>
Show all the Controls of the specified Type on the specified Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Show__1_2">Show(T)(Control.ControlCollection, String)</a></td><td>
Show all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleChecked">ToggleChecked(IEnumerable(Control))</a></td><td>
Toggle the checked state of multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleChecked_1">ToggleChecked(Control)</a></td><td>
Toggle the checked state of an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleChecked__1">ToggleChecked(T)(String)</a></td><td>
Toggle the checked state of all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleChecked__1_1">ToggleChecked(T)(Control, String)</a></td><td>
Toggle the checked state of all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleChecked__1_2">ToggleChecked(T)(Control.ControlCollection, String)</a></td><td>
Toggle the checked state of all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleEnabled">ToggleEnabled(IEnumerable(Control))</a></td><td>
Toggle the enabled state of multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleEnabled_1">ToggleEnabled(Control)</a></td><td>
Toggle the enabled state of an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleEnabled__1">ToggleEnabled(T)(String)</a></td><td>
Toggle the enabled state of all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleEnabled__1_1">ToggleEnabled(T)(Control, String)</a></td><td>
Toggle the enabled state of all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleEnabled__1_2">ToggleEnabled(T)(Control.ControlCollection, String)</a></td><td>
Toggle the enabled state of all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleVisible">ToggleVisible(IEnumerable(Control))</a></td><td>
Toggle the visible state of multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleVisible_1">ToggleVisible(Control)</a></td><td>
Toggle the visible state of an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleVisible__1">ToggleVisible(T)(String)</a></td><td>
Toggle the visible state of all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleVisible__1_1">ToggleVisible(T)(Control, String)</a></td><td>
Toggle the visible state of all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_ToggleVisible__1_2">ToggleVisible(T)(Control.ControlCollection, String)</a></td><td>
Toggle the visible state of all the Controls of the specified Type on the specified Control Collection.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Uncheck">Uncheck(IEnumerable(Control))</a></td><td>
Uncheck multiple Controls at once.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Uncheck_1">Uncheck(Control)</a></td><td>
Uncheck an specific ctrl.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Uncheck__1">Uncheck(T)(String)</a></td><td>
Uncheck all the Controls of the specified Type on the active Formulary.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Uncheck__1_1">Uncheck(T)(Control, String)</a></td><td>
Uncheck all the Controls of the specified Type on the specified Control Container.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Application_UserInterface_Tools_Graphical_ControlIterator_Uncheck__1_2">Uncheck(T)(Control.ControlCollection, String)</a></td><td>
Uncheck all the Controls of the specified Type on the specified Control Collection.</td></tr></table>&nbsp;
<a href="#controliterator-class">Back to Top</a>

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
<a href="#controliterator-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
ControlIterator.Disable(CheckBox1)

ControlIterator.Enable({CheckBox1, CheckBox2})

ControlIterator.Dispose({CheckBox1, CheckBox2})

ControlIterator.Check(Of CheckBox)(Me)

ControlIterator.Uncheck(Of CheckBox)(Me.GroupBox1)

ControlIterator.Hide(Of CheckBox)("1")

ControlIterator.Show(Of CheckBox)("1")

ControlIterator.PerformAction(Of CheckBox)(Sub(ctrl As CheckBox) ctrl.Visible = True)

ControlIterator.PerformAction(Me.Controls, Sub(c As Control)
                                               c.BackColor = Color.Green
                                           End Sub)

ControlIterator.PerformAction(Of TextBox)(Me.Controls,
                                          Sub(tb As TextBox)
                                              tb.Tag = 2I
                                          End Sub,
                                          containsName:="TextBox_Pattern")

ControlIterator.AsyncPerformAction(RichTextBox1,
                                   Sub(rb As RichTextBox)
                                        For n As Integer = 0 To 9
                                            rb.AppendText(CStr(n))
                                        Next
                                    End Sub)
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />