# [Distributed File System Replication](distributed-file-system-replication--dfsr-.md)
## [About DFSR](about-dfsr.md)
### [What's New](what-s-new.md)
#### [What's New in DFSR in Windows Server 2008 R2](what-s-new-in-dfsr-in-windows-server-2008-r2-and-windows-7.md)
### [DFSR Overview](dfsr-overview.md)
### [DFSR Security Model](dfsr-security-model.md)
### [DFSR Replicated Folders](dfsr-replicated-folders.md)
### [DFSR WMI Provider Overview](dfsr-wmi-provider-overview.md)
### [DFSR Configuration Modes](configuring-dfsr.md)
### [Monitoring DFSR](monitoring-dfsr.md)
## [Using DFSR](using-the-dfsr-wmi-provider.md)
### [Polling the Active Directory for Configuration Changes](polling-the-active-directory-for-configuration-changes.md)
### [Displaying and Changing DFSR Local Computer Settings](displaying-and-changing-dfsr-machine-configuration-settings.md)
### [Getting the ID Record for a File or Folder](getting-the-id-record-for-a-file-or-folder.md)
### [Getting Replication Backlog Information](getting-replication-backlog-information.md)
### [Finding the Server that Originated a File or Folder Update](finding-the-server-that-originated-a-file-or-folder-update.md)
## [DFSR WMI Classes](dfsr-wmi-classes.md)
### [CONFIG_STATUS Return Codes](config-status-return-codes.md)
### [MONITOR_STATUS Return Codes](monitor-status-return-codes.md)
### [DfsrConfig](dfsrconfig.md)
#### [PollDsNow method](polldsnow-dfsrconfig.md)
### [DfsrConflictInfo](dfsrconflictinfo.md)
#### [Delete method](delete-dfsrconflictinfo.md)
### [DfsrConnectionConfig](dfsrconnectionconfig.md)
### [DfsrConnectionInfo](dfsrconnectioninfo.md)
#### [CheckConnectivity method](checkconnectivity-dfsrconnectioninfo.md)
#### [ForceDownload method](forcedownload-dfsrconnectioninfo.md)
#### [ForceFolderReplication method](forcefolderreplication-dfsrconnectioninfo.md)
#### [ForceReplication method](forcereplication-dfsrconnectioninfo.md)
### [DfsrIdRecordInfo](dfsridrecordinfo.md)
#### [GetFullFilePath method](getfullfilepath-dfsridrecordinfo.md)
### [DfsrIdUpdateInfo](dfsridupdateinfo.md)
### [DfsrInfo](dfsrinfo.md)
### [DfsrLocalMemberConfig](dfsrlocalmemberconfig.md)
### [DfsrLocalMemberInfo](dfsrlocalmemberinfo.md)
### [DfsrMachineConfig](dfsrmachineconfig.md)
### [DfsrReplicatedFolderConfig](dfsrreplicatedfolderconfig.md)
#### [Offline method](dfsrreplicatedfolderconfig-offline.md)
#### [Online method](dfsrreplicatedfolderconfig-online.md)
### [DfsrReplicatedFolderInfo](dfsrreplicatedfolderinfo.md)
#### [CleanupConflictDirectory method](cleanupconflictdirectory-dfsrreplicatedfolderinfo.md)
#### [Fence method](fence-dfsrreplicatedfolderinfo.md)
#### [GetOutboundBacklogFileCount method](getoutboundbacklogfilecount-dfsrreplicatedfolderinfo.md)
#### [GetOutboundBacklogFileIdRecords method](getoutboundbacklogfileidrecords-dfsrreplicatedfolderinfo.md)
#### [GetStatus method](dfsrreplicatedfolderinfo-getstatus.md)
#### [GetVersionVector method](getversionvector-dfsrreplicatedfolderinfo.md)
### [DfsrReplicationGroupConfig](dfsrreplicationgroupconfig.md)
### [DfsrSyncInfo](dfsrsyncinfo.md)
### [DfsrVolumeConfig](dfsrvolumeconfig.md)
#### [ResumeReplication method](resumereplication-dfsrvolumeconfig.md)
### [DfsrVolumeInfo](dfsrvolumeinfo.md)
### [MSFT_DfsrConflictInfo](msft-dfsrconflictinfo.md)
#### [DeleteConflict method](deleteconflict-msft-dfsrconflictinfo.md)
### [MSFT_DfsrConnectionConfig](msft-dfsrconnectionconfig.md)
### [MSFT_DfsrConnectionInfo](msft-dfsrconnectioninfo.md)
#### [ForceReplication method](forcereplication-msft-dfsrconnectioninfo.md)
#### [ForceFolderReplication method](forcefolderreplication-msft-dfsrconnectioninfo.md)
#### [ForceDownload method](forcedownload-msft-dfsrconnectioninfo.md)
#### [CheckConnectivity method](checkconnectivity-msft-dfsrconnectioninfo.md)
### [MSFT_DfsrIdRecordInfo](msft-dfsridrecordinfo.md)
#### [GetFullFilePath method](getfullfilepath-msft-dfsridrecordinfo.md)
#### [GetIdRecordByPath method](msft-dfsridrecordinfo-getidrecordbypath.md)
### [MSFT_DfsrIdUpdateInfo](msft-dfsridupdateinfo.md)
### [MSFT_DfsrLocalMemberConfig](msft-dfsrlocalmemberconfig.md)
### [MSFT_DfsrLocalMemberInfo](msft-dfsrlocalmemberinfo.md)
### [MSFT_DfsrMachineConfig](msft-dfsrmachineconfig.md)
### [MSFT_DfsrReplicatedFolderConfig](msft-dfsrreplicatedfolderconfig.md)
#### [Offline method](offline-msft-dfsrreplicatedfolderconfig.md)
#### [Online method](online-msft-dfsrreplicatedfolderconfig.md)
### [MSFT_DfsrReplicatedFolderInfo](msft-dfsrreplicatedfolderinfo.md)
#### [GetVersionVector method](getversionvector-msft-dfsrreplicatedfolderinfo.md)
#### [CleanupConflictDirectory method](cleanupconflictdirectory-msft-dfsrreplicatedfolderinfo.md)
#### [GetOutboundBacklogFileCount method](getoutboundbacklogfilecount-msft-dfsrreplicatedfolderinfo.md)
#### [GetOutboundBacklogFileIdRecords method](getoutboundbacklogfileidrecords-msft-dfsrreplicatedfolderinfo.md)
#### [Fence method](fence-msft-dfsrreplicatedfolderinfo.md)
#### [GetStatus method](getstatus-msft-dfsrreplicatedfolderinfo.md)
### [MSFT_DfsrReplicationGroupConfig](msft-dfsrreplicationgroupconfig.md)
### [MSFT_DfsrServiceConfig](msft-dfsrserviceconfig.md)
#### [PollDsNow method](polldsnow-msft-dfsrserviceconfig.md)
### [MSFT_DfsrServiceInfo](msft-dfsrserviceinfo.md)
### [MSFT_DfsrSyncInfo](msft-dfsrsyncinfo.md)
### [MSFT_DfsrVolumeConfig](msft-dfsrvolumeconfig.md)
#### [ExportDBClone method](msft-dfsrvolumeconfig-exportdbclone.md)
#### [GetDBCloneState method](msft-dfsrvolumeconfig-getdbclonestate.md)
#### [ImportDBClone method](msft-dfsrvolumeconfig-importdbclone.md)
#### [ResetDBClone method](msft-dfsrvolumeconfig-resetdbclone.md)
#### [ResumeReplication method](resumereplication-msft-dfsrvolumeconfig.md)
### [MSFT_DfsrVolumeInfo](msft-dfsrvolumeinfo.md)
## [DFSR Glossary](dfsr-glossary.md)
