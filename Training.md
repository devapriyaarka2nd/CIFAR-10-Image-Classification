# Training Instructions

## Step 1

Load CIFAR-10 dataset.

## Step 2

Normalize images.

## Step 3

Apply Data Augmentation.

## Step 4

Build CNN architecture.

## Step 5

Compile model.

Optimizer:
- Adam

Loss:
- Categorical Crossentropy

Metric:
- Accuracy

## Step 6

Train model

```python
batch_size = 64
epochs = 300
```

Early stopping and ReduceLROnPlateau are used to prevent overfitting.

## Step 7

Evaluate the trained model on the test set.
