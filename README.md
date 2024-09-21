# Python Script Generator
<div style="display: flex; justify-content: center; align-items: center;">
  <img src="https://github.com/user-attachments/assets/25de3c9a-d73a-4200-8ac8-d6a2416e6e3d" style="width: 500px; height: auto; margin-right: 20px;" />
  <img src="https://github.com/user-attachments/assets/4069bf44-a6f3-4eac-922f-b1df086a69dd" style="width: 500px; height: auto;" />
</div>

**Try the deployed app [here]([https://mito-data-cleaning-demo.streamlit.app/](https://mito-script-generator-demo.streamlit.app/))**

Welcome to the **Python Script Generator Demo**! This app simplifies data manipulation by allowing you to interact with your data through an Excel-like interface while generating Python scripts based on your actions.

## Features

- **Intuitive Interface**: Manipulate your data using familiar spreadsheet functions.
- **Automatic Script Generation**: As you transform your data, the app records each step and generates the corresponding Python code.
- **CSV Export**: Download your cleaned data as a CSV file.

## Getting Started

1. **Import Your Data**: Upload your dataset into the app via Streamlit.
2. **Manipulate Your Data**: Use Mitosheet to clean and transform your data as needed.
3. **Download and Review**: Once you’re finished, download your cleaned data as a CSV file and view the generated Python scripts for each transformation step.

## Why is this app useful?
**Streamlined Data Processing**: Quickly clean and transform data for analysis without needing extensive programming knowledge, making it accessible for non-developers.

## Mito Streamlit Package 
Learn more about the Mito Streamlit package [here](https://docs.trymito.io/mito-for-streamlit/getting-started) or following the [getting started guide](https://docs.trymito.io/mito-for-streamlit/create-an-app).

### Run Locally 
1. Create a virtual environment:
```
python3 -m venv venv
```

2. Start the virtual environment:
```
source venv/bin/activate
```

3. Install the required python packages:
```
pip install -r requirements.txt
```

4. Start the streamlit app
```
streamlit run main.py
```

## About Mitosheet
This app is a demo of the Mitosheet library. To learn more about Mitosheet and its capabilities, check out the [Mitosheet documentation](https://github.com/mitaas/mito).

Happy coding!
