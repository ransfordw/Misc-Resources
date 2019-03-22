# Azure Deployment


### Getting started!

#### 1. Create an Azure Account through the Azure Portal. Do this using your Microsoft account

#### 2. Go to portal.azure.com

#### 3. [Here](https://github.com/go2ismail/AdminLTE-ASP-NET-MVC) is a link to a repo if you would like to run a practice deployment

#### 4. Clone the project and "cd" into that directory

#### 5. Open the project, right click on the MVC assembly, and select Publish

#### 6. Click Start under publish

#### 7. Make sure you are in the App Service tab, click the Create New radio button

#### 8. Give the App Name something unique

#### 9. Select Free Trial or Pay-As-You-Go depending on whether or not you are in the free trial or not

#### 10. Select new Resource group. Name it rg_YourAppName

#### 11. Select the free hosting plan

#### 12. Select Create

# At this point you should have a deployed version of Admin-LTE

<br>
<br>

# Deploying our Projects

### The following are step by step instructions for deploying an ElevenNote styled n-tier application with a database

#### 1. Open and build your project to make sure there are no errors. (crtl + shift + b)

#### 2. Right click on the MVC assembly, and select Publish

#### 3. Choose App Service 
#### *Make sure you are logged in to Azure*

#### 4. Select Create in the middle section then publish

#### 5. Like we did before, in the App Service window give the app a unique name. You will see red if the name is already taken

#### 6. Select Free Trial or Pay-As-You-Go depending on whether or not you are in the free trial or not

#### 7. Select new Resource group. Name it rg_YourAppName

#### 8. Select Free Trial or Pay-As-You-Go depending on whether or not you are in the free trial or not. The default name is fine for this
<br>

# Now things diverge a little from before:
## In the practice version, we did not have a database to worry about but with our projects we will want some sort of database on our deployed applications

#### 9. On the right select "**Create a SQL Database**"

#### 10. In the "Configure SQL Database" dialog, click "New" next to SQL Server

#### 11. Name the server. Example name: yourappnamesqldbserver. (yourappname + sql + db + server)

#### 12. Set up an Admin username and password. Make sure you can remember it or write it down somewhere, you will need these credentials later on

#### 13. Click OK, but DO NOT move past that yet

#### 14. In the Connection String Name, enter the name for your connection string. If you don't remeber where that is it should be in your web.config file in the MVC. It is likely "DefaulConnection"

#### 15. At this point we should have four things resources you've configured in the Create App Service dialog

#### 16. Deployment should begin and can take 5-20+ minutes the first time
