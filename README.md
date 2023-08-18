## Grafana Dashboards for Azure

### Prerequisites  

Log Collection
   * VM Insights has to be enabled for all VMs
   * For Application Dashboard is able to read logs from multiple App Insights instances.
     This is made possible by having the multiple Workspaced-enabled App Insights "located" in a single LA workspace, and the kusto query acts on that single LA workspace App Insights tables.
*Tables starting with <u>App</u>* are App Insights Tables containing logs from multiple instances
  <img src="https://github.com/weixian-zhang/Gov-POC-Azure-Observability-Grafana/assets/43234101/e2714784-6379-4da8-bd2f-3c62bff692ca" width="200px" height="500px" />



### Application Dashboard  

![image](https://github.com/weixian-zhang/Gov-POC-Azure-Observability-Grafana/assets/43234101/e7bd3aa1-fb91-455f-a786-8a7cc23f9115)
 

* requires Workspace-based Application Insights instances
* requires Standard Tests (previously known as Web Test) to be configured with SSL validity check
  <img src ="https://github.com/weixian-zhang/Gov-POC-Azure-Observability-Grafana/assets/43234101/29ba0e07-3f44-4e49-b000-8f16d39d7fc3" width="300px" height="300px" />

