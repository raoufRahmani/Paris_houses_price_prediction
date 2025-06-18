Paris_house_price_prediction
# The Objective

The objective of our study is to determine the effect of some features (like the number of rooms and the surface area) on the price of a house in Paris, through a multiple linear regression model, and then improve the quality of our prediction with the ExtraTreesRegressor algorithm.

## Practical Section: Econometric Study of Real Estate Prices in Paris — Analysis Based on the DVF Dataset

* Description of the dataset used

The data used in this study is extracted from "Demande de Valeurs Foncières" (DVF) dataset, published and produced by the General Directorate of Public Finances (DGFiP), which records all real estate transactions that took place over the past five years in metropolitan France, in the Overseas Departments and Regions, with the exception of Alsace, Moselle, and Mayotte. The data is selected from the Data.gouv.fr website and concerns the territory of Paris. The DVF file contains several pieces of information for each transaction.
Here is a short explanation for each column :

valeur_fonciere: Represents the sale price of the property (also called the property value) in euros, as recorded in the transaction.

nombre_pieces_principales: This column represents the number of main rooms in the property (such as bedrooms, living rooms, dining rooms). It does not include bathrooms, kitchens, or utility rooms.

surface_bati: This refers to the built surface area of the property in square meters. It includes the total indoor living space.

longitude: This column indicates the longitudinal geographic coordinate of the property, used to locate it on a map.

latitude: This column indicates the latitudinal geographic coordinate of the property, used to locate it on a map.

* Exploratory Data Analysis

  * Checking for missing values
  * Verifying and converting data types
  * Visualizing variable distributions
  * Representing the number of main rooms

* Econometric Modeling of Real Estate Prices

  * Estimating the econometric model
  * Interpreting the regression results

* Improving Price Estimation with the ExtraTreesRegressor Model

  * Evaluating the importance of explanatory variables in our model
