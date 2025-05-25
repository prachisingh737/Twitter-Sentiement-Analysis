#### Conversational Data Analysis Agent with Langchain and IBM watsonx LLM
This project demonstrates how to build an interactive conversational agent that enables natural language querying and dynamic data visualization on CSV datasets. Leveraging Langchain and IBM’s watsonx LLM (Llama 3.3), the agent understands user questions, processes data in a pandas DataFrame, and generates visual charts like bar plots, pie charts, box plots, and scatter plots in response.

# Key Features
Natural language queries on tabular data without writing code

Automatic generation of Python code for data filtering and visualization

Support for various chart types to help quickly explore data trends

Enables non-technical users to interact with data easily and make data-driven decisions

Uses Langchain’s create_pandas_dataframe_agent to integrate LLM and pandas seamlessly

# How It Works
The agent uses the language model to interpret questions, then dynamically creates and executes Python code on the data to provide answers and visuals. This approach bridges the gap between advanced data analysis and user-friendly conversational interfaces.

# Technologies Used
Python (pandas, matplotlib, seaborn)

Langchain

IBM watsonx.ai (Llama 3.3 LLM)
