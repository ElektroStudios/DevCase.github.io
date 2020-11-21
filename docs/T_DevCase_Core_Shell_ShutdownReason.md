# ShutdownReason Enumeration
 

Specifies a shutdown/restart reason.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum ShutdownReason
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration ShutdownReason
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShutdownReason
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class ShutdownReason
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type ShutdownReason
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.Other">**Other**</td><td>0</td><td>Other issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MajorApplication">**MajorApplication**</td><td>262144</td><td>Application issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MajorHardware">**MajorHardware**</td><td>65536</td><td>Hardware issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MajorOperatingSystem">**MajorOperatingSystem**</td><td>131072</td><td>Operating system issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MajorPower">**MajorPower**</td><td>393216</td><td>Power failure.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MajorSoftware">**MajorSoftware**</td><td>196608</td><td>Software issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MajorSystem">**MajorSystem**</td><td>327680</td><td>System failure..</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorBlueScreen">**MinorBlueScreen**</td><td>15</td><td>Blue screen crash event.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorCordUnplugged">**MinorCordUnplugged**</td><td>11</td><td>Unplugged.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorDisk">**MinorDisk**</td><td>7</td><td>Disk.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorEnvironment">**MinorEnvironment**</td><td>12</td><td>Environment.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorHardwareDriver">**MinorHardwareDriver**</td><td>13</td><td>Driver.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorHotfix">**MinorHotfix**</td><td>17</td><td>Hot fix.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorHotfixUninstall">**MinorHotfixUninstall**</td><td>23</td><td>Hot fix uninstallation.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorHung">**MinorHung**</td><td>5</td><td>Unresponsive.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorInstallation">**MinorInstallation**</td><td>2</td><td>Installation.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorMaintenance">**MinorMaintenance**</td><td>1</td><td>Maintenance.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorMmc">**MinorMmc**</td><td>25</td><td>MMC issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorNetworkConnectivity">**MinorNetworkConnectivity**</td><td>20</td><td>Network connectivity.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorNetworkCard">**MinorNetworkCard**</td><td>9</td><td>Network card.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorOtherDriver">**MinorOtherDriver**</td><td>14</td><td>Other driver event.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorPowerSupply">**MinorPowerSupply**</td><td>10</td><td>Power supply.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorProcessor">**MinorProcessor**</td><td>8</td><td>Processor.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorReconfig">**MinorReconfig**</td><td>4</td><td>Reconfigure.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorSecurity">**MinorSecurity**</td><td>19</td><td>Security issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorSecurityFix">**MinorSecurityFix**</td><td>18</td><td>Security patch.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorSecurityFixUninstall">**MinorSecurityFixUninstall**</td><td>24</td><td>Security patch uninstallation.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorServicePack">**MinorServicePack**</td><td>16</td><td>Service pack.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorServicePackUninstall">**MinorServicePackUninstall**</td><td>22</td><td>Service pack uninstallation.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorTermSrv">**MinorTermSrv**</td><td>32</td><td>Terminal Services.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorUnstable">**MinorUnstable**</td><td>6</td><td>Unstable.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorUpgrade">**MinorUpgrade**</td><td>3</td><td>Upgrade.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.MinorWmi">**MinorWmi**</td><td>21</td><td>WMI issue.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.FagUserDefined">**FagUserDefined**</td><td>1073741824</td><td>The reason code is defined by the user. 

 If this flag is not present, the reason code is defined by the system.</td></tr><tr><td /><td target="F:DevCase.Core.Shell.ShutdownReason.FagUserPlanned">**FagUserPlanned**</td><td>2147483648</td><td>The shutdown was planned. 

 The system generates a System State Data (SSD) file. This file contains system state information such as the processes, threads, memory usage, and configuration. 

 If this flag is not present, the shutdown was unplanned. 

 Notification and reporting options are controlled by a set of policies. For example, after logging in, the system displays a dialog box reporting the unplanned shutdown if the policy has been enabled. 

 An SSD file is created only if the SSD policy is enabled on the system.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />