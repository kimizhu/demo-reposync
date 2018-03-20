# Create and share dashboards in the Azure portal
You can can create multiple dashboards and share them with others who have access to your Azure subscriptions.  This article goes through the basics of creating, editing, publishing, and managing access to dashboards.

## Create a dashboard
To create a dashboard, select the **New dashboard** button next to the current dashboard's name.  

This action creates a new, empty, private dashboard and puts you into customization mode where you can name your dashboard and add or rearrange tiles.  When in this mode, the collapsible tile gallery takes over the left navigation menu.  The tile gallery lets you find tiles for your Azure resources in various ways.

## Understanding access control for dashboards	
With Role-Based Access Control (RBAC), you can assign users to roles at three different levels of scope:	
	
* subscription	
* resource group	
* resource	
	
The permissions you assign are inherited from subscription down to the resource. The published dashboard is a resource. Therefore, you may already have users assigned to roles for the subscription which also work for the published dashboard. 
