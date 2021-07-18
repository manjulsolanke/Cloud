## Azure Monitor logs

Azure Monitor is a service for collecting and analyzing telemetry. 

### Data collection in Azure Monitor
Azure Monitor collects two fundamental types of data:
 - Metrics 
 - logs 


 ![Azure monitor](./azure-monitor.png)


Azure Monitor collects data automatically from a range of components. For example:

    Application data: Data that relates to your custom application code.
    Operating system data: Data from the Windows or Linux virtual machines that host your application.
    Azure resource data: Data that relates to the operations of an Azure resource, such as a web app or a load balancer.
    Azure subscription data: Data that relates to your subscription. It includes data about Azure health and availability.
    Azure tenant data: Data about your Azure organization-level services, such as Azure Active Directory.

Because Azure Monitor is an automatic system, it begins to collect data from these sources as soon as you create Azure resources such as virtual machines and web apps. You can extend the data that Azure Monitor collects by:

Enabling diagnostics: For some resources, such as Azure SQL Database, you receive full information about a resource only after you have enabled diagnostic logging for it. You can use the Azure portal, the Azure CLI, or PowerShell to enable diagnostics.
Adding an agent: For virtual machines, you can install the Log Analytics agent and configure it to send data to a Log Analytics workspace. This agent increases the amount of information that's sent to Azure Monitor.

### Application Insights


Application Insights, a feature of Azure Monitor, is an extensible Application Performance Management (APM) service for developers and DevOps professionals.


- Visualizations
        
        Live metrics streams: Charts that display performance values as they vary in near-real time.
        Metrics explorer: Tool that shows how metrics vary over time.
        Alerts: Messages automatically sent to app admins when target metrics exceed specified thresholds. You can use alerts to ensure your team is aware of critical issues immediately.
        Profiler: Shows how a set of requests, like those for a single web page, were delivered. You can use these profiles, for example, to see which page elements load slowly.
        Application Map: Displays the components of an application and how they link to each other. You can use the data shown with each component to diagnose performance bottlenecks and failure hotspots.
        Usage analysis: Information about your app's users. For example, you can see numbers of unique users and sessions and information about user retention.