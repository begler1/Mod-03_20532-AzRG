<!---
Version: 1.0 
-->
# Exercise 1: Creating an Azure Web App
## INTRODUCTION MESSAGE
In this exercise, you will:  
  
Create a Web App instance in the Portal.  
Go to the URL for the new Web App.  
  
The main tasks for this exercise are as follows:  
Create a Web App instance using the Azure Portal.  
Go to the newly created Web App's placeholder page
## COMPLETION MESSAGE
Results: After completing this exercise, you will have used the Portal to create a Web App instance.
### Login as Student
Login as Student with a password of Pa$$w0rd.

#### :bulb: KNOWLEDGE
You can use the Commands menu and choose Ctrl\+Alt\+Delete then click Student and enter Pa$$w0rd and press Enter. You can also use the Command menu and choose Paste/Paste Password instead of typing the password manually.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/5fb2586e.jpg
>* ShowAutomatically = No





### On the Start screen, click Internet Explorer
On the Start screen, click the Internet Explorer tile

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666327.jpg
>* ShowAutomatically = No





### Go to the new Azure Portal
Go to https://portal.azure.com. Enter the email address of your Microsoft account associated with your Azure subscription. Then enter the password for your Microsoft account. Check Keep me signed in. Click Sign In.

#### :bulb: KNOWLEDGE
Before starting this lab, you must have completed the lab in Module 2. All work in this lab is done within vm20532 created in the lab in Module 2. Start and Connect via Azure Portal.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666328.jpg
>* ShowAutomatically = No



#### :calling: COMMAND
```TypeText
https://portal.azure.com
```


### Browse Virtual Machines
In the navigation pane on the left side of the Azure Portal, click Virtual Machines.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666329.jpg
>* ShowAutomatically = No





### Start the VM
Click the vm20532 VM that was created in the lab in Module 2 for development. In the Overview blade, if the VM is stopped, click Start and wait for the VM to start up. This may take a few minutes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666330.jpg
>* ShowAutomatically = No





### Connect to the VM via RDP
When the vm20532 VM has started, click Connect. You may have to click the Refresh button first.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666331.jpg





### Allow pop-ups
If presented with a message box that shows a pop-up has been blocked, select Options for this site and choose Always Allow. Then click Connect again.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/672175.jpg





### Click Open
When presented with the RDP download popup at the bottom of the screen, click Open.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/672176.jpg





### In the Remote Desktop Connection dialog box:
In the Remote Desktop Connection dialog box, perform the following steps:  
a. Click Don’t ask me again for connections to this computer to prevent this dialog box from displaying again.  
b. Click Connect.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666332.jpg





### In the Windows Security dialog box:
In the Windows Security dialog box, perform the following steps:  
a. For the User name dialog box, provide the value, Student. b. For the Password dialog box, provide the value, AzurePa$$w0rd. c. Click OK.

#### :bulb: KNOWLEDGE
Note: If you computer is on a domain, you may need to add a backslash before the username to "escape" the domain.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666333.jpg





### In the Remote Desktop Connection dialog box:
In the Remote Desktop Connection dialog box, perform the following steps:  
a. Verify if the Remote certificate name matches the name of your virtual machine. b. Click Don’t ask me again for connections to this computer to prevent this dialog box from displaying again. c. Click Yes.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666334.jpg





### Minimize Server Manager
If you just started the VM, Server Manager will start automatically after 30 seconds. If it starts, minimize it.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666335.jpg





### On the Taskbar, open Internet Explorer
On the Taskbar, click the Internet Explorer icon.





### Sign in to the Azure Portal
Sign in to the Azure Portal at https://portal.azure.com.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666336.jpg



#### :calling: COMMAND
```TypeText
https://portal.azure.com
```


### Click New. Select the Web + Mobile option
In the navigation pane on the left side of the screen, click \+ New. Select the Web \+ Mobile option. Click the See all link to navigate to the Marketplace.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666338.jpg





### Search for and select the Web App + SQL template
Search for and select the Web App \+ SQL template.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666339.jpg





### In the Web App + SQL blade, click Create button
In the Web App \+ SQL blade, click the Create button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666340.jpg





### In the form that displays, perform the following:
In the form that displays, perform the following steps: a. In the App name dialog box, create a unique name for your website. b. In the Subscription Group section, select the subscription you wish to use. c. In the Resource Group section, select the Use existing option and then select the 20532 Resource Group from the list. d. Select the App Service plan option. e. In the App Service plan blade, click the Create New button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666341.jpg





