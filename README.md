# Mini VGG from scratch

- An attempt to make a tiny VGG model from scratch

## Structure

### Convolutional Block
- (Conv2D + BatchNormalization + ReLU) * 2 + MaxPool2D + Dropout

### FC Block
- GlobalAveragePooling2D + Dense + BatchNormalization + ReLu + Dropout + Dense(softmax)