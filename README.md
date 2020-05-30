# Keras-Training-Neural-Nets
Training Neural Nets with a small-sized data

Using several optimizer and loss functions for different classification problems:
While rmsprop is used as optimizer, as loss function:
categorical_crossentropy is used for multi-class classification problem,
binary_crossentropy is used for binary classification problem,
mse (mean_squared_error) is used for mean squared regression problems

Example:
model.compile(optimizer='rmsprop', loss='binary_crossentropy', metrics=['accuracy'])




