# Walkthrough: how to deploy TriMedX website

In this walkthrough we will go through all the deployment process step by step. Before you start, please, prepare your environment for deployment. The tools and software you will need are listed in the next section

>Note: It is strongly recommended to read the whole document before you start deploying to understand how the settings are interconnected and mutually dependent

## Prerequisites

- The latest version of [Visual Studio 2017 Community](https://www.visualstudio.com/downloads/)
- [.NET Core 2.0.6](https://github.com/dotnet/core/blob/master/release-notes/download-archives/2.0.6-download.md)
- .ASP.NET Core will be downloaded while opening the project with Visual Studio (in case it's missing)
- [NodeJS 8.9.1](https://nodejs.org/en/blog/release/v8.9.1/)
- [.NET Framework 4.7](https://www.microsoft.com/en-US/download/details.aspx?id=55167)
- [Git Bash](https://git-scm.com/downloads) (for Windows use default installation presets)
- [IIS 7](https://www.iis.net/downloads/microsoft/iis-manager) if missing
- [Microsoft SQL Server Management Studio 17.5](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
- Notepad
- GitHub account
- Okta developer account (see below how to set it up)

## Okta configuration
In this section you will configue authorization presets in Okta web interface. Configuring Okta in advance will allow us to use ports designated as trusted.



