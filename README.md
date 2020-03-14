# torch-notes

1. Don't accumulate loss to Average metric without detaching from the computation graph. If you forget, it might cause GPU memory problem


2. Remember to set network.eval() at test time


3. Convert tensor to image for visualization

  https://discuss.pytorch.org/t/simple-way-to-inverse-transform-normalization/4821/6

4. Dataloader will automatically convert numpy data type in Dataset to corresponding torch data type


5. Inherit nn.Module for custom loss

6. Input of torch transforms must be PIL image
