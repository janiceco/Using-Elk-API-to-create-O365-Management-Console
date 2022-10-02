# Office 365 Management API Connector for the Elastic Stack (ELK)

This simple API connector queries the Office 365 Management API and pushes audit logs to the Elastic Stack (Logstash) via TCP. 

*This script was tested with Python 3.5 and 3.6.*

## Required modules
**Requests**
```
pip3 install requests
```

**[Microsoft Azure Active Directory Authentication Library (ADAL) for Python](https://github.com/AzureAD/azure-activedirectory-library-for-python)**
```
pip3 install adal
```
**IMPORTANT**: Before utilizing this script, you will need to create an Azure app to grant this script access to the API endpoints. 

