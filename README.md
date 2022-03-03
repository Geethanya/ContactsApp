**prerequisite**
SQL Server 2014 or Above
Visual Studio 2019

**Code Execution Steps**

Download the "ContactsApp.bak" file and restore into your local SQL DB server
Un-Zip ContactsApp.zip file and open in your Visual Studio 2019
Update "Data Source" name in web.config file. Note: "Data Source" Name is your database server name
Example:
add key="Connection" value="Integrated Security=SSPI;Persist Security Info=False;Initial Catalog=ContactsApp;Data Source=**MyPC\SQLEXPRESS**"/>
Press F5 button from Visual Studio




