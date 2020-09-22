# zabbix-juniper-PPP summary
 
ZBX-JUNIPER-PPP summary
==============

This template uses the SNMP to get summary information for Point-to-Point Protocol (PPP) from JunOS devices that are support JNX-PPP-MIB.


Items
-----
  * jnxPppSummaryPppInterfaceCount - The total number of PPP interfaces configured in the system.
  * jnxPppSummaryPppIfOperUp
  * jnxPppSummaryPppIpNcpOpened
  * jnxPppSummaryPppIpv6NcpOpened
  * jnxPppSummaryPppIpNcpNoResources
  * jnxPppSummaryPppIpv6NcpNoResources

Triggers
--------
  * No IPv6 resources for PPP
  * No IPv4 resources for PPP

Graphs
------
  * jnxPppSummaryPpp

Installation
------------

1. Import **zbx-Template jnxPppSummary.xml** file into Zabbix.
2. Add to your host the **{$SNMP_COMMUNITY}** macro with your SNMP community as value.
3. Associate **Template jnxPppSummary** template to the host.

### Requirements

This template was tested for Zabbix 4.4.0 and higher.There are no additional requirements.

### Copyright

  Copyright (c) 2020 Igor Popov

License
-------
   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

### Authors

  Igor Popov
  (ipopovi |at| gmail |dot| com)
