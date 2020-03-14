# torch-notes

1. Don't accumulate loss to Average metric without detaching from the computation graph. If you forget, it might cause GPU memory problem


2. Remember to set network.eval() at test time
