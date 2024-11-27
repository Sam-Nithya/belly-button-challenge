# belly-button-challenge


This project visualizes data on the belly button biodiversity dataset, including interactive charts that display the demographics and bacteria cultures of various test subjects.

## Files Overview

- **`app.js`** (located in `static/js/` folder): This JavaScript file contains the code for building the interactive charts and demographic panel. It uses the D3.js library to load and process data from `samples.json` and render the visualizations on the webpage.

- **`index.html`**: The HTML file that serves as the main entry point for the dashboard. It includes the structure of the webpage, such as the layout for displaying the interactive charts and dropdowns, and links to the necessary CSS (Bootstrap) and JavaScript (D3 and Plotly) libraries.

- **`output.jpeg`**: This file is an image output generated from the visualizations. You can view it as a static representation of the data that was processed.

- **`samples.json`**: This is the data file in JSON format that contains the information about each test subject, including demographic details and bacterial species found in their belly buttons. This data is loaded by `app.js` to generate the interactive charts.

- **`README.md`**: This file, which provides an overview of the project, the files in the project, and how to use it.

## How to Run

To run this project locally, follow these steps:

1. **Clone the repository**:
   If you haven't already cloned the repository, do so with the following command:

   ```bash
   git clone https://github.com/Sam-Nithya/belly-button-challenge.git
