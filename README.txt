# CSE6242-Stock-Viz-Helper
## DESCRIPTION
`Stock-Viz-Helper` consists of two charts: interactive technical analysis and stock close price prediction. Interactive technical analysis aims to make stock technicla terms easier to pick up with a collection of tools, such as selectable components, hovering explanation text boxes, and extended explanations. Stock prediction chart offers insight from our machine learning model with prediction of 25 stock close prices for 7 days.

### File description
- Images: The folder storing images for concept explanations.
- dist: Techan.js package. The main package to implement our project.
- plot: The source code of interactive technical analysis chart.
- prediction: The source code of stock close price prediction chart.
- src: The source code for Techan.js components.
- stock_data: The folder containing `combined_stocks.csv` used by interactive technical analysis chart and `combined_stocks_with_predictions.csv` for stock close price prediction chart.
- model: The folder contains `stock_price_prediction_dva.ipynb` for model training and prediction

## INSTALLATION

### Visualization
- A python environment is needed if you intend to run the code with `python -m http.server`
- Install `Live Server` extension from VS Code for your preference

### Machine Learning Model
- Run `pip install -r requirements.txt` from the `model` folder to install required packages
 
## EXECUTION
 
### Visulization
We offer two methods to run our application.

- In the prohect folder, run `python -m http.server 8000`.
- Use `Live Server` extension from VS Code. Open `index.html` in either `plot` folder or `prediction` folder. Click the `Go Live` icon at the bottom-right corner and lauch the applcation.

### Machine Learning Model

- Follow the execution flow in the `stock_price_prediction_dva.ipynb`