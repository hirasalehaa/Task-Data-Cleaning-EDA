# Task-Data-Cleaning-EDA

Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.
Bar Chart:
import plotly.express as px

# Prepare data
genders = ["male", "female"]
counts = [25, 75]

# Create bar chart
fig = px.bar(x=genders, y=counts, color=genders)

# Add title
fig.update_layout(title="Distribution of Genders")

# Show plot
fig.show()
