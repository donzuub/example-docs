# Data Dictionary for Collection: ServiceInstallers
## Fields
| Field Name | Data Type | Description |
|------------|-----------|-------------|
| Version | str | |
| Pms | str | |
| DownloadLink | str | |
| Tables | list | |
| DeleteLocalDb | bool | |
| Settings | list | |
| document_id | str | |
| Resyncs | list | |
| PmsVersion | str | |

## Example Document
```json
{'Version': '2.3.8.0', 'Pms': 'opendental', 'DownloadLink': 'https://store-cdn.zuub.com/Installers/DEV/OpenDental/Updates/ZuubSync.OpenDental.2.3.8.1.zip', 'Tables': [], 'DeleteLocalDb': False, 'Settings': [{'Key': 'SyncDataTypes_append', 'Value': '30,99,98,29'}, {'Key': 'TxLimitInYears', 'Value': '5'}, {'Key': 'DeleteInterval', 'Value': '15'}, {'Key': 'SecondaryInterval', 'Value': '20'}, {'Key': 'FullResyncDay', 'Value': 'Saturday'}], 'document_id': 'JCmkEL9GxX7HP0Unuvr3'}
```
