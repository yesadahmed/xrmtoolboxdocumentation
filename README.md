# Powerautomate for Crm Solution
A xrmtoolbox plugin for Dynamic365 Customer engagement to create new cloud powerautomate workflows using common data service connectors and add it to selected crm solution.
Please note this tool works only with only oauth and certificates types connection.
<br/>For how to connect and working examples please see below.
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

## Examples
<img src="https://github.com/yesadahmed/xrmtoolboxdocumentation/blob/main/pics/startup1.PNG"  height="600">
