# SymTagEnum Enumeration
 

Flags combination for <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_SymbolInfo_Tag">Tag</a> property.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum SymTagEnum
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration SymTagEnum
```

**VB Usage**<br />
``` VB Usage
Dim instance As SymTagEnum
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class SymTagEnum
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type SymTagEnum
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.None">**None**</td><td>0</td><td>Indicates that the symbol has no type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Exe">**Exe**</td><td>1</td><td>Indicates that the symbol is an `.exe` file. 

 There is only one SymTagExe symbol per symbol store. 

 It serves as the global scope and does not have a lexical parent.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Compiland">**Compiland**</td><td>2</td><td>Indicates the compiland symbol for each compiland component of the symbol store. 

 For native applications, `SymTagCompiland` symbols correspond to the object files linked into the image. 

 For some kinds of Microsoft Intermediate Language (MSIL) images, there is one compiland per class.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.CompilandDetails">**CompilandDetails**</td><td>3</td><td>Indicates that the symbol contains extended attributes of the compiland. 

 Retrieving these properties may require loading compiland symbols.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.CompilandEnv">**CompilandEnv**</td><td>4</td><td>Indicates that the symbol is an environment string defined for the compiland.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Function">**Function**</td><td>5</td><td>Indicates that the symbol is a function.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Block">**Block**</td><td>6</td><td>Indicates that the symbol is a nested block.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Data">**Data**</td><td>7</td><td>Indicates that the symbol is data.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Annotation">**Annotation**</td><td>8</td><td>Indicates that the symbol is for a code annotation. 

 Children of this symbol are constant data strings (`SymTagData`, `LocIsConstant`, `DataIsConstant`). 

 Most clients ignore this symbol.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Label">**Label**</td><td>9</td><td>Indicates that the symbol is a label.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.PublicSymbol">**PublicSymbol**</td><td>10</td><td>Indicates that the symbol is a public symbol. 

 For native applications, this symbol is the COFF external symbol encountered while linking the image.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Udt">**Udt**</td><td>11</td><td>Indicates that the symbol is a user-defined type (structure, class, or union).</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Enum">**Enum**</td><td>12</td><td>Indicates that the symbol is an enumeration.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.FunctionType">**FunctionType**</td><td>13</td><td>Indicates that the symbol is a function signature type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.PointerType">**PointerType**</td><td>14</td><td>Indicates that the symbol is a pointer type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.ArrayType">**ArrayType**</td><td>15</td><td>Indicates that the symbol is an array type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.BaseType">**BaseType**</td><td>16</td><td>Indicates that the symbol is a base type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Typedef">**Typedef**</td><td>17</td><td>Indicates that the symbol is a typedef, that is, an alias for another type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.BaseClass">**BaseClass**</td><td>18</td><td>Indicates that the symbol is a base class of a user-defined type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Friend">**Friend**</td><td>19</td><td>Indicates that the symbol is a friend of a user-defined type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.FunctionArgType">**FunctionArgType**</td><td>20</td><td>Indicates that the symbol is a function argument.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.FuncDebugStart">**FuncDebugStart**</td><td>21</td><td>Indicates that the symbol is the end location of the function's prologue code.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.FuncDebugEnd">**FuncDebugEnd**</td><td>22</td><td>Indicates that the symbol is the beginning location of the function's epilogue code.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.UsingNamespace">**UsingNamespace**</td><td>23</td><td>Indicates that the symbol is a Namespace DevCase.Interop.name, active in the current scope.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.VTableShape">**VTableShape**</td><td>24</td><td>Indicates that the symbol is a virtual table description.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.VTable">**VTable**</td><td>25</td><td>Indicates that the symbol is a virtual table pointer.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Custom">**Custom**</td><td>26</td><td>Indicates that the symbol is a custom symbol and is not interpreted by `DIA`.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Thunk">**Thunk**</td><td>27</td><td>Indicates that the symbol is a thunk used for sharing data between 16 and 32 bit code.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.CustomType">**CustomType**</td><td>28</td><td>Indicates that the symbol is a custom compiler symbol.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.ManagedType">**ManagedType**</td><td>29</td><td>Indicates that the symbol is in metadata.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.Dimension">**Dimension**</td><td>30</td><td>Indicates that the symbol is a `FORTRAN` multi-dimensional array.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.CallSite">**CallSite**</td><td>31</td><td>Indicates that the symbol represents the call site.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.InlineSite">**InlineSite**</td><td>32</td><td>Indicates that the symbol represents the inline site.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.BaseInterface">**BaseInterface**</td><td>33</td><td>Indicates that the symbol is a base interface.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.VectorType">**VectorType**</td><td>34</td><td>Indicates that the symbol is a vector type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.MatrixType">**MatrixType**</td><td>35</td><td>Indicates that the symbol is a matrix type.</td></tr><tr><td /><td target="F:DevCase.Interop.Unmanaged.Win32.Enums.SymTagEnum.HlslType">**HlslType**</td><td>36</td><td>Indicates that the symbol is a High Level Shader Language type.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/bkedss5f.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/bkedss5f.aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Enums">DevCase.Interop.Unmanaged.Win32.Enums Namespace</a><br />