# Rainfall-Predictions
> Build a predictive model that leverages historical weather data (including whether it rained on the current day) to forecast whether it will rain on the next day ('RainTomorrow').

![Rain](https://github.com/Vengatesan-K/Amazon-Phone-Price-Analysis/assets/128688827/e5914890-ef3f-41ae-8561-4b12f081677c)

***

<table align="center">
    <tr>
        <td width="10%">
            <img src="https://png.pngtree.com/png-vector/20231127/ourmid/pngtree-rain-red-flat-icon-isolated-clouds-png-image_10722735.png">
        </td>
        <td>
            <div align="center" style="font-size:200%">
                <font color="#21618C">
                    <b>Tomorrow's Rain : Today's Clues</b> 
                </font>
            </div>
        </td>
    </tr>
</table>

<hr>


<span style="font-family:Comic Sans MS"> 🎯 The dataset you're referring to, encompassing Australian weather data from 2008 to 2017, includes additional columns such as 'RainToday,' with the primary target of interest being the 'RainTomorrow' column.</span>



<span style="font-family:Comic Sans MS"> 🎯 This dataset is valuable for predictive analysis, particularly in understanding and forecasting whether it will rain the following day based on various weather attributes and conditions recorded over the specified period.</span>



<span style="font-family:Comic Sans MS"> 🎯 By utilizing this dataset, machine learning models can be trained to discern patterns, relationships, and dependencies between various weather parameters (like temperature, humidity, wind speed, atmospheric pressure, etc.), the occurrence of rain on a particular day ('RainToday'), and whether rain will persist to the next day ('RainTomorrow').</span>

<hr>




<table align="center">
    <tr>
        <td width="6%">
            <img src="https://cdn3.iconfinder.com/data/icons/ui-9/512/question_database-1024.png">
        </td>
        <td>
            <div align="center", style="font-size:200%">
                <font color="#21618C">
                    <b>About Dataset</b> 
                </font>
            </div>
        </td>
    </tr>
</table>

| Field         | Description                                           | Unit            | Type   |
| ------------- | ----------------------------------------------------- | --------------- | ------ |
| Date          | Date of the Observation in YYYY-MM-DD                 | Date            | object |
| Location      | Location of the Observation                           | Location        | object |
| MinTemp       | Minimum temperature                                   | Celsius         | float  |
| MaxTemp       | Maximum temperature                                   | Celsius         | float  |
| Rainfall      | Amount of rainfall                                    | Millimeters     | float  |
| Evaporation   | Amount of evaporation                                 | Millimeters     | float  |
| Sunshine      | Amount of bright sunshine                             | hours           | float  |
| WindGustDir   | Direction of the strongest gust                       | Compass Points  | object |
| WindGustSpeed | Speed of the strongest gust                           | Kilometers/Hour | object |
| WindDir9am    | Wind direction averaged of 10 minutes prior to 9am    | Compass Points  | object |
| WindDir3pm    | Wind direction averaged of 10 minutes prior to 3pm    | Compass Points  | object |
| WindSpeed9am  | Wind speed averaged of 10 minutes prior to 9am        | Kilometers/Hour | float  |
| WindSpeed3pm  | Wind speed averaged of 10 minutes prior to 3pm        | Kilometers/Hour | float  |
| Humidity9am   | Humidity at 9am                                       | Percent         | float  |
| Humidity3pm   | Humidity at 3pm                                       | Percent         | float  |
| Pressure9am   | Atmospheric pressure reduced to mean sea level at 9am | Hectopascal     | float  |
| Pressure3pm   | Atmospheric pressure reduced to mean sea level at 3pm | Hectopascal     | float  |
| Cloud9am      | Fraction of the sky obscured by cloud at 9am          | Eights          | float  |
| Cloud3pm      | Fraction of the sky obscured by cloud at 3pm          | Eights          | float  |
| Temp9am       | Temperature at 9am                                    | Celsius         | float  |
| Temp3pm       | Temperature at 3pm                                    | Celsius         | float  |
| RainToday     | If there was rain today                               | Yes/No          | object |
| RainTomorrow  | If there is rain tomorrow                             | Yes/No          | float  |

ℹ️ ***This dataset contains observations of weather metrics for each day from 2008 to 2017.***
