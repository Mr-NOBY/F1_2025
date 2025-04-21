# F1 Race Prediction Model 🏎️

This project uses machine learning to predict Formula 1 race outcomes based on qualifying data. Currently, it's using the 2024 Grand Prix data to predict the 2025 race results.

## Current Model Status

- **Basic Model Implementation**
  - Uses qualifying session data (Q1, Q2, Q3 times)
  - Team information
  - Grid positions
  - Ensemble model combining:
    - Random Forest
    - Gradient Boosting
    - XGBoost

## Current Limitations

- No feature engineering implemented yet
- Weather data not included
- Telemetry data not utilized
- Limited historical data (only using previous year's race)

## Planned Enhancements

Throughout the 2025 season, the following improvements will be implemented:

1. **Feature Engineering**
   - Sector times analysis
   - Speed trap data
   - Tire management metrics
   - Historical performance at specific tracks

2. **Additional Data Sources**
   - Weather conditions and forecasts
   - Full telemetry data
   - Track-specific characteristics
   - Historical race patterns

3. **Model Improvements**
   - Advanced feature selection
   - Hyperparameter optimization
   - More sophisticated ensemble techniques
   - Race strategy simulation

## Tools Used

- Python
- FastF1
- Scikit-learn
- XGBoost
- Pandas

## Current Model Performance

- Mean Absolute Error: ~17.64 seconds
- Basic prediction capabilities based on qualifying performance

## Contributing

Feel free to contribute to this project. The model will be continuously improved throughout the 2025 F1 season.

## License

This project is open source and available under the MIT License.

## 2025 Predections:
- China: **81 Oscar Piastri**
- Japan: **1 Max Verstappen**
- Bahrain: **81 Oscar Piastri**
- Saudi Arabia: **1 Max Verstappen**

