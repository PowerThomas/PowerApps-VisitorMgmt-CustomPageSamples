# Power Apps - Visitor Management - Custom Page Samples
![App Home Page](/VisitorMngtAppHome.png)

## Description
This repository hosts a sample model-driven Power Platform application for managing visitors, featuring custom page examples. **Please note that this app is for demonstration purposes only and is not a fully functional application.**

## Dependencies
This app has the following dependencies:

1. [**Creator Kit**](https://aka.ms/CreatorKit): Used for the building blocks of the custom pages.
2. [**NativeDialogControl**](https://github.com/PowerThomas/NativeDialogControl): Required for creating native dialogues in custom pages.

## Features

### Homepage
The homepage acts as a dashboard and features:
- KPIs that provide an overview of the visitor flow.
- Shortcuts for registering new visitors.
- Two overviews: one for today's visitors and another for recent visitors.

### New Scheduled Request
From the Visitors view, a new button is available in the command bar to create a scheduled request. Clicking on this opens a custom page as a sidebar, which serves as a wizard to guide the user through the request creation process.

### Confirm Arrival
From a visit form, there's a "Confirm Arrival" button in the command bar. Clicking on it opens a custom page in a centered dialog. Users can:
- Provide additional notes for the host.
- Confirm the arrival, triggering a form refresh and updating the Business Process Flow and other details automatically.

### Dialog Test Page
This custom page demonstrates the capabilities of NativeDialogControl.

### Navigation Options
This custom page showcases all the available navigation options within a custom page.

---

## How to Use
1. Make sure to install all the dependencies.
2. Import the [unmanaged solution](https://github.com/PowerThomas/PowerApps-VisitorMgmt-CustomPageSamples/releases/tag/Unmanaged).
3. Add several locations in the Branch table.
4. Have fun exploring Custom Pages!
  
## Contributing
This is an open-source project. Feel free to contribute by forking the repository and submitting a pull request.

## License
MIT