### In the New App Service plan blade:
e. In the New App Service plan blade, locate the App Service plan dialog box and provide the value SamplePlan. f. In the Location list, select the region that is closest to your location. g. Select the Pricing tier option. h. If present, click the View All link. Otherwise continue.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666342.jpg





### Locate and select the Free pricing tier.
Locate and select the Free pricing tier. Click the Select button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666343.jpg





### Back in the App Service plan blade, click OK
k. Back in the App Service plan blade, click the OK button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666344.jpg





### Back in the Web App + SQL blade:
l. Back in the Web App \+ SQL blade, click the SQL Database option. m. In the Database blade, click the Create a new database option. n. In the SQL Database blade, locate the Name box and provide the value EventsContextDB. o. In the SQL Database blade, click the Target server option.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666345.jpg





### In the Server blade, create a new server
p. In the Server blade, click the Create a new server option. q. In the Server name dialog box, create a unique name for your server instance. r. In the Server admin login dialog box, create a user name \(testuser\) for your administrative SQL user. s. In the Password and Confirm Password dialog boxes, create a password \(TestPa$$w0rd\). t. In the Location list, select the region that is closest to your location and leave the Allow azure services to access server checked. u. Click the Select button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666346.jpg





### Back in the SQL Database blade, click Select
v. Back in the SQL Database blade, keep the default values for Pricing and Collation then click the Select button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666347.jpg





### Click the Create button to create your Web App
w. Back in the Web App \+ SQL blade, leave App Insights turned off, then click the Create button to create your Web App and SQL database.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666348.jpg





### Wait for Web App to deploy
Note: Creating a Web App is typically very fast, but you have to wait for the Web App and the SQL Server DB to be created and running before you can go to the Web App. When the Web App is running, its status displays as Running in the App Services list.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666350.jpg





### Browse App Services
In the navigation pane on the left side, click More Services. Scroll-down, locate and select the App Services option.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666349.jpg





### Verify that the Web App has a status of Running.
Verify that the Web App has a status of Running. In the App Services list, click the Web App that you just created.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666351.jpg





### Open the Web App URL
On the Essentials panel at the top of the Overview blade. \(You may have to scroll up to see it\). Under the URL header, click the hyperlink to the Web App. It should end in azurewebsites.net.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666352.jpg





### Verify that the Web App exists.
Verify that the Web App exists. Close the tab displaying the website

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666353.jpg






# Exercise 2: Deploying an ASP.NET Web Application to an Azure Web App
## INTRODUCTION MESSAGE
In this exercise, you will:  
  
Download the publish profile for an existing Web App.  
Publish a web application by using the publish wizard in Visual Studio.  
  
The main tasks for this exercise are as follows:  
Open an existing ASP.NET web application project with Visual Studio.  
Download the publish profile for the Azure Web App.  
Publish the ASP.NET web application to the Azure Web App.  
Verify that the web application is successfully published.
## COMPLETION MESSAGE
Results: After completing this exercise, you will have used a publish profile to publish web applications directly to a Web App.
### Open an existing ASP.NET web application project
On the taskbar, click the File Explorer icon. Click This PC, then go to Allfiles \(F\):\\Mod03\\Labfiles\\Starter\\Contoso.Events, and then double-click Contoso.Events.sln. \(The file extension may be hidden\). If prompted for the application to open, click Visual Studio 2017. The project may take a few minutes to open.

#### :bulb: KNOWLEDGE
Note that Known file extensions \(such as .sln\) may be hidden. See screenshot. It may also take a while for Visual Studio to open.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666380.jpg
>* ShowAutomatically = No





### Set Startup Project
In the Solution Explorer pane, scroll-down then right-click the Contoso.Events.Management project, and then click Set as Startup Project.

#### :bulb: KNOWLEDGE
Note: If Solution Explorer is not visible you can open it by using the View menu and selecting Solution Explorer.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666381.jpg





### On the Debug menu, click Start Debugging.
On the Debug menu, click Start Debugging.

#### :bulb: KNOWLEDGE
Note: If this is the first time you are creating a build for this solution, NuGet will implicitly restore any missing packages. You do not have to manually restore the missing packages.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666382.jpg





