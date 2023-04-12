Our second implementation supports a verbose mode that allows you to observe gradual changes to the model during optimization.

The problem is that the verbose mode is too verbose - it prints out thousands of lines of text optimizing a simple model.

Add a parameter verbose_interval that will make the verbose mode less verbose. A value of 100 should print for every 100 optimizations etc.

Try to do an optimization where you get 10 prints, and plot the suboptimal intermediate results in a figure.