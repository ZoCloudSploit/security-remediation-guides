[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# AZURE / Storage Accounts / Securing Storage Account Network
## Quick Info

| | |
|-|-|
| **Plugin Title** | Securing Storage Account Network |
| **Cloud** | AZURE |
| **Category** | Storage Accounts |
| **Description** | With this you can secure your storage accounts to a specific set of supported networks. |
| **More Info** | When Azure network rules are configured, only applications requesting data from over the specified set of networks can access a storage account. |
| **AZURE Link** | https://docs.microsoft.com/en-us/azure/storage/common/storage-network-security |
| **Recommended Action** | In your Azure storage account, select an existing Storage Account, then select Firewall & Virtual Networks under Storage Account Settings , and you can add the necessary Network Details to be allowed. |

## Detailed Remediation Steps for a new Storage Account
1.  Login to Azure Portal (i.e portal.azure.com)
2.  Once logged in go to Azure Portal
![](images/Azure_Portal.png)