### Verify events under the Latest 3 Events header
On the home page of the web application, verify that a list of three events displays under the Latest 3 Events header.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666383.jpg





### Click Events in the navigation bar
Click Events in the navigation bar at the top of the webpage. Verify that the Events page displays a list of events. Close the tab displaying the Web App.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666384.jpg





### Switch back to the Azure Portal
Click on the Internet Exlorer icon in the task bar to switch back to the Azure Portal. The Web App blade should already be open.

#### :bulb: KNOWLEDGE
If it is not already open, launch Internet Exlorer and enter https://portal.azure.com and login. If the Web App blade is not already open, in the App Services list, click the Web App that you had just created.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666385.jpg





### Get publish profile
Click the Get publish profile option. In the download dialog box, click the arrow to the right of the Save button, and then click Save As.

#### :bulb: KNOWLEDGE
If necessary, click the More button at the top of the blade to see the Get Publish profile option.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666386.jpg





### Save the Publish Profile
In the Save As dialog box, go to Allfiles \(F\):\\Mod03\\Labfiles, and then click Save. You can then close the message box at the bottom of the screen.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666387.jpg





### Switch back to Visual Studio and Publish project
Switch back to Visual Studio by clicking the icon in the task bar. In the Solution Explorer pane of the Contoso.Events - Microsoft Visual Studio window, right-click Contoso.Events.Management, and then click Publish.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666388.jpg





### Make sure the Publish window is fully visible:
Make sure the Publish window is fully visible by clicking the push-pull button on the Solution Explorer to Auto Hide that window. Auto Hide any other windows that may be in the way also.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/779398.jpg





### On the Publish window:
On the Publish window, click the > icon and select Import Profile then click the Publish button.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/779399.jpg





### Import Publish Settings File
In the Import Publish Settings File dialog box, under this PC, navigate to Allfiles \(F\):\\Mod03\\Labfiles, and then select your previously saved publish profile and click Open. The Web App will then proceed to publish to Azure.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773262.jpg





### Verify Publish succeeded
Verify Publish has succeeded in the Web Publish Activity window. Notice the hyperlink for the Web App in the Web Publish Activity window under the words "Publish Succeeded". Note the Web App opens in the Visual Studio browser. Click the push-pull pin in the Web Publish Activity window to Auto Hide it.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/779400.jpg





### Verify the Web App home page
On the home page of the web application, verify that a list of three events displays under the Latest 3 Events header.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773264.jpg





### Click Events in the navigation bar
Click Events in the navigation bar at the top of the webpage. Verify that the Events page displays a list of events. Close the tab displaying the Web App.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773265.jpg





### Test the Web App using Internet Explorer
Switch back to the Azure Portal. You should still be on the Web App Overview blade. Click on the URL hyperlink for the Web App. This should open Internet Explorer for the Web App. Close the tab for the Web App when finished. Leave the Azure Portal tab open.

#### :bulb: KNOWLEDGE
If the published version of the Web App does not appear, try to refresh the browser.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/779401.jpg






# Exercise 3: Configuring an Azure Web App
## INTRODUCTION MESSAGE
In this exercise, you will:  
  
Use the ConfigurationManager class to read custom app settings from a web configuration file.  
Modify custom app settings by using the Portal.  
  
The main tasks for this exercise are as follows:  
Implement logic to read a configuration setting from app settings.  
Publish web application to the Azure Web App.  
Modify the app settings in the Portal.  
Verify that the app settings are successfully updated.
## COMPLETION MESSAGE
Results: After completing this exercise, you will have configured custom app settings by using a Web.config file and the Azure Portal.
### Switch back to Visual Studio
Switch back to Visual Studio by clicking the icon in the task bar.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773234.jpg





### Set Tools/Options:
Enlarge the font of the Text Editor by choosing Tools/Options then selecting the Fonts and Colors page under the Environment category. You can also request Word Wrap by choosing the Text Editor category then clicking All Languages and selecting the Word Wrap and Show visual glyphs for word wrap options. Click OK when finished.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773238.jpg





### Open EventsListViewModel.cs
In the Solution Explorer pane of the Contoso.Events - Microsoft Visual Studio window, expand the Contoso.Events.ViewModels project. In the Solution Explorer pane, double-click EventsListViewModel.cs.

#### :bulb: KNOWLEDGE
If you don't see the Solution Explorer you can select it from the View menu.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666362.jpg





