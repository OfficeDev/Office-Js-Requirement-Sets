# Office-Js Requirement sets

The purpose of this repository is to provide a central source of mapping of Office hosts and their corresponding OfficeJs requirement sets.
This repository can be used as a reference by Office developers to check  requirement sets are supported by host (Excel, Word, Outlook, etc.) on a given platform (Win32, Mac, Online, iOS, etc.)

Requirement sets are named groups of API members. They are similar to product version numbers. Office Add-ins use requirement sets specified in the manifest or use a runtime check to determine whether an Office host supports APIs that an add-in needs.
For more information, visit Office developer [website](https://dev.office.com).

For general information about where add-ins are supported by Office host, see  [Office Add-in host and platform availability](https://dev.office.com/add-in-availability).

## Contents

This repository contains the following assets:

1. [Mapping JSON file](mapping/requirements_officejs.json)
2. [Mapping JSON file schema](mapping/schema_requirements.json)

## Contribution

Your feedback is important to us.
* To let us know about any questions or issues you find, [submit an issue](https://github.com/OfficeDev/Office-Js-Requirements/issues) in this repository.  
* We also encourage you to fork, make the fix, and do a pull request of your proposed changes. For details, see [Contribute to this documentation](contribute.md).


This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information, see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
