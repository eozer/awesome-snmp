<!--lint disable double-link-->
# Awesome SNMP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!-- TODO: Enable the badge when the repository is mature enough, older than 30 days. -->
<!-- [![Awesome lint](https://github.com/eozer/awesome-snmp/actions/workflows/awesome-lint.yml/badge.svg)](https://github.com/eozer/awesome-snmp/actions/workflows/awesome-lint.yml) -->

Simple Network Management Protocol (SNMP) is an Internet Standard protocol for collecting and organizing information about managed devices on IP networks and for modifying that information to change device behaviour.

This is a curated list of awesome SNMP libraries, tools, and other resources. Contributions are welcome!


## Contents
- [Libraries](#libraries)
- [Tools](#tools)
- [Publications](#publications)
- [Miscellaneous](#miscellaneous)

## Libraries
_Helpful to write SNMP applications._

### C/C++
- [net-snmp](http://www.net-snmp.org/) - A suite of software for using and deploying the SNMP protocol (v1, v2c and v3 and the AgentX subagent protocol). Contains also Python bindings.
- [SNMP++](https://www.agentpp.com/api/cpp/snmp_pp.html) - BSD licensed SNMP implemention from HP. Supports SNMP v1/2c/v3, thread-safety, and many more.
- [AGENT++](https://www.agentpp.com/api/cpp/agent_pp.html) - The AGENT++ C++ framework provides a complete tri-lingual SNMP v1/2c/3 protocol engine and dispatcher for the development of SNMP agents. Apache licensed.
- [AgentX++](https://www.agentpp.com/api/cpp/agentx_pp.html) - The AgentX++ C++ framework provides a complete AgentX protocol (RFC 2741) implementation that adds AgentX master and sub-agent support to AGENT++ (`Commercial`).
### Go
- [gosnmp/gosnmp](https://github.com/gosnmp/gosnmp)

### Java
- [SNMP4J](https://www.agentpp.com/api/java/snmp4j.html) - SNMP4J is an enterprise class, free open source, and state-of-the-art SNMP v1/2c/v3 implementation for Java™.
- [SNMP4J-Agent](https://www.agentpp.com/api/java/snmp4jagent.html) - SNMP4J-Agent is a Java™ API on top of the core SNMP4J API for the development of SNMP agents (command responders).

### JavaScript
- [node-snmp-native](https://github.com/calmh/node-snmp-native) -  Native JavaScript SNMP library for Node.js.
- [node-snmpjs](https://github.com/joyent/node-snmpjs) - This package provides a toolkit for SNMP agents and management applications in Node.js.
- [snmp-node](https://github.com/neias/snmp-node) - Native JavaScript SNMP library for Node.js.

**[⬆ back to top](#contents)**

## Tools
_You use these to work with SNMP easier._

### CLIs
- [encode_keychange](http://www.net-snmp.org/) - Produces the KeyChange string for SNMPv3 (part of net-snmp).
- [snmptranslate](http://www.net-snmp.org/) - Translates MIB OID names between numeric and textual forms (part of net-snmp).
- [snmpget](http://www.net-snmp.org/) - Communicates with a network entity using SNMP GET requests (part of net-snmp).
- [snmpgetnext](http://www.net-snmp.org/) - Communicates with a network entity using SNMP GETNEXT requests (part of net-snmp).
- [snmpbulkget](http://www.net-snmp.org/) - Communicates with a network entity using SNMP GETBULK requests (part of net-snmp).
- [snmpwalk](http://www.net-snmp.org/) - Retrieves a subtree of management values using SNMP GETNEXT requests (part of net-snmp).
- [snmpbulkwalk](http://www.net-snmp.org/) - Retrieves a subtree of management values using SNMP GETBULK requests (part of net-snmp).
- [snmpset](http://www.net-snmp.org/) - Communicates with a network entity using SNMP SET requests (part of net-snmp).
- [snmptrap](http://www.net-snmp.org/) - Sends SNMP TRAP or INFORM notification messages (part of net-snmp).
- [snmpd](http://www.net-snmp.org/) - An SNMP agent that responds to SNMP requests for a given host (part of net-snmp).
- [snmptrapd](http://www.net-snmp.org/) - An SNMP daemon that listens for SNMP TRAPs or INFORMs and logs or acts upon them (part of net-snmp).
- [snmptest](http://www.net-snmp.org/) - Communicates with a network entity using SNMP requests (part of net-snmp).
- [snmpusm](http://www.net-snmp.org/) - Manipulates the SNMPv3 User-based-security user table (part of net-snmp).
- [snmpvacm](http://www.net-snmp.org/) - Manipulates the SNMPv3 View-based-access-control-module configuration tables (part of net-snmp).
- [snmpdf](http://www.net-snmp.org/) - Displays disk information like the unix df tool using information collected from SNMP (part of net-snmp).
- [mib2c](http://www.net-snmp.org/) - A MIB conversion utility that can translate MIB structures into other forms, such as C-code (part of net-snmp).
- [SNMP4JCLT](https://www.agentpp.com/tools/snmp4jclt.html) - Use the SNMP4J Command Line Tool (CLT) to send SNMPv1/v2c/v3 requests and traps to a target with IPv4 or v6 based UDP, TCP, or TLSv1,2 transport (`Commercial`).

### GUIs
- [tkmib](http://www.net-snmp.org/) - A perl/Tk interactive graphical MIB browser for SNMP.
- [MIB Designer](https://www.agentpp.com/tools/mibdesigner.html) - Use MIB Designer to create, edit, manage, and explore SMI specifications (`Commercial`).
- [MIB Explorer Pro](https://www.agentpp.com/tools/mibexplorer.html) - Use MIB Explorer to browse, configure, test&debug, monitor, and discover SNMPv1/2c/3 entities.

**[⬆ back to top](#contents)**

## Publications
_How-to's, tutorials, blog posts, documentation and books._

### RFCs
- [rfc1098](https://tools.ietf.org/rfc/rfc1098.txt) - A Simple Network Management Protocol (version 1).
- [rfc1155](https://tools.ietf.org/rfc/rfc1155.txt) - Structure and Identification of Management Information.
- [rfc2578](https://tools.ietf.org/rfc/rfc2578.txt) - Structure of Management Information Version 2 (SMIv2).
- [rfc2741](https://tools.ietf.org/rfc/rfc2741.txt) - Agent Extensibility (AgentX) Protocol Version 1.
- [rfc2742](https://tools.ietf.org/rfc/rfc2742.txt) - Definitions of Managed Objects for Extensible SNMP Agents.
- [rfc3410](https://tools.ietf.org/rfc/rfc3410.txt) - Introduction and Applicability Statements for Internet Standard Management Framework.
- [rfc3411](https://tools.ietf.org/rfc/rfc3411.txt) - An Architecture for Describing Simple Network Management Protocol (SNMP) Management Frameworks.
- [rfc3412](https://tools.ietf.org/rfc/rfc3412.txt) - Message Processing and Dispatching for the Simple Network Management Protocol (SNMP).
- [rfc3413](https://tools.ietf.org/rfc/rfc3413.txt) - Simple Network Management Protocol (SNMP) Applications.
- [rfc3414](https://tools.ietf.org/rfc/rfc3414.txt) - User-based Security Model (USM) for version 3 of the
 Simple Network Management Protocol (SNMPv3).
- [rfc3415](https://tools.ietf.org/rfc/rfc3415.txt) - View-based Access Control Model (VACM) for the Simple Network Management Protocol (SNMP).
- [rfc3416](https://tools.ietf.org/rfc/rfc3416.txt) - Version 2 of the Protocol Operations for the Simple
Network Management Protocol (SNMP).
- [rfc3417](https://tools.ietf.org/rfc/rfc3417.txt) - Transport Mappings for the Simple Network Management
Protocol (SNMP).
- [rfc3418](https://www.ietf.org/rfc/rfc3418.txt) - Management Information Base (MIB) for the Simple Network Management Protocol (SNMP).
- [rfc3584](https://tools.ietf.org/rfc/rfc3584.txt) - Coexistence between Version 1, Version 2, and Version 3 of the Internet-standard Network Management Framework.
- [rfc3826](https://tools.ietf.org/rfc/rfc3826.txt) - The Advanced Encryption Standard (AES) Cipher Algorithm
in the SNMP User-based Security Model.
- [rfc4088](https://tools.ietf.org/rfc/rfc4088.txt) - Uniform Resource Identifier (URI) Scheme for the Simple Network Management Protocol (SNMP).
- [rfc5343](https://www.rfc-editor.org/rfc/rfc5343.txt) - Simple Network Management Protocol (SNMP) Context EngineID Discovery.
- [rfc5590](https://www.rfc-editor.org/rfc/rfc5590.txt) - Transport Subsystem for the Simple Network Management Protocol (SNMP).
- [rfc5591](https://www.rfc-editor.org/rfc/rfc5591.txt) - Transport Subsystem for the Simple Network Management Protocol (SNMP).
- [rfc5592](https://www.rfc-editor.org/rfc/rfc5592.txt) - Secure Shell Transport Model for the Simple Network Management Protocol (SNMP).
- [rfc7630](https://www.rfc-editor.org/rfc/rfc7630.txt) - HMAC-SHA-2 Authentication Protocols in the User-based Security Model (USM) for SNMPv3.

**[⬆ back to top](#contents)**

## Miscellaneous
_Items that belong on the list but difficult to classify._

**[⬆ back to top](#contents)**

## Contributing
Please take a quick look at the [contribution guidelines](contributing.md) first. Thank you to all contributors.

