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

## Detailed Remediation Steps for New Storage Accounts
1.  Login to Azure Portal (i.e portal.azure.com)
2.  Once Logged in navigate to "All Services" and search for Storage Accounts
3.  Click on "Create Storage Account"
4.  Choose Storage Account Features as desired and click on Advanced to configure Storage Network Restrictions
5.  Here you can choose which Networks are to be allowed

## Detailed Remediation Steps for New Storage Accounts
1.  Login to Azure portal (i.e portal.azure.com)
2.  Once Logged in navigate to "All Services" and search for Storage Accounts
3.  Click on Existing Storage Account you want to configure Network Restrictions on
4.  Under Settings you will see an option for "Firewalls and Virtual Networks" in the left pane
5.  Here you can specify existing Azure virtual Networks and/or Add IP ranges to allow access from the internet or your on-premises networks
6. Further if needed Exceptions can be added for Scenerios as below
  a.  Allow Trusted Microsoft Services Access
  b.  Allow read access for logging from any network
  c.  Allow read access for storage metrics from any network
