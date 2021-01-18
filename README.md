# Powerautomate for Crm Solution
A xrmtoolbox plugin for Dynamic365 Customer engagement to create new cloud powerautomate workflows using common data service connectors and add it to selected crm solution.
**Also flow created are subject to crm solution only not [MYFlows]** (https://make.powerapps.com/) 
Once they are created you have to authenticate them in Flows (https://make.powerapps.com/) website.<br/>Please note this tool works only with only oauth and certificates types connection.
<br/>For how to connect and working examples please see below.<br/>
# [Go to Conections](#how-to-connect-in-xrmtoolbox-connection-types)<br/>
# [Go to Application](#application-explanation)<br/>
# [Go to Examples](#examples)<br/>
# [Go to After flow Created](#Created)<br/>
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
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/startuppic.PNG" >

### Select a solution to continue
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/selectcrm.PNG" >
In order to create a new flow or add existing flow you must select a solution to continue from this dropdown.

### Add a new Solution to continue
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/addnewsol.PNG" >
If you want to create a new solution, you can add it form here and. Note you can also select publisher for your solution. The new solution will appear in all solution list.

### Create Flow
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/addnewflow.PNG" >
When you have selected the flow, you can add the Flow to the solution. <br/>
  Also, you need to select one Trigger and Action in order to create a flow. &#x1F534; <br/>
 Once you have created the flow, it will appear in the user flows list.

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
**Share**:  Allow you to share the flow to selected user. &#x1F499; <br/>
**Unshare**:  Allow you to unshare the flow to selected user. &#x1F53B;<br/>
**Owner**:  Allow you to change the owner (careful you are giving others privilege to edit flow). &#x1F49C;<br/>

### Solution flows
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/selsolflows.PNG" >
Displays list of flow added to selected solution.

## Examples

### Add a new flow (system)
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/example1.PNG" >

### Add a new flow to solution
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/example2.PNG" >

### Share a flow to user in crm
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/sharing.PNG" >
In this example first we select a user and the click the share button to share this flow to user selected.
This is same for unshare and change owner actions.<br/><br/>

## Created



Feel free let me know about new features you want and any improvents you thought.
I will try to address as soon as possible.<br/>
you can riase new issues/fearures [here](https://github.com/yesadahmed/xrmtoolboxdocumentation/issues).

**Adnan Samuel**

