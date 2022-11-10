#### Welcome to Model Bank Deployment guide Documetation POC 

Objective

Setup a fully functional environment in BaaS with OOTB services + sample integrations with Retail ModelBank default configurations.

Developer Prerequisites

*   **Get acquainted with BaaS working knowledge,** as basic knowledge is required in order to execute the steps presented in this guide. Read [community guide](https://community.backbase.com/documentation/baas/latest/index "https://community.backbase.com/documentation/baas/latest/index") and [Use Case from BaaS](/wiki/spaces/BAAS/pages/1780121706 "/wiki/spaces/BAAS/pages/1780121706") before starting installation.
    
*   **Access to project’s Github organisation**. This should be managed by project’s Solutions Architect or Technical Manager.
    
*   Connection to Backbase VPN and Web Proxy:  
    [How to install Aviatrix VPN on MacBook](https://backbase.atlassian.net/wiki/spaces/I4E/pages/2497020179)  
    [How to use Webproxy via VPN](https://backbase.atlassian.net/wiki/spaces/I4E/pages/2497709075)
    
*   Postman client: [Download Postman | Get Started for Free](https://www.postman.com/downloads/)
    

Scope of this guide

The scope of the installation, for both out-of-the-box and custom/sample services, is provided as form of ‘**API Catalogue**’ document and **Architecture Diagram**

Tools and helpers

### Dependencies :

Construct URLs for project's environment

You can construct the URLs for your environment in the following format:

`RUNTIME_NAME` and `INSTALLATION_NAME` values can be found in DSC (`basic-installation.yml`) as `runtime` and `installation` respectively

*   Identity:
    
    `1https://identity.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/auth/`
    
*   CXP Manager (prior to 2022.02)
    
    `1https://app.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/cxp-manager/login`
    
*   Retail USA web portal (prior to 2022.02)
    
    `1https://app.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/retail-app`
    
*   Business USA web portal (including and after 2022.02) (SME only)
    
    `1https://business.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/web`
    
*   Retail USA web portal (including and after 2022.02)
    
    `1https://app.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/web`
    
*   Employee portal (prior to 2022.02)
    
    `1https://app.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/employee-app/login`
    
*   Employee portal (including and after 2022.02)
    
    `1https://employee.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/`
    
*   Employee essentials (prior to 2022.02)
    
    `1https://app.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/employee-essentials/login`
    
*   Employee essentials (including and after 2022.02)
    
    `1https://employee-essentials.<RUNTIME_NAME>.<INSTALLATION_NAME>.live.backbaseservices.com/`
    