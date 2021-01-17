# Powerautomate for Crm Solution
A xrmtoolbox plugin for Dynamic365 Customer engagement to create new cloud powerautomate workflows using common data service connectors and add it to selected crm solution.
Please note this tool works only with only oauth and certificates types connection.
<br/>For how to connect and working examples please see below.<br/>


## How to Connect in xrmtoolbox (connection Types)
Once you have the xrmtoolbox you need to install this plugin form Tool Library as shown below.
![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/library.png)

Once the installion is done, you will see this plugin as follows:
![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/PluginInXrm.PNG?raw=true)

Since this plugin connects to CE webapi so by default it requires **OAuth or Certifcate** type connections in xrmtoolbox.
<br/>For example regarding available OAuth connections in xrmtools are mentioned below:

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/Conn1.png)

Some examples are as follows.

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/sdkcontrol.png)

![xrmtoolbox connections](https://github.com/yesadahmed/xrmtoolboxAddins/blob/main/JsonToCSharp/images/conneciont.PNG)
 AuthType=OAuth;Username=jsmith@contoso.onmicrosoft.com; Password=passcode;
Url=https://contoso:8080/Test;AppId=<GUID>;RedirectUri=app://<GUID>; LoginPrompt=Never

## Application Explanation
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/startup1.PNG" >

### Select a solution to continue
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/selectcrm.PNG" >
In order to create a new flow or add existing flow you must select a solution to continue from this dropdown.

### Add a new Solution to continue
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/addnewsol.PNG" >
If you want to create a new solution, you can add it form here and. Note you can also select publisher for your solution. The new solution will appear in all solution list.

### Create Flow
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/addnewflow.PNG" >
When you have selected the flow, you can add the Flow to the solution. **Also, you need to select one Trigger and Action in order to create a flow.** Once you have created the flow, it will appear in the user flows list.

### CE Triggers and Actions
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/flow_trg_flows.PNG" >
Select at least one Trigger and action to create a new flow.

### Customer Engagement Users
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/systemusers.PNG" >
Available licensed dynamic365 users.

### Add flow to selected
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/addflowtosol.PNG" >
Select a flow form list below to add the flow to selected solution.


### User flows
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/usersslows.PNG" >
**Share**: Allow you to share the flow to selected user.
**Unshare**: Allow you to unshare the flow to selected user.
**Owner**: Allow you to change the owner (careful you are giving others privilege to edit flow).

### Solution flows
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/selsolflows.PNG" >
Displays list of flow added to selected solution.

### Examples

