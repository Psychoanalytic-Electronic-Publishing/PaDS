# PaDS 
The PaDS Web system provides a portal for the administration of the following functions:
  - Subscriber or member detail maintenance and authentication.
  - Subscriber block order importing.
  - Order taking and maintaining.
  - Creditcard authorisation interface.
  - Cashbook maintenance.
  - Bank deposit maintenance.
  - Shipping and despatch.
  - Report generation.
  - Product and rates administration
  - Content set administration
  
## Getting Started
- Download PaDSForGitHub Zip file and unzip.
- Install database backups PaDSForGitHub\BusinessLogic\SQL\DBCreation\PaDS_Try.bak and PaDS_Logs_Try.bak on SQL Server 2017 or above. SQL Express is sufficient.
- On SQL Server run PaDSForGitHub\BusinessLogic\SQL\CreateUsersAndRoleseplaceServerName.sql
- Open the PaDS.sln file in Visual Studio 2019 or above
- Complile the solution
- Open PaDSForGitHub\PaDSTestHarness\bin\Debug\PaDSTestHarness.exe
- Update the "Primary Connection String" & "Test Data Directory" and click "Compile 1st SQL"
- The PaDS solution should now run showing the PaDS website, the PEPSecure API & the Federated/OpenAthens pass through page.
- Users Test1 to Test9 are available all with password TestUserPassword01.  User Test6 has full admin rights on PaDSs.

### Prerequisites
You will need the following things properly installed on your computer.
 - Visual Studio 2019
 - Microsoft .NET Framework 4.7.1
 - DevExpress v19.2 ASP.NET Subscription (with DevExtreme) package. (https://www.devexpress.com/)
 - Ionic Zip v4.0.30319 a library for handling zip archives. http://www.codeplex.com/DotNetZip (Flavor=Retail)
 - Spreadsheetgear2017 a library for handling spreadsheets. https://www.spreadsheetgear.com
 - Microsof Office 2016 or above, used to manipulate Word documents and Excel pivot tables
### API
  - OpenAPI documentation - https://app.swaggerhub.com/apis/nrshapiro/PEPSecure/1.04
