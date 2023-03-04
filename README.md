
# Our Solution for T-AIMS Challenge

Academic Grand Challenge on Climate Change

### Problem Statement
To develop solutions that can predict the occurrence of heat waves and the Air Quality Index (AQI) for Tier-2 cities of Telangana. The goal is to come up with innovative and effective ways to mitigate the impact of heat waves and poor air quality on the health and well-being of the residents in these cities. The solutions should be based on data-driven models and take into account various factors such as temperature, humidity, wind speed, and pollution levels.


### Demo




### Our solution
 - > In our project, data for Telangana's Tier 2 cities is fetched and stored in a CSV file. Using this data, we will then undertake data analysis and preprocessing in order to gain insightful information.

- > Using MAPE to assess the model's correctness, we were able to obtain a score that was reasonably low, indicating that the AQI prediction was accurate 

- >  Using maximum temperature data, we also forecasted heat waves. Overall, our approach offers a trustworthy way to anticipate AQI and heat waves in Telangana's Tier 2 cities.

- > Our solution also involves retraining our model every seven days to improve the accuracy of our predictions. To achieve this, we collect current data to update the historical data used to train the model. By doing so, our model can make more accurate predictions based on the most recent data available.




### Our Model

- >  Our project involves the use of ***SARIMAX model***, a powerful time series forecasting model that can take into account both the time component and exogenous variables such as weather data. SARIMAX model allows us to accurately predict the AQI and identify periods of heat waves using historical data and current weather data obtained from APIs.
- > We evaluated the model's accuracy using Mean Absolute Percentage Error (MAPE). Our project also involved predicting heat waves using the temperature data obtained from Open Weather API.
- > Model Accuracy for :
- > Model Workflow 

<img width="773" alt="Screenshot 2023-03-04 at 9 35 23 PM" src="https://user-images.githubusercontent.com/96522398/222916487-ec0343a8-b1f4-4ee6-89fc-099cb7d716d3.png">


### Project Features

- Real-time AQI and Pollutants such as PM2.5, PM10, SO2, NO2 

- Real-time Weather with Temperature, Humidity and Wind Speed

- AQI and weather models are retrained every seven days, ensuring that the predictions remain accurate and relevant.

- The project also includes an interactive graph that displays the Predicted AQI data and weather Data for the selected city
### Installation



Clone the repository using the following command:
```bash
git clone https://github.com/iamneo-production/5e43a363-c20b-41af-8510-d632bdd2aa81.git
```
Change directory to the project directory:
```bash
cd 5e43a363-c20b-41af-8510-d632bdd2aa81
```
Activate the virtual environment:
```bash
source env/bin/activate
```
Install the required packages:
```bash
pip install -r requirements.txt
```
Start the application:
```bash
python3 app.py
```
## Screenshots

![f617c9b1-b578-4faf-9239-fabeda7262a3](https://user-images.githubusercontent.com/96522398/222923174-428ce240-e092-47a2-a948-85537946566e.jpg)

![f857c707-0a6d-4c4a-a086-c8c7f2f8dff3](https://user-images.githubusercontent.com/96522398/222923182-d65e8bb5-d464-4e76-8bdc-802224ad62e7.jpg)

![512698fd-8730-49c1-845d-7649ef82b372](https://user-images.githubusercontent.com/96522398/222923200-70626cac-b87a-4784-ba6f-5b9b26cfa2b9.jpg)

![147c2c4e-5f69-4126-b8f8-c04e818486f4](https://user-images.githubusercontent.com/96522398/222923207-705e69cf-89cd-4c21-99a0-9f92eb385d35.jpg)

![6595592a-9c7c-4173-b9bc-6d7a3775a7c3](https://user-images.githubusercontent.com/96522398/222923223-dd558d97-c03f-4e49-9f93-477ad665498b.jpg)

![b8889171-3395-4f7a-a288-e0eba3adf30e](https://user-images.githubusercontent.com/96522398/222923249-f3c67b10-e49a-457b-8276-7a47a094d4aa.jpg)

![ac20d546-1a3f-4155-9d6c-6c9b5dd263f9](https://user-images.githubusercontent.com/96522398/222923257-014adf01-4f73-41b8-861c-0fffb4ac01e0.jpg)


### Team Members

- [Aditya Gohil](https://github.com/Adi0015)
- [Aman Yevge](https://github.com/amanyevge)
- [Ria Kokate](https://github.com/RiaKokate)
- [Sanika Chaudhari](https://github.com/Sanika0701)

