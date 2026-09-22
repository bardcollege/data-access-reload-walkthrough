# Data Access Reload Walkthrough

Navigate to the [Ellucian Customer Center](https://elluciansupport.service-now.com/customer_center?id=customer_center_home) and log in. Click 'Tools' in the navigation bar, and select 'Data Access' on the top left under 'Ethos.'

When prompted, select 'SaaS Production' for Bard College.

Open the dropdown on the 'Current Data' tab and select 'Student API'. Click the filter icon on the right above the table, type 'courses' for the resource, and click 'Filter.'

Click the checkbox for the 'courses' resource, then click the settings icon that appears in the right column. Verify the settings are set to 500 page size and 20 max concurrent pages.

Press the 'Reload' button. Nothing will happen! Wait a few minutes. Go to the 'Data Loads' tab and you will be able to see the load in progress once it starts. This can take 7 or 8 minutes. If nothing has happened after 10, refresh the page and re-initiate the load.

Once the load has started it should only take 6 or 7 minutes to complete.
