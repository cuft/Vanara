﻿![Vanara](https://raw.githubusercontent.com/dahall/Vanara/master/docs/icons/VanaraHeading.png)
### **Vanara.PInvoke.NetApi32 NuGet Package**
[![Version](https://img.shields.io/nuget/v/Vanara.PInvoke.NetApi32?label=NuGet&style=flat-square)](https://github.com/dahall/Vanara/releases)
[![Build status](https://img.shields.io/appveyor/build/dahall/vanara?label=AppVeyor%20build&style=flat-square)](https://ci.appveyor.com/project/dahall/vanara)

PInvoke API (methods, structures and constants) imported from Windows NetApi32.dll.

### **What is Vanara?**

[Vanara](https://github.com/dahall/Vanara) is a community project that contains various .NET assemblies which have P/Invoke functions, interfaces, enums and structures from Windows libraries. Each assembly is associated with one or a few tightly related libraries.

### **Issues?**

First check if it's already fixed by trying the [AppVeyor build](https://ci.appveyor.com/nuget/vanara-prerelease).
If you're still running into problems, file an [issue](https://github.com/dahall/Vanara/issues).

### **Included in Vanara.PInvoke.NetApi32**

Functions | Enumerations | Structures
--- | --- | ---
DavAddConnection DavCancelConnectionsToServer DavDeleteConnection DavFlushFile DavGetExtendedError DavGetHTTPFromUNCPath DavGetTheLockOwnerOfTheFile DavGetUNCFromHTTPPath DavInvalidateCache DavRegisterAuthCallback DavUnregisterAuthCallback DsAddressToSiteNames DsAddressToSiteNamesEx DsDeregisterDnsHostRecords DsEnumerateDomainTrusts DsGetDcCloseW DsGetDcName DsGetDcNext DsGetDcOpen DsGetDcSiteCoverage DsGetForestTrustInformationW DsGetSiteName DsMergeForestTrustInformationW DsRoleFreeMemory DsRoleGetPrimaryDomainInformation DsValidateSubnetName NetAddAlternateComputerName NetAddServiceAccount NetAlertRaise NetAlertRaiseEx NetApiBufferAllocate NetApiBufferFree NetApiBufferReallocate NetApiBufferSize NetConnectionEnum NetCreateProvisioningPackage NetDfsAdd NetDfsAddFtRoot NetDfsAddRootTarget NetDfsAddStdRoot NetDfsAddStdRootForced NetDfsEnum NetDfsGetClientInfo NetDfsGetFtContainerSecurity NetDfsGetInfo NetDfsGetSecurity NetDfsGetStdContainerSecurity NetDfsGetSupportedNamespaceVersion NetDfsMove NetDfsRemove NetDfsRemoveFtRoot NetDfsRemoveFtRootForced NetDfsRemoveRootTarget NetDfsRemoveStdRoot NetDfsSetClientInfo NetDfsSetFtContainerSecurity NetDfsSetInfo NetDfsSetSecurity NetDfsSetStdContainerSecurity NetEnumerateComputerNames NetEnumerateServiceAccounts NetFileClose NetFileEnum NetFileGetInfo NetFreeAadJoinInformation NetGetAadJoinInformation NetGetAnyDCName NetGetDCName NetGetDisplayInformationIndex NetGetJoinableOUs NetGetJoinInformation NetGroupAdd NetGroupAddUser NetGroupDel NetGroupDelUser NetGroupEnum NetGroupGetInfo NetGroupGetUsers NetGroupSetInfo NetGroupSetUsers NetIsServiceAccount NetJoinDomain NetLocalGroupAdd NetLocalGroupAddMember NetLocalGroupAddMembers NetLocalGroupDel NetLocalGroupDelMember NetLocalGroupDelMembers NetLocalGroupEnum NetLocalGroupGetInfo NetLocalGroupGetMembers NetLocalGroupSetInfo NetLocalGroupSetMembers NetProvisionComputerAccount NetQueryDisplayInformation NetQueryServiceAccount NetRemoteComputerSupports NetRemoteTOD NetRemoveAlternateComputerName NetRemoveServiceAccount NetRenameMachineInDomain NetRequestOfflineDomainJoin NetRequestProvisioningPackageInstall NetScheduleJobAdd NetScheduleJobDel NetScheduleJobEnum NetScheduleJobGetInfo NetServerComputerNameAdd NetServerComputerNameDel NetServerDiskEnum NetServerEnum NetServerGetInfo NetServerSetInfo NetServerTransportAdd NetServerTransportAddEx NetServerTransportDel NetServerTransportEnum NetSessionDel NetSessionEnum NetSessionGetInfo NetSetPrimaryComputerName NetShareAdd NetShareCheck NetShareDel NetShareDelEx NetShareEnum NetShareGetInfo NetShareSetInfo NetStatisticsGet NetUnjoinDomain NetUseAdd NetUseDel NetUseEnum NetUseGetInfo NetUserAdd NetUserChangePassword NetUserDel NetUserEnum NetUserGetGroups NetUserGetInfo NetUserGetLocalGroups NetUserModalsGet NetUserModalsSet NetUserSetGroups NetUserSetInfo NetValidateName NetValidatePasswordPolicy NetValidatePasswordPolicyFree NetWkstaGetInfo NetWkstaSetInfo NetWkstaTransportAdd NetWkstaTransportDel NetWkstaTransportEnum NetWkstaUserEnum NetWkstaUserGetInfo NetWkstaUserSetInfo                                     | AUTHNEXTSTEP DAV_AUTHN_SCHEME DomainControllerAddressType DomainControllerType DomainTrustFlag DsGetDcNameFlags DsGetDcOpenOptions DsGetForestTrustInformationFlags DSROLE_FLAGS DSROLE_MACHINE_ROLE DSROLE_OPERATION_STATE DSROLE_PRIMARY_DOMAIN_INFO_LEVEL DSROLE_SERVER_STATE GetLocalGroupFlags LogonServerRole NET_VALIDATE_PASSWORD_TYPE SvcAcctAddFlag SvcAcctRemFlag UserAcctCtrlFlags UserEnumFilter UserOpPriv UserPrivilege PRJOB AtJobFlags DFS_NAMESPACE_VERSION_ORIGIN DFS_TARGET_PRIORITY_CLASS DfsAddFlags DfsCapabilities DfsMoveFlags DfsPropertyFlag DfsRemoveFlags DfsState DfsStorageState DSREG_JOIN_TYPE NET_COMPUTER_NAME_TYPE NETSETUP NETSETUP_JOIN_STATUS NETSETUP_NAME_TYPE NETSETUP_PROVISION RemoteSupportFlags NetServerEnumFilter SERVER_TRANSPORT_FLAGS ServerPlatform SESS ShareLevelAccess SHI1005_FLAGS STYPE NetUseFlags NetUseForce NetUseStatus NetUseType PLATFORM_ID                                                                                                                                             | DAV_CALLBACK_AUTH_BLOB DAV_CALLBACK_AUTH_UNP DAV_CALLBACK_CRED DOMAIN_CONTROLLER_INFO DS_DOMAIN_TRUSTS DSROLE_OPERATION_STATE_INFO DSROLE_PRIMARY_DOMAIN_INFO_BASIC DSROLE_UPGRADE_STATUS_INFO GROUP_INFO_0 GROUP_INFO_1 GROUP_INFO_1002 GROUP_INFO_1005 GROUP_INFO_2 GROUP_INFO_3 GROUP_USERS_INFO_0 GROUP_USERS_INFO_1 LOCALGROUP_INFO_0 LOCALGROUP_INFO_1 LOCALGROUP_INFO_1002 LOCALGROUP_MEMBERS_INFO_0 LOCALGROUP_MEMBERS_INFO_1 LOCALGROUP_MEMBERS_INFO_2 LOCALGROUP_MEMBERS_INFO_3 LOCALGROUP_USERS_INFO_0 NET_DISPLAY_GROUP NET_DISPLAY_MACHINE NET_DISPLAY_USER NET_VALIDATE_AUTHENTICATION_INPUT_ARG NET_VALIDATE_OUTPUT_ARG NET_VALIDATE_PASSWORD_CHANGE_INPUT_ARG NET_VALIDATE_PASSWORD_HASH NET_VALIDATE_PASSWORD_RESET_INPUT_ARG NET_VALIDATE_PERSISTED_FIELDS USER_INFO_0 USER_INFO_1 USER_INFO_10 USER_INFO_1003 USER_INFO_1005 USER_INFO_1006 USER_INFO_1007 USER_INFO_1008 USER_INFO_1009 USER_INFO_1010 USER_INFO_1011 USER_INFO_1012 USER_INFO_1013 USER_INFO_1014 USER_INFO_1017 USER_INFO_1018 USER_INFO_1020 USER_INFO_1023 USER_INFO_1024 USER_INFO_1025 USER_INFO_1051 USER_INFO_1052 USER_INFO_1053 USER_INFO_11 USER_INFO_2 USER_INFO_20 USER_INFO_21 USER_INFO_22 USER_INFO_23 USER_INFO_24 USER_INFO_3 USER_INFO_4 USER_MODALS_INFO_0 USER_MODALS_INFO_1 USER_MODALS_INFO_1001 USER_MODALS_INFO_1002 USER_MODALS_INFO_1003 USER_MODALS_INFO_1004 USER_MODALS_INFO_1005 USER_MODALS_INFO_1006 USER_MODALS_INFO_1007 USER_MODALS_INFO_2 USER_MODALS_INFO_3 ADMIN_OTHER_INFO ERRLOG_OTHER_INFO PRINT_OTHER_INFO STD_ALERT USER_OTHER_INFO AT_ENUM AT_INFO DFS_GET_PKT_ENTRY_STATE_ARG DFS_INFO_1 DFS_INFO_100 DFS_INFO_101 DFS_INFO_102 DFS_INFO_103 DFS_INFO_104 DFS_INFO_105 DFS_INFO_106 DFS_INFO_107 DFS_INFO_150 DFS_INFO_2 DFS_INFO_200 DFS_INFO_3 DFS_INFO_300 DFS_INFO_4 DFS_INFO_5 DFS_INFO_50 DFS_INFO_6 DFS_INFO_7 DFS_INFO_8 DFS_INFO_9 DFS_STORAGE_INFO DFS_STORAGE_INFO_1 DFS_TARGET_PRIORITY DFS_SUPPORTED_NAMESPACE_VERSION_INFO DSREG_USER_INFO NETSETUP_PROVISIONING_PARAMS TIME_OF_DAY_INFO SERVER_INFO_100 SERVER_INFO_101 SERVER_INFO_102 SERVER_INFO_402 SERVER_INFO_403 SERVER_TRANSPORT_INFO_0 SERVER_TRANSPORT_INFO_1 SERVER_TRANSPORT_INFO_2 SERVER_TRANSPORT_INFO_3 CONNECTION_INFO_0 CONNECTION_INFO_1 FILE_INFO_2 FILE_INFO_3 SESSION_INFO_0 SESSION_INFO_1 SESSION_INFO_10 SESSION_INFO_2 SESSION_INFO_502 SHARE_INFO_0 SHARE_INFO_1 SHARE_INFO_1004 SHARE_INFO_1005 SHARE_INFO_1006 SHARE_INFO_1501 SHARE_INFO_1503 SHARE_INFO_2 SHARE_INFO_501 SHARE_INFO_502 SHARE_INFO_503 STAT_SERVER_0 STAT_WORKSTATION_0 USE_INFO_0 USE_INFO_1 USE_INFO_2 USE_INFO_3 USE_INFO_4 USE_INFO_5 WKSTA_INFO_100 WKSTA_INFO_101 WKSTA_INFO_1010 WKSTA_INFO_1011 WKSTA_INFO_1012 WKSTA_INFO_1013 WKSTA_INFO_1018 WKSTA_INFO_102 WKSTA_INFO_1023 WKSTA_INFO_1027 WKSTA_INFO_1028 WKSTA_INFO_1032 WKSTA_INFO_1033 WKSTA_INFO_1041 WKSTA_INFO_1042 WKSTA_INFO_1043 WKSTA_INFO_1044 WKSTA_INFO_1045 WKSTA_INFO_1046 WKSTA_INFO_1047 WKSTA_INFO_1048 WKSTA_INFO_1049 WKSTA_INFO_1050 WKSTA_INFO_1051 WKSTA_INFO_1052 WKSTA_INFO_1053 WKSTA_INFO_1054 WKSTA_INFO_1055 WKSTA_INFO_1056 WKSTA_INFO_1057 WKSTA_INFO_1058 WKSTA_INFO_1059 WKSTA_INFO_1060 WKSTA_INFO_1061 WKSTA_INFO_1062 WKSTA_INFO_302 WKSTA_INFO_402 WKSTA_INFO_502 WKSTA_TRANSPORT_INFO_0 WKSTA_USER_INFO_0 WKSTA_USER_INFO_1 WKSTA_USER_INFO_1101 