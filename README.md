# 🎯 Volatility3-Velociraptor-Artifacts

[![GitHub stars](https://img.shields.io/github/stars/aminemoussaa/Volatility-3?style=social)](https://github.com/aminemoussaa/Volatility-3)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/aminemoussaa/Volatility-3)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/aminemoussaa/Volatility-3/graphs/commit-activity)

<div align="center">
  <img src="https://raw.githubusercontent.com/socfortress/CoPilot/main/frontend/src/assets/images/socfortress_logo.svg" width="200" height="150" alt="SOCFortress Logo">
  <h3>Complete Collection of 44 Production-Ready Velociraptor Artifacts for Volatility 3 Memory Forensics</h3>
  <p><em>Created by Amine Moussa for SOCFortress | Based on SOCFortress Volatility 3 Ultimate Memory Forensics Cheatsheet</em></p>
</div>

---

## 🚀 What is this?

**Volatility3-Velociraptor-Artifacts** is a comprehensive, battle-tested collection of 44 Velociraptor artifacts that wrap every Volatility 3 plugin from the SOCFortress Ultimate Memory Forensics Cheatsheet. Each artifact is a self-contained YAML file that enables seamless integration of Volatility 3's powerful memory analysis capabilities directly into your Velociraptor deployments.

**No coding required** - just upload the YAML files to your Velociraptor server and start analyzing memory dumps immediately!

## 💡 Why use this?

This collection saves security teams **hours of manual artifact development** by providing:

- ✅ **Complete Coverage**: All 44 artifacts from the SOCFortress cheatsheet, covering every major forensics category
- ✅ **Production-Ready**: Battle-tested artifacts used in real-world investigations
- ✅ **Zero Configuration**: Pre-built YAML files with proper parameter validation and documentation
- ✅ **Community-Driven**: Free for the security community, maintained by SOCFortress experts
- ✅ **Cross-Platform**: Works with any Volatility 3 installation on Windows, Linux, or macOS
- ✅ **Comprehensive Documentation**: Each artifact includes detailed descriptions and usage examples
- ✅ **Regular Updates**: Kept current with latest Volatility 3 releases and Velociraptor features

## 🎯 Features

- **44 Complete Artifacts** - Every plugin from the SOCFortress cheatsheet wrapped as Velociraptor artifacts
- **Self-Contained YAMLs** - Each file is independent and fully documented
- **Parameter Validation** - Proper input validation and error handling
- **Multiple Output Formats** - Support for pretty, CSV, JSON, and JSONL outputs
- **Memory Dump Flexibility** - Works with raw dumps, crash dumps, and hibernation files
- **Windows Support** - Compatible with Windows XP through Windows 11
- **Investigation Workflows** - Specialized artifacts for malware, rootkit, and ransomware analysis
- **Community Support** - Active maintenance and community contributions welcome

## 📦 What's Included

This repository contains **all 44 artifacts** as individual `.yaml` files, organized by forensic category:

### 🔍 Quick Start & System Information
- `Custom.Windows.Volatility3.WindowsInfo` - Basic system information (OS, kernel, architecture)
- `Custom.Windows.Volatility3.QuickStartBundle` - Essential initial triage data

### 👥 Process Analysis
- `Custom.Windows.Volatility3.PsList` - Active process listing
- `Custom.Windows.Volatility3.PsScan` - Scan for hidden processes
- `Custom.Windows.Volatility3.PsTree` - Process tree with relationships
- `Custom.Windows.Volatility3.PsXView` - Cross-reference process visibility
- `Custom.Windows.Volatility3.Malfind` - Detect injected code and hollowing
- `Custom.Windows.Volatility3.VadInfo` - Virtual Address Descriptor analysis
- `Custom.Windows.Volatility3.MemMap` - Process memory mapping
- `Custom.Windows.Volatility3.Privileges` - Process privileges and tokens
- `Custom.Windows.Volatility3.GetSIDs` - Security identifiers
- `Custom.Windows.Volatility3.CmdLine` - Command line arguments
- `Custom.Windows.Volatility3.Envars` - Environment variables
- `Custom.Windows.Volatility3.LdrModules` - Loaded DLL analysis
- `Custom.Windows.Volatility3.HollowProcesses` - Process hollowing detection
- `Custom.Windows.Volatility3.SuspiciousThreads` - Thread analysis

### 🌐 Network Analysis
- `Custom.Windows.Volatility3.NetScan` - Network connection scanning
- `Custom.Windows.Volatility3.NetStat` - Active network connections

### 📁 Registry Analysis
- `Custom.Windows.Volatility3.HiveList` - Registry hive enumeration
- `Custom.Windows.Volatility3.PrintKey` - Registry key inspection
- `Custom.Windows.Volatility3.UserAssist` - UserAssist execution history
- `Custom.Windows.Volatility3.ShimCache` - ShimCache artifacts
- `Custom.Windows.Volatility3.AmCache` - AmCache execution data
- `Custom.Windows.Volatility3.ScheduledTasks` - Scheduled task analysis

### 🛡️ Kernel & Rootkit Detection
- `Custom.Windows.Volatility3.Modules` - Kernel module analysis
- `Custom.Windows.Volatility3.DriverScan` - Driver scanning
- `Custom.Windows.Volatility3.DriverModule` - Driver module details
- `Custom.Windows.Volatility3.Callbacks` - Kernel callbacks
- `Custom.Windows.Volatility3.DeviceTree` - Device tree structure
- `Custom.Windows.Volatility3.SSDT` - System Service Descriptor Table

### 🔎 Scanning & Enumeration
- `Custom.Windows.Volatility3.SvcScan` - Service scanning
- `Custom.Windows.Volatility3.MutantScan` - Mutex scanning
- `Custom.Windows.Volatility3.FileScan` - File object scanning
- `Custom.Windows.Volatility3.DumpFiles` - File dumping from memory
- `Custom.Windows.Volatility3.Timeliner` - Timeline creation

### 🕵️ Hidden Asset Detection
- `Custom.Windows.Volatility3.FindHiddenProcesses` - Hidden process discovery
- `Custom.Windows.Volatility3.FindHiddenDrivers` - Hidden driver detection

### ⚡ Specialized Workflows
- `Custom.Windows.Volatility3.RootkitWorkflow` - Automated rootkit investigation
- `Custom.Windows.Volatility3.MalwareWorkflow` - Malware analysis workflow
- `Custom.Windows.Volatility3.RansomwareWorkflow` - Ransomware investigation
- `Custom.Windows.Volatility3.CompleteTriageReport` - Full triage report
- `Custom.Windows.Volatility3.MasterCollection` - Configurable master collection

## 🚀 Quick Start

### Prerequisites
- Velociraptor server (v0.6.8+ recommended)
- Volatility 3 installed on Velociraptor clients
- Memory dump file (`.dmp`, `.raw`, or hibernation file)

### Installation

1. **Clone or Download** this repository:
   ```bash
   git clone https://github.com/aminemoussaa/Volatility-3.git
   cd Volatility-3
   ```

2. **Upload Artifacts to Velociraptor**:
   - Go to **View Artifacts** → **Upload Custom Artifact**
   - Select and upload the desired `.yaml` files
   - Or upload all 44 files for complete coverage

3. **Configure Memory Dump Path**:
   - Set the `MemoryDumpPath` parameter to your memory dump location
   - Example: `C:\MemoryDumps\incident.dmp`

4. **Run Your First Artifact**:
   - Search for `Custom.Windows.Volatility3.WindowsInfo`
   - Click **Launch** and monitor the results

## 🏗️ Architecture

### Design Philosophy
- **Modularity**: Each artifact is self-contained and can be used independently
- **Consistency**: Standardized parameter naming and validation across all artifacts
- **Flexibility**: Support for multiple output formats and filtering options
- **Reliability**: Comprehensive error handling and input validation
- **Documentation**: Inline documentation in each YAML file

### Artifact Structure
Each YAML file follows this structure:
```yaml
name: Custom.Windows.Volatility3.PluginName
description: |
  Detailed description of the artifact's purpose
  and what Volatility 3 plugin it wraps
author: amine
type: CLIENT
parameters:
  - name: MemoryDumpPath
    type: string
    description: Path to memory dump file
  # ... additional parameters
```

### Integration with Volatility 3
- Artifacts use the `execve` function to call Volatility 3
- Automatic path resolution for `vol.py`
- Parameter passing with proper escaping
- Output parsing and formatting for Velociraptor

## 🤝 Contributing

We welcome contributions from the security community!

### How to Contribute
1. **Fork** this repository
2. **Create** a feature branch: `git checkout -b feature/new-artifact`
3. **Add** your artifact following the naming convention
4. **Test** thoroughly with sample memory dumps
5. **Document** parameters and expected outputs
6. **Submit** a pull request with a detailed description

### Guidelines
- Follow the existing naming convention: `Custom.Windows.Volatility3.PluginName`
- Include comprehensive descriptions and examples
- Test with multiple Windows versions when possible
- Update this README if adding new categories
- Ensure artifacts work with latest Volatility 3 releases

### Testing
- Test with sample memory dumps from different Windows versions
- Verify parameter validation works correctly
- Check output formatting in all supported formats
- Ensure artifacts handle edge cases gracefully

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

The MIT License allows for:
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ✅ No liability or warranty requirements

## 🙏 Credits

### Created By
**Amine Moussa** - SOCFortress Security Engineer

### Based On
- **SOCFortress Volatility 3 Ultimate Memory Forensics Cheatsheet**
- **Volatility Foundation** - For the excellent Volatility 3 framework
- **Velociraptor** by Rapid7 - For the powerful digital forensics platform

### Contributors
- SOCFortress Team

### Acknowledgments
Special thanks to the digital forensics community for their continuous innovation and sharing of knowledge. This collection builds upon years of collective expertise in memory forensics.

---

<div align="center">
  <strong>🔒 Secure your systems with SOCFortress solutions</strong><br>
  <a href="https://www.socfortress.co">SOCFortress Website</a> |
  <a href="https://discord.gg/UN3pNBzaEQ">Join our Discord</a> |
  <a href="https://socfortress.medium.com/">Read our Blog</a>
</div>





