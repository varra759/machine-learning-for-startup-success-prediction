# Prosperity Prognosticator: Machine Learning for Startup Success Prediction

Prosperity Prognosticator is a machine learning–powered web application that predicts the success probability of a startup based on 76 real-world features. It is designed to assist entrepreneurs, investors, and analysts in evaluating startup potential using data-driven insights.

## Project Overview

This project integrates the complete machine learning lifecycle with a web deployment interface:

- Data collection and cleaning
- Exploratory data analysis (univariate and multivariate)
- Feature engineering and encoding
- Model building using Random Forest Classifier
- Performance evaluation using classification metrics
- Web application development using Flask
- Frontend interface for user input and result visualization
- REST API for programmatic access
- Interactive HTML templates and a comprehensive Jupyter Notebook

## Technologies Used

- **Frontend**: HTML5, CSS3, Bootstrap, Jinja2 templates
- **Backend**: Python 3, Flask
- **Machine Learning**: Scikit-learn (RandomForestClassifier)
- **Visualization**: Seaborn, Matplotlib
- **Notebook**: Jupyter Notebook
- **Deployment**: Localhost or compatible cloud hosting (Render, Railway, etc.)

## Folder Structure

Prosperity-Prognosticator/
├── app.py # Flask backend application
├── random_forest_model.pkl # Trained machine learning model
├── Startup_Success_Model.ipynb # Jupyter Notebook (model building and analysis)
├── templates/ # Frontend templates
│ ├── index.html
│ ├── home.html
│ ├── adaptivity.html
│ └── results.html


## How to Run Locally

1. Clone the repository:
2. Install required packages:
3. Run the Flask server:
4. Open your browser and go to: http://127.0.0.1:5000/


## Model Performance

- Accuracy: 95%
- F1 Score: 0.95
- ROC-AUC: 0.94
- Precision-Recall AUC: 0.97

## Features

- Accepts 76 input features related to funding, milestones, geography, and startup characteristics
- Predicts startup success or failure
- Displays confidence levels and success probability
- Shows AI-based insights and recommendations
- User-friendly web interface with dynamic feedback
- REST API endpoint at `/api/predict` for integration with external tools

## Team Contributions

- **Rajdeep**: Team lead, model building,frontend development(`home.html`), backend development (`app.py`), final code review
- **Biswadeep**: Model evaluation, testing, result visualization (`results.html`)
- **Bhagat**: Data collection, preparation, univariate and multivariate analysis, `adaptivity.html`
- **Rajat**: Data analysis and visualization, frontend development (`index.html`), debugging

## License

This project is licensed under the MIT License.

## Acknowledgments

- Dataset source: Crunchbase and secondary resources
- Model: Random Forest with one-hot encoded categorical features
- Tools: Google Colab, VS Code, GitHub

## Included Notebook

The file `Startup_Success_Model.ipynb` contains:

- Full exploratory data analysis
- Preprocessing pipeline
- Feature importance visualization
- Model training and evaluation steps
- Graphs and metrics for interpretability
