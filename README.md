
## Contact 
If you want to contact me, you can reach me at <shubham22071@iiitd.ac.in>

thanks
# Service Metrics Fat Table

## Overview

This project implements a dynamic web table that displays service metrics in a consolidated "fat row" format. Each service's client and server metrics are grouped together into rows with two sub-rows representing the client and server sides. The table supports filtering and sorting functionalities, making it easy to analyze and compare service performance metrics.

## Features

- **Fat Row Format**: Displays client and server metrics for each service in a consolidated view.
- **Filtering**: Allows filtering by service name or side (client/server).
- **Sorting**: Enables sorting using any provided metrics on the client or server sides.
- **Responsive Design**: Ensures the table performs well and looks good on various screen sizes.
- **Large Dataset Support**: Optimized to handle and display large amounts of data efficiently.

## Technologies Used

- React.js
- react-table library

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js (v12.0.0 or later)
- npm (v6.0.0 or later)

## Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Install the dependencies:
   
## Usage

To run the application in development mode:

This will start the development server. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Project Structure

- `src/App.js`: The main application component.
- `src/FatTable.js`: The fat table component implementation.
- `src/data.js`: Sample data for the table.

## Customization

### Adding More Data

To add more data to the table, edit the `src/data.js` file. Follow the existing data structure:

```javascript
{
  service: "service-name",
  client: {
    requests: number,
    rate: string,
    p75: string,
    p90: string,
    p99: string,
    error: string
  },
  server: {
    // Same structure as client
  }
}

This will start the development server. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.







