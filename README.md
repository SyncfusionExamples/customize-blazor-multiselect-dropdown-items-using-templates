# Customize Blazor MultiSelect Dropdown Items Using Templates

## Overview

This sample demonstrates how to customize the appearance and behavior of the Syncfusion [Blazor MultiSelect Dropdown](https://www.syncfusion.com/blazor-components/blazor-multiselect-dropdown) by using template features. The application shows how dropdown items can be rendered with custom layouts and how selected values can be displayed using a customized value template instead of the default text representation.

The sample also illustrates how to enhance the dropdown popup experience by adding custom header and footer content. These customization techniques help developers present additional business information, improve usability, and create richer selection experiences while continuing to use the standard MultiSelect interaction model.

## Key Features

- Uses the `SfMultiSelect` component to provide multi-selection functionality.
- Demonstrates custom item rendering through the `ItemTemplate` feature.
- Demonstrates custom selected value rendering through the `ValueTemplate` feature.
- Shows how to customize popup content using template support.
- Includes custom header template content for the dropdown popup.
- Includes custom footer template content for the dropdown popup.
- Demonstrates template-based UI customization for displaying additional contextual information alongside selectable items.
- Uses data binding and field mapping to display structured data within the dropdown list.
- Provides an example implementation for creating visually rich MultiSelect dropdown experiences.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `DropDownItemUsingTempalte.sln`.
3. Restore all NuGet packages.
4. Build the solution.
5. Set the hosted server project as the startup project if required.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Navigate to the repository root directory.
3. Restore NuGet packages:

```bash
dotnet restore
```

4. Run the application:

```bash
dotnet run
```

5. Open the local application URL displayed in the terminal after the project starts.

## Project Structure

`DropDownItemUsingTempalte.sln` - Solution file containing the Client, Server, and Shared projects.
`Client/Pages/Index.razor` - Main sample page demonstrating MultiSelect template customization using Item, Header, Footer, and Value templates.
`Client/Pages/FetchData.razor` - Default Blazor template page used to retrieve weather data from the server API.
`Server/Controllers/WeatherForecastController.cs` - API controller providing weather forecast data for the default FetchData page.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Documentation: https://blazor.syncfusion.com/documentation/multiselect-dropdown/templates

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.