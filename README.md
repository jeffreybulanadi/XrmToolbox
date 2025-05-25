# XrmToolBox

XrmToolBox is a powerful and efficient Windows application that hosts tools to customize and manage Microsoft Dynamics 365/CRM instances.

## Overview

XrmToolBox is built on .NET Framework and provides a modular architecture where community developers can create and share tools that help administrators, customizers, and developers interact with Microsoft Dynamics 365/CRM.

## Prerequisites

- Windows Operating System
- .NET Framework 4.7.2 or later
- Microsoft Dynamics 365/CRM instance
- Visual Studio 2019 or later (for development)

## Getting Started

1. Clone this repository
2. Run XrmToolBox.exe

## Features

- Connection management to multiple organizations
- Tool/plugin management
- Auto-update capability
- Plugin store integration
- Modern UI with docking windows

## Development

To develop new tools for XrmToolBox:

1. Create a new Class Library (.NET Framework) project
2. Add reference to XrmToolBox.Extensibility
3. Implement required interfaces
4. Build and deploy your tool

## Building from Source

1. Clone the repository:

    ```bash
    git clone https://github.com/YourUsername/XrmToolBox.git
    ```

2. Restore NuGet packages:

    ```bash
    nuget restore XrmToolBox.sln
    ```

3. Build the solution:

    ```bash
    msbuild XrmToolBox.sln /p:Configuration=Release
    ```

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Dependencies

- Microsoft.CrmSdk.CoreAssemblies
- Microsoft.CrmSdk.Deployment
- Microsoft.CrmSdk.Workflow
- Microsoft.Web.WebView2
- Newtonsoft.Json
- WeifenLuo.WinFormsUI.Docking
- NuGet.Protocol

## Support

For support, please visit the [XrmToolBox Website](https://www.xrmtoolbox.com) or create an issue in this repository.

## Acknowledgments

- Thanks to all contributors who have helped make XrmToolBox better
- Special thanks to the Dynamics 365 community
