# Omnis Git Port

We are publishing the Omnis import/export library which we use at amétiq to open projects with several libraries and to import/export them with one click. Please note that the project was originally written for internal use and may still have an architectural reference to amétiq siMed. Please feel free to adapt the project to your wishes and needs.


## Getting Started

1. Import GitImportExport.lbs from this sources via "New Lib from JSON" in Omnis Studio.
1. Open StartupTask of GitImportExport.
1. In the new Menu popping up select "Open Application" and select a Omnis Application you want to work with. For OSX you can just select your app from application folder, the GitImportExport will resolve the path to the firstruninstall folder. On Windows you have to select the root directory of your libraries.
1. Now you can select the export option from the menu.
1. The import work vise versa.


### Prerequisites

Omnis Studio 8.1 or higher


## Authors

* **Jari Elmer, Benjamin Rohner** - *For amétiq ag, Pfäffikon SZ, Switzlerland https://www.ametiq.com*
