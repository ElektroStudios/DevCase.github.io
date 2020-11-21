# IpStats Fields
 

The <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats</a> type exposes the following members.


## Fields
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_DefaultTTL">DefaultTTL</a></td><td>
The default initial time-to-live (TTL) for datagrams originating on a particular computer. 

 This member can be set to MIB_USE_CURRENT_TTL to use the current deafult TTL value when setting the forwarding and time-to-live (TTL) options using the SetIpStatistics and SetIpStatisticsEx functions.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_ForwardedDatagrams">ForwardedDatagrams</a></td><td>
The number of datagrams forwarded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_Forwarding">Forwarding</a></td><td>
Specifies whether IP forwarding is enabled or disabled for this IP protocol.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_FragmentsCreates">FragmentsCreates</a></td><td>
The number of fragments created.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_FragmentsFails">FragmentsFails</a></td><td>
The number of datagrams that have not been fragmented because the IP header specifies no fragmentation. These datagrams are discarded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_FragmentsOks">FragmentsOks</a></td><td>
The number of datagrams that were fragmented successfully.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_InAddressErrors">InAddressErrors</a></td><td>
The number of datagrams received that have address errors.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_InDelivers">InDelivers</a></td><td>
The number of received datagrams delivered.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_InDiscards">InDiscards</a></td><td>
The number of received datagrams discarded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_InHeaderErrors">InHeaderErrors</a></td><td>
The number of datagrams received that have header errors.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_InReceives">InReceives</a></td><td>
The number of datagrams received.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_InUnknownProtocols">InUnknownProtocols</a></td><td>
The number of datagrams received that have an unknown protocol.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_NumAddresses">NumAddresses</a></td><td>
The number of IP addresses associated with this computer.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_NumInterfaces">NumInterfaces</a></td><td>
The number of interfaces.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_NumRoutes">NumRoutes</a></td><td>
The number of routes in the IP routing table.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_OutDiscards">OutDiscards</a></td><td>
The number of transmitted datagrams discarded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_OutNoRoutes">OutNoRoutes</a></td><td>
The number of datagrams for which this computer did not have a route to the destination IP address. These datagrams were discarded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_OutRequests">OutRequests</a></td><td>
The number of outgoing datagrams that IP is requested to transmit. This number does not include forwarded datagrams.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_ReassemblyFails">ReassemblyFails</a></td><td>
The number of datagrams that cannot be reassembled.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_ReassemblyOks">ReassemblyOks</a></td><td>
The number of datagrams that were successfully reassembled.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_ReassemblyRequired">ReassemblyRequired</a></td><td>
The number of datagrams that require re-assembly.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_ReassemblyTimeout">ReassemblyTimeout</a></td><td>
The amount of time allowed for all pieces of a fragmented datagram to arrive. 

 If all pieces do not arrive within this time, the datagram is discarded.</td></tr><tr><td>![Public field](media/pubfield.gif "Public field")</td><td><a href="F_DevCase_Interop_Unmanaged_Win32_Structures_IpStats_RoutingDiscards">RoutingDiscards</a></td><td>
The number of outgoing datagrams discarded.</td></tr></table>&nbsp;
<a href="#ipstats-fields">Back to Top</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IpStats">IpStats Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />