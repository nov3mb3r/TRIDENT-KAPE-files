# TRIDENT-KapeFiles
A list of KAPE modules that were ported from TRIDENT project. More information on KAPE can be found on its official documentation page: https://ericzimmerman.github.io/KapeDocs/#!index.md

The processed artifacts will be stored in each file respectively
### Network (net.txt)
| Artifact | KapeFile |
| --- | --- |
| Active network interfaces | PowerShell_Network_Adapters.mkape |
| Connections by spawned processes | PowerShell_Net_ProcessList.mkape |
| DNS cache | PowerShell_DNSCache.mkape | 


### Process Information (process.txt)
| Artifact | KapeFile |
| --- | --- |
| Running processes | PowerShell_ProcessInfo.mkape & PowerShell_PSList.mkape |
| Process commandline | PowerShell_Process_Cmdline.mkape |

### Persistence (persistence.txt)
| Artifact | KapeFile |
| --- | --- |
| Commands on Startup | PowerShell_Startup_Commands.mkape |
| Scheduled tasks | PowerShell_Schtasks.mkape |

### User account activity (user_activity.txt)
| Artifact | KapeFile |
| --- | --- |
| Recent files | PowerShell_Recent_Files.mkape |
| Kerberos sessions | PowerShell_KRB_Sessions.mkape |
| SMB sessions | PowerShell_SMB_Sessions.mkape
| RDP sessions | PowerShell_RDP_Sessions.mkape |

### WMI (wmi.txt)
| Artifact | KapeFile |
| --- | --- |
| Consumers | PowerShell_WMI_Consumers.mkape
| Filters | PowerShell_WMI_Filters.mkape
| General Info | PowerShell_WMI_Instances.mkape

### Advanced (advanced.txt)
| Artifact | KapeFile |
| --- | --- |
| DLL List | PowerShell_DLL_Llist.mkape |
| Named Pipes | PowerShell_NamedPipes.mkape |
| Windows Defender Exclusions | PowerShell_Defender_Exclusions.mkape |
| Total process count | PowerShell_Total_Processes.mkape |







