# Getting Started with EPICS project

For now ignore the .gitkeep file in frontend, backend and in ML. don't worry about it.


# Tech Stack
ML - PYTHON, PYTORCH
BACKEND - DJANGO, DRF
FRONTEND - REACTJS (use jsx files)

# MAIN WORKFLOW OF PROJECT 

1.  Fetching live urban weather data from the OpenWeatherMap API.
2.  Fetching corresponding data from a mapped rural location.
3.  Calculating the Urban Heat Island (UHI) index based on temperature and humidity differences.
4.  Feeding the live urban data into a trained  Random Forest Machine Learning model to predict the UHI severity.
5.  Displaying a complete dashboard showing the official classification, the Urban vs. Rural comparison, and actionable recommendations for tree planting.