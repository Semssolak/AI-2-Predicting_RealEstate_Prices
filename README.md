# AI2-Predicting_RealEstate_Prices

 
This project demonstrates a Multiple Linear Regression model using a dataset related to real estate prices. The model is built using Python with the `pandas` and `sklearn` libraries. The dataset includes information on the area of the property, the number of rooms, the age of the building, and the price of the property.

## Project Structure

- `multilinearregression.csv`: The dataset used for training the model.
- `multiple_linear_regression.py`: Python script implementing the model.
- `README.md`: Explanation of the project and instructions for use.

## Dataset

The dataset (`multilinearregression.csv`) contains the following columns:

- `alan`: Area of the property (in square meters)
- `odasayisi`: Number of rooms
- `binayasi`: Age of the building (in years)
- `fiyat`: Price of the property (in local currency)

Example data:

| alan | odasayisi | binayasi | fiyat  |
|------|-----------|----------|--------|
| 180  | 5         | 10       | 510000 |
| 225  | 4         | 18       | 508000 |
| 260  | 3         | 2        | 548000 |

## Dependencies

To run this project, you will need the following Python libraries:

- `pandas`
- `matplotlib`
- `sklearn`

You can install these packages using pip:

```bash
pip install pandas matplotlib scikit-learn