### Locate the following code:
Locate and select the following code of EventsListViewModel.cs:  
this.EventCount = 3;

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666363.jpg





### Replace the line of code with the following:
Replace the line of code with the following new code:  
this.EventCount = Int32.Parse\(ConfigurationManager.AppSettings\["EventsListViewModel.EventCount"\]\);

#### :bulb: KNOWLEDGE
\(You can highlight the existing code and click the "A" icon \(Type Text\) in the step window to paste the new code, if you wish\)

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666364.jpg



#### :calling: COMMAND
```TypeText
this.EventCount = Int32.Parse(ConfigurationManager.AppSettings["EventsListViewModel.EventCount"]);
```


### Open Web.config
In the Solution Explorer pane of the Contoso.Events - Microsoft Visual Studio window, expand the Contoso.Events.Management project. In the Solution Explorer pane, double-click Web.config

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666366.jpg





### Add the following line of code:
In the appSettings element, before line 8, add the following new line of code: \(if you see an error, see "knowledge tip"\)  
<add key="EventsListViewModel.EventCount" value="5" />

#### :bulb: KNOWLEDGE
\(You create a new line and click the "A" icon \("Type Text"\) in the step window to paste the new code, if you wish\). If the "Type Text" feature enters an extra double-quote, delete it manually.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666367.jpg



#### :calling: COMMAND
```TypeText
  <add key="EventsListViewModel.EventCount" value="5" />
```


### Start Debugging
On the Debug menu, click Start Debugging. \(This will also save all files\)

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/623366.jpg





### Verify that a list of five events displays now
On the home page of the web application, verify that a list of five events displays under the Latest 5 Events header.  
Close the tab displaying the Web App.

#### :bulb: KNOWLEDGE
Verify the local URL for debugging

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666369.jpg





### Publish project after debugging
In the Solution Explorer pane of the Contoso.Events - Microsoft Visual Studio window, right-click Contoso.Events.Management, and then click Publish.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666370.jpg





### Click Publish.
Click Publish.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773244.jpg





### Verify that a list of five events displays
On the home page of the web application, verify that a list of five events displays under the Latest 5 Events header.  
Close the tab displaying the Web App.

#### :bulb: KNOWLEDGE
Verify the production URL

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/773245.jpg





### Switch back to the Azure Portal
Click on the Internet Exlorer icon in the task bar to switch back to the Azure Portal. The Web App blade should already be open.

#### :bulb: KNOWLEDGE
If it is not already open, launch Internet Exlorer and enter https://portal.azure.com and login. If the Web App blade is not already open, in the App Services list, click the Web App that you had just created.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666373.jpg





### Select Application settings
In the Settings section, select the Application settings option.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666374.jpg





### Override EventCount via App Settings
In the Application settings blade, scroll-down to the App Settings section.   
In the Key box, type EventsListViewModel.EventCount. In the Value box, type 2. Click Save.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666375.jpg





### Wait for Save to complete
Note: After you update the configuration settings, you must wait for a few seconds to see the configuration changes. You will know that the configuration changes are applied when the Configure tab is editable again.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666376.jpg





### Return to Overview blade and click Web App URL
Return to your Web App's Overview blade. Locate the Essentials panel at the top of the blade.  
Under the URL header, click the hyperlink to the Web App.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666377.jpg





### Verify that a list of two events displays
On the home page of the web application, verify that a list of two events displays under the Latest 2 Events header.  
Close the tab displaying the Web App.

#### :bulb: KNOWLEDGE
Notice that the Web App did not have to be re-published to override the EventsCount through App Settings.

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666378.jpg





### Close Internet Explorer
Close Internet Explorer





### Close Visual Studio
Close Visual Studio





### Close File Explorer
Close File Explorer





### Close Server Manager
Close Server Manager \(if open\)





### Close RDP session
Close RDP session and click OK to disconnect

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666357.jpg
>* ShowAutomatically = No





### Stop VM to save billing charges
If you are stopping labs for the day, on the vm2032 Overview page in the Azure Portal, click Stop to stop billing charges until you start labs again. If prompted, click Yes to stop the VM.





### Close Internet Explorer
Close Internet Explorer to end the lab

#### :camera: SCREENSHOT
>LODSProperties
>* Uri = screens//content/lab35888/screens/666359.jpg
>* ShowAutomatically = No






