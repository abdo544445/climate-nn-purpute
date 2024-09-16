# Climate Neural Network Project

This project implements a physics-informed neural network to analyze and predict climate data, specifically temperature anomalies. It uses TensorFlow to create a custom layer that incorporates physical constraints into the model.

## Project Overview

The main components of this project are:

1. Data loading and preprocessing
2. Custom PhysicsInformedLayer implementation
3. Neural network model creation and training
4. Evaluation and visualization of results

## Dependencies

- TensorFlow
- NumPy
- pandas
- matplotlib
- xarray
- scikit-learn

## Data

The project uses climate data from the file `gistemp1200_GHCNv4_ERSSTv5.nc.gz`. This dataset contains temperature anomaly information.

## Key Features

- Custom `PhysicsInformedLayer` that applies physical constraints to the input data
- Data preprocessing and normalization
- Model training with validation
- Visualization of training and validation loss

## Usage

1. Ensure all dependencies are installed.
2. Place the climate data file in the appropriate directory.
3. Run the Jupyter notebook to execute the entire pipeline.

## Model Architecture

The neural network model consists of:
- An input layer
- A custom PhysicsInformedLayer
- A dense hidden layer with ReLU activation
- An output layer

## Results

The model is trained to predict temperature anomalies based on historical data. The README can be updated with specific results and insights once the model has been fully trained and evaluated.

## Future Improvements

- Incorporate additional climate variables
- Experiment with different model architectures
- Implement more sophisticated physical constraints
- Extend the prediction to future time periods

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Abdo Al-atrash
Email: abdoforanything1@gmail.com
