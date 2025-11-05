# Cisco Network Security 1.0 - Complete Lab Command Reference

[![Live Demo](https://img.shields.io/badge/Live-Demo-success?style=for-the-badge)](https://yourusername.github.io/cisco-network-security-labs/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

A comprehensive, interactive web-based command reference guide for Cisco Network Security 1.0 course labs. This project provides network security professionals and students with essential Cisco IOS configurations covering **22 critical security labs** in a modern, easy-to-navigate interface.

## 🌟 Key Features

### 📚 Comprehensive Lab Coverage
- **22 Essential Security Labs** from Cisco Networking Academy's Network Security 1.0 course
- Detailed command syntax with clear explanations
- Real-world configuration examples for immediate application
- Security best practices and implementation strategies
- Verification commands to validate configurations

### 🎨 Modern User Interface
- **Fully Responsive Design**: Seamless experience across desktop, tablet, and mobile devices
- **Interactive Navigation**: Fixed sidebar with instant section access
- **Visual Hierarchy**: Color-coded sections and cards for easy identification
- **Smooth Scrolling**: Enhanced navigation experience between sections
- **Mobile-Optimized**: Hamburger menu and touch-friendly interface for small screens

### 🔍 Interactive Diagrams
- **Mermaid.js Network Topologies**: Visual representations of lab scenarios
- **Zoom Controls**: Zoom in/out on diagrams for detailed viewing
- **Fullscreen Mode**: Expand diagrams for comprehensive analysis
- **Reset Functionality**: Return to default view instantly

## 📋 Security Domains Covered

### 🔐 Access Control & Authentication
- **Lab 4.4.8**: Secure Passwords & SSH Configuration
  - Service password encryption and minimum length policies
  - RSA key generation and SSH version 2 implementation
  - VTY line security with local authentication
  
- **Lab 7.2.6**: Local AAA Configuration
  - AAA new-model implementation
  - Local user database setup
  - Console and VTY authentication methods
  
- **Lab 7.4.9**: Server-Based AAA (TACACS+ & RADIUS)
  - TACACS+ server configuration with encrypted packets
  - RADIUS server setup with authentication/authorization
  - Fallback mechanisms to local authentication

### 🌐 Routing Protocol Security
- **Lab 6.3.7**: OSPF MD5 Authentication
  - OSPF message-digest authentication configuration
  - Interface-level MD5 key assignment
  - Area-wide authentication enforcement
  
- **Lab 6.7.12**: Integrated Security (Syslog, NTP & SSH)
  - OSPF security integration
  - NTP authentication with MD5
  - Centralized logging configuration
  - Complete SSH hardening

### 🕐 Time Synchronization & Logging
- **Lab 6.6.4**: NTP Configuration
  - NTP server specification and authentication
  - MD5 key-based time source verification
  - Hardware clock synchronization
  - Stratum level management
  
- **Lab 6.7.12**: Syslog Integration
  - Centralized logging server setup
  - Millisecond precision timestamps
  - Log level configuration
  - Remote log transmission

### 🛡️ Traffic Filtering & ACLs

#### Standard ACLs
- **Lab 8.5.5**: Named Standard IPv4 ACLs
  - Descriptive ACL naming conventions
  - Individual entry editing capability
  - Network-based filtering

- **Lab 8.5.6**: Numbered Standard IPv4 ACLs
  - Traditional numbered ACL implementation
  - Range 1-99 and 1300-1999 usage
  - Basic permit/deny logic

#### Extended ACLs
- **Lab 8.5.12**: Extended ACLs - Scenario 1
  - Protocol-specific filtering (HTTP, HTTPS, FTP)
  - Port-based access control
  - Source and destination IP matching

- **Lab 8.5.13**: Extended ACLs - Scenario 2
  - Complex multi-host filtering scenarios
  - Service-specific restrictions
  - ICMP control implementation

#### Advanced ACL Applications
- **Lab 8.6.5**: Attack Mitigation ACLs
  - RFC 1918 private address filtering
  - Reserved/loopback address blocking
  - Fragmented packet prevention
  - Common service attack protection
  - ICMP rate limiting
  - TCP SYN flood protection

- **Lab 8.7.4**: IPv6 ACLs
  - IPv6 address format handling
  - Prefix notation implementation
  - ICMPv6 and Neighbor Discovery protection
  - IPv6-specific security considerations

### 🔥 Firewall Technologies

#### Zone-Based Policy Firewall
- **Lab 10.3.11**: ZPF Configuration
  - Security zone creation (Inside, Outside, DMZ)
  - Zone-pair policy definition
  - Class maps for traffic classification
  - Policy maps with inspect/drop actions
  - Stateful packet inspection

#### Cisco ASA Firewall
- **Lab 21.7.5**: ASA Basic Configuration
  - Initial device setup and management
  - Security level assignment (0-100)
  - NAT configuration (Dynamic PAT, Static NAT, Identity NAT)
  - Access control list implementation
  - Application layer inspection
  - DHCP service configuration

### 📊 Network Monitoring

#### Packet Analysis
- **Lab 9.2.4**: Packet Flow Analysis
  - Cisco IOS packet tracer simulation
  - Debug IP packet commands
  - NetFlow configuration and export
  - ACL logging for flow tracking
  - Interface statistics analysis
  - NAT translation verification

#### Traffic Monitoring
- **Lab 11.4.6**: Local SPAN Configuration
  - Port mirroring setup
  - Multiple source port configuration
  - VLAN-based SPAN
  - Encapsulation preservation
  - Ingress filtering options

### 🔒 Layer 2 Security

#### Port Security
- **Lab 14.3.11**: Port Security Implementation
  - MAC address limiting per port
  - Static MAC address assignment
  - Sticky MAC learning
  - Violation modes (Protect, Restrict, Shutdown)
  - Error-disabled state recovery

#### Spanning Tree Security
- **Lab 14.8.10**: STP Loop Prevention
  - BPDU Guard configuration
  - Root Guard implementation
  - Loop Guard activation
  - UDLD (UniDirectional Link Detection)
  - Topology change monitoring

- **Lab 14.9.10**: STP Security Features
  - Global and interface-level BPDU Guard
  - BPDU Filter configuration
  - Root Guard on uplinks
  - Automatic error recovery
  - Inconsistent port detection

#### VLAN Security
- **Lab 14.9.11**: Layer 2 VLAN Security
  - VLAN access maps (VACLs)
  - Private VLAN configuration (Isolated, Community, Promiscuous)
  - VLAN hopping prevention
  - Native VLAN security
  - DHCP snooping implementation
  - Dynamic ARP Inspection (DAI)

### 🔐 VPN Technologies
- **Lab 19.5.5**: Site-to-Site IPsec VPN
  - ISAKMP (IKE Phase 1) policy configuration
  - IPsec transform sets (Phase 2)
  - Crypto map creation and application
  - Pre-shared key authentication
  - Perfect Forward Secrecy (PFS)
  - Interesting traffic ACL definition
  - VPN tunnel verification commands

## 🎯 What This Guide Provides

### For Students
- **Structured Learning Path**: Follow the 22 labs in sequence or jump to specific topics
- **Command Explanations**: Understand what each command does and why it's used
- **Visual Learning**: Network diagrams illustrate lab topologies
- **Best Practices**: Learn industry-standard security implementations

### For Professionals
- **Quick Reference**: Find commands fast with organized navigation
- **Copy-Paste Ready**: Use commands directly in production environments (after testing!)
- **Troubleshooting**: Verification commands for each configuration
- **Real-World Scenarios**: Practical examples based on common security requirements

### For Certification Candidates
- **Exam Preparation**: Covers key CCNA Security and CCNP Security topics
- **Command Mastery**: All essential security commands in one place
- **Scenario-Based Learning**: Multi-step configurations that mirror exam questions
- **Verification Methods**: Learn how to validate your configurations

## 🛠️ Technical Implementation

### Technologies Used
- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern styling with Flexbox and Grid layouts
- **JavaScript (ES6+)**: Interactive features and smooth navigation
- **Tailwind CSS**: Utility-first styling framework
- **Mermaid.js**: Dynamic network topology diagrams
- **Font Awesome**: Professional iconography
- **Google Fonts**: Premium typography (Crimson Text & Inter)

### Performance Features
- **Zero Dependencies**: Runs entirely in the browser
- **Fast Loading**: Optimized assets and minimal external requests
- **Offline Capable**: Save page for offline reference
- **Print Friendly**: Styled for printing command references

## 📱 Cross-Platform Compatibility

### Desktop Experience
- Full sidebar navigation always visible
- Multi-column layouts for efficient space usage
- Interactive diagram controls
- Optimized for 1024px+ screens

### Tablet Experience
- Adaptive layouts with toggle navigation
- Touch-friendly interface elements
- Responsive grid systems
- Optimized for 768px-1023px screens

### Mobile Experience
- Hamburger menu for space efficiency
- Single-column optimized layouts
- Touch gesture support
- Fully functional on screens <768px

## 📖 Educational Purpose

This guide is designed for:
- **CCNA Security** certification preparation
- **CCNP Security** foundational knowledge
- **Network Security** course students
- **IT Security Professionals** requiring quick command reference
- **Network Administrators** implementing Cisco security solutions
- **DevOps Engineers** working with network automation

## ⚠️ Important Notes

- **Lab Environment First**: Always test in a lab before production
- **Official Documentation**: Consult Cisco docs for latest command syntax
- **Security Compliance**: Follow your organization's security policies
- **Version Awareness**: Commands may vary between IOS versions

## 📚 Additional Resources

- [Cisco Networking Academy](https://www.netacad.com/)
- [Cisco IOS Command Reference](https://www.cisco.com/c/en/us/support/ios-nx-os-software/ios-15-4m-t/products-command-reference-list.html)
- [Cisco Security Configuration Guides](https://www.cisco.com/c/en/us/support/security/index.html)
- [Original Lab Source](https://itexamanswers.net/network-security-exam-answers-version-1-0-full-labs.html)

## 🤝 Contributing

Contributions are welcome! Ways to contribute:
- Report errors or typos
- Suggest additional labs or commands
- Improve command explanations
- Enhance diagrams and visualizations
- Add troubleshooting tips
- Submit feature requests

## 📝 License

This project is licensed under the MIT License - free to use for educational purposes.

## 🌟 Acknowledgments

- **Cisco Networking Academy** for comprehensive network security education
- **Open-source community** for excellent tools and libraries
- **IT educators and students** worldwide for feedback and support

---

<div align="center">

### 🚀 [**Access the Live Guide**](https://yourusername.github.io/cisco-network-security-labs/)

**⭐ Star this repository if you find it helpful!**

*Made with 💙 for network security professionals and students worldwide*

</div>
