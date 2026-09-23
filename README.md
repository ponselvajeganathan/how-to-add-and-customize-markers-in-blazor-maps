# How to Add and Customize Markers in the Blazor Maps Control

## Overview

This sample demonstrates marker rendering and customization using the Syncfusion [Blazor Maps](https://www.syncfusion.com/blazor-components/blazor-map) component in a hosted Blazor WebAssembly application. The implementation shows how to display location-based data using markers, customize marker appearance, and bind styling information from a data source. The sample also demonstrates tooltip integration and formatting techniques that help users explore geographic information through interactive map experiences. This project serves as a practical reference for developers building location-aware applications with customizable map markers.

**Examples**: https://blazor.syncfusion.com/demos/maps/marker?theme=bootstrap5  

**Documentation**: https://help.syncfusion.com/chart-sdk/blazor/maps/markers

## Key Features

- Demonstrates rendering markers on a map using the Maps marker feature.
- Shows how marker shapes can be customized to represent geographic locations differently.
- Demonstrates binding marker styling information from the map data source.
- Illustrates how marker colors can be dynamically configured using data values.
- Demonstrates rendering multiple marker configurations within a map view.
- Shows how tooltips can be associated with markers to display contextual geographic information.
- Demonstrates tooltip formatting techniques for improved readability.
- Uses marker-based visualization to represent location-specific data points.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `CustomizingMarkersInMap.sln`

3. Restore NuGet packages.
4. Set the startup project 
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root or startup project directory.

```bash
dotnet restore
dotnet run
```

## Project Structure

`Client/Pages/Index.razor` — Contains the primary Syncfusion Maps implementation, marker configuration, marker customization logic, tooltip rendering, and geographic visualization settings.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://help.syncfusion.com/chart-sdk/blazor/maps/markers

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.