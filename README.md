# ![LOGO](logo.png) StorSimple8000SeriesManagementClient **flow**ground Connector

## Description

A generated **flow**ground connector for the StorSimple8000SeriesManagementClient API (version 2017-06-01).

Generated from: https://api.apis.guru/v2/specs/azure.com/storsimple8000series-storsimple/2017-06-01/swagger.json<br/>
Generated at: 2019-05-07T17:39:18+03:00

## API Description



## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Lists all of the available REST API operations of the Microsoft.StorSimple provider

*Tags:* `Operations`

#### Input Parameters
* `api-version` - _required_ - The api version

### Retrieves all the managers in a subscription.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `api-version` - _required_ - The api version

### Retrieves all the managers in a resource group.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `api-version` - _required_ - The api version

### Deletes the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified manager name.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Updates the StorSimple Manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the access control records in a manager.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the access control record.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `accessControlRecordName` - _required_ - The name of the access control record to delete.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified access control record name.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `accessControlRecordName` - _required_ - Name of access control record to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or Updates an access control record.

*Tags:* `AccessControlRecords`

#### Input Parameters
* `accessControlRecordName` - _required_ - The name of the access control record.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the alerts in a manager.

*Tags:* `Alerts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Retrieves all the bandwidth setting in a manager.

*Tags:* `BandwidthSettings`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the bandwidth setting

*Tags:* `BandwidthSettings`

#### Input Parameters
* `bandwidthSettingName` - _required_ - The name of the bandwidth setting.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified bandwidth setting name.

*Tags:* `BandwidthSettings`

#### Input Parameters
* `bandwidthSettingName` - _required_ - The name of bandwidth setting to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the bandwidth setting

*Tags:* `BandwidthSettings`

#### Input Parameters
* `bandwidthSettingName` - _required_ - The bandwidth setting name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Clear the alerts.

*Tags:* `Alerts`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Lists supported cloud appliance models and supported configurations.

*Tags:* `CloudAppliances`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Complete minimal setup before using the device.

*Tags:* `Devices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the list of devices for the specified manager.

*Tags:* `Devices`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device

### Deletes the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$expand` - _optional_ - Specify $expand=details to populate additional fields related to the device or $expand=rolloverdetails to populate additional fields related to the service data encryption key rollover on device

### Patches the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the alert settings of the specified device.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the alert settings of the specified device.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Authorizes the specified device for service data encryption key rollover.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets all the backup policies in a device.

*Tags:* `BackupPolicies`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the backup policy.

*Tags:* `BackupPolicies`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The name of the backup policy.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the properties of the specified backup policy name.

*Tags:* `BackupPolicies`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The name of backup policy to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the backup policy.

*Tags:* `BackupPolicies`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The name of the backup policy to be created/updated.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Backup the backup policy now.

*Tags:* `BackupPolicies`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The backup policy name.
* `backupType` - _required_ - The backup Type. This can be cloudSnapshot or localSnapshot.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets all the backup schedules in a backup policy.

*Tags:* `BackupSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The backup policy name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the backup schedule.

*Tags:* `BackupSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The backup policy name.
* `backupScheduleName` - _required_ - The name the backup schedule.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the properties of the specified backup schedule name.

*Tags:* `BackupSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The backup policy name.
* `backupScheduleName` - _required_ - The name of the backup schedule to be fetched
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the backup schedule.

*Tags:* `BackupSchedules`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupPolicyName` - _required_ - The backup policy name.
* `backupScheduleName` - _required_ - The backup schedule name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the backups in a device.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Deletes the backup.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupName` - _required_ - The backup name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Clones the backup element as a new volume.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupName` - _required_ - The backup name.
* `backupElementName` - _required_ - The backup element name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Restores the backup on the device.

*Tags:* `Backups`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `backupName` - _required_ - The backupSet name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deactivates the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Lists the hardware component groups at device-level.

*Tags:* `HardwareComponentGroups`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Changes the power state of the controller.

*Tags:* `HardwareComponentGroups`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `hardwareComponentGroupName` - _required_ - The hardware component group name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Downloads and installs the updates on the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets all the jobs for specified device. With optional OData query parameters, a filtered set of jobs is returned.

*Tags:* `Jobs`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Gets the details of the specified job name.

*Tags:* `Jobs`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `jobName` - _required_ - The job Name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Cancels a job on the device.

*Tags:* `Jobs`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `jobName` - _required_ - The jobName.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns all failover sets for a given device and their eligibility for participating in a failover. A failover set refers to a set of volume containers that need to be failed-over as a single unit to maintain data integrity.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the metrics for the specified device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _required_ - OData Filter options

### Gets the metric definitions for the specified device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the network settings of the specified device.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Updates the network settings on the specified device.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the public encryption key of the device.

*Tags:* `Managers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Scans for updates on the device.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the Security properties of the specified device name.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Patch Security properties of the specified device name.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### sync Remote management Certificate between appliance and Service

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Sends a test alert email.

*Tags:* `Alerts`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the time settings of the specified device.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the time settings of the specified device.

*Tags:* `DeviceSettings`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the update summary of the specified device name.

*Tags:* `Devices`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets all the volume containers in a device.

*Tags:* `VolumeContainers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the volume container.

*Tags:* `VolumeContainers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The name of the volume container.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the properties of the specified volume container name.

*Tags:* `VolumeContainers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The name of the volume container.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the volume container.

*Tags:* `VolumeContainers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The name of the volume container.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the metrics for the specified volume container.

*Tags:* `VolumeContainers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _required_ - OData Filter options

### Gets the metric definitions for the specified volume container.

*Tags:* `VolumeContainers`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the volumes in a volume container.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the volume.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `volumeName` - _required_ - The volume name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the properties of the specified volume name.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `volumeName` - _required_ - The volume name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the volume.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `volumeName` - _required_ - The volume name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the metrics for the specified volume.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `volumeName` - _required_ - The volume name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _required_ - OData Filter options

### Gets the metric definitions for the specified volume.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `volumeContainerName` - _required_ - The volume container name.
* `volumeName` - _required_ - The volume name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Retrieves all the volumes in a device.

*Tags:* `Volumes`

#### Input Parameters
* `deviceName` - _required_ - The device name
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Failovers a set of volume containers from a specified source device to a target device.

*Tags:* `Devices`

#### Input Parameters
* `sourceDeviceName` - _required_ - The source device name on which failover is performed.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Given a list of volume containers to be failed over from a source device, this method returns the eligibility result, as a failover target, for all devices under that resource.

*Tags:* `Devices`

#### Input Parameters
* `sourceDeviceName` - _required_ - The source device name on which failover is performed.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the encryption settings of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the extended info of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the extended information of the specified manager name.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Updates the extended info of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `If-Match` - _required_ - Pass the ETag of ExtendedInfo fetched from GET call

### Creates the extended info of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Lists the features and their support status

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Gets all the jobs for the specified manager. With optional OData query parameters, a filtered set of jobs is returned.

*Tags:* `Jobs`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _optional_ - OData Filter options

### Returns the activation key of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Returns the symmetric encrypted public encryption key of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the metrics for the specified manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version
* `$filter` - _required_ - OData Filter options

### Gets the metric definitions for the specified manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Provisions cloud appliance.

*Tags:* `CloudAppliances`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Re-generates and returns the activation key of the manager.

*Tags:* `Managers`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets all the storage account credentials in a manager.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Deletes the storage account credential.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `storageAccountCredentialName` - _required_ - The name of the storage account credential.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Gets the properties of the specified storage account credential name.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `storageAccountCredentialName` - _required_ - The name of storage account credential to be fetched.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

### Creates or updates the storage account credential.

*Tags:* `StorageAccountCredentials`

#### Input Parameters
* `storageAccountCredentialName` - _required_ - The storage account credential name.
* `subscriptionId` - _required_ - The subscription id
* `resourceGroupName` - _required_ - The resource group name
* `managerName` - _required_ - The manager name
* `api-version` - _required_ - The api version

## License

**flow**ground :- Telekom iPaaS / azure-com-storsimple-8000-series-storsimple-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
