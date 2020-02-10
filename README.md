## Reagent Replenishment

Reagents are an integral part in medicine and healthcare. The use of reagents forms the basis of any lab and it is good to find out the reagent consumption and forecasting. In this project, there are two phases:

This project is done in two phases:

- Generation of Reagent Consumption Data
- Building a model for forecasting the reagent usage.

For above, two notebooks are created:

* reagent_datagen_extended.ipynb
The generation of data is done by the following code.
df_reagent_X = get_data(number_of_obs = 3000, reagent_name = CONST_REAGENT_AFP_NAME); df_reagent_X
After that various reagent data can be combined (appended).

* reagent_forecasting_model_nn.ipynb
Model Building for reagent forecasting is done in this file.


Note: Licensing and other information will be updated in due course.
