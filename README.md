# Creating a Dashboard with Dash in Python

This repository provides an example of how to create a dashboard using the Dash library in Python. Dash is a powerful tool for building interactive web applications with data visualizations and user interfaces.

## Installation

To run the dashboard locally, you need to install the required dependencies. You can do this by executing the following command:

```
pip install -r requirements.txt
```

This command will install the necessary packages, including Dash and its core components. The requirements.txt is provided in the repo itself.

## Usage

To start the dashboard, run the following command:

```
python app.py
```
Here app.py is used to refer to the python file name, and it will change as per the file you would run from the __Scripts__ folder.
This command will start a local development server, and you can access the dashboard in your web browser by navigating to [http://localhost:8050/](http://localhost:8050/).

## Folder Structure

The repository has the following structure:

- `Datasets`: This folder contains the data set that I have used for making various dashboards. It has two datasets namely `automobileEDA.csv` and `airline_data.csv`.
- `Scripts`: This word contains the two python scripts for making the dashboards using the datasets given in this repo. 
- `requirements.txt`: This file lists all the required package and their versions.
- `README.md`: This file provides instructions and information about the project.

## Customizing the Dashboard

You can customize the dashboard to suit your specific needs. Here are a few areas you can modify:

- **Layout**: The layout of the dashboard is defined in the `app.layout` section of the `app.py` file. You can modify the structure and appearance of the dashboard by adding, removing, or rearranging the components.
- **Graphs and Visualizations**: The example provided in the `app.py` file includes a basic bar chart. You can customize the graph by modifying the data, layout, and other properties of the `dcc.Graph` component. Dash provides various graph types and customization options, allowing you to create rich and interactive visualizations.
- **Callbacks**: Callback functions are used to update the dashboard based on user interactions. In the `app.py` file, there is an example callback function `update_graph()` that can be modified to update the graph based on user input or other events.

Feel free to explore the Dash documentation for more information on customizing and extending your dashboards: [https://dash.plotly.com/](https://dash.plotly.com/)

## Acknowledgments

- The Dash library, developed by Plotly, provides a powerful framework for creating interactive web applications and dashboards.
- The example in this repository is adapted from the official Dash documentation and showcases the basic usage of the library.

## Contact

For any questions or inquiries, please contact [adrijeguha37@gmail.com](adrijeguha37@gmail.com).

Happy dashboarding!