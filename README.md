# Project paper work

This contains the illustrations to the project paper regarding predictions of dynalmical systems with Graph neural networks. The experiments are done on heat diffusion and wave propagation systems.

Note that some illustrations might be innacurate due to bugs in matplotlib.


_Heat diffusion_


Here is a heat diffusion for a longer time period with a larger graph for illustration purposes.

![](./long_time_graph_50hot.gif)

Data:

With 10x10 grid graph

Test data:

![](./heatwave/test0.gif)

Graph network prediction:

![](./heatwave/pred0.gif)

With 10x10 grid graph with 10 disconnected nodes

Test data:

![](./heatwave/test10.gif)

Graph network prediction:

![](./heatwave/pred10.gif)

With 10x10 grid graph with 30 disconnected nodes

Test data:

![](./heatwave/test30.gif)

Graph network prediction:

![](./heatwave/pred30.gif)


_Wave propagation_

Here are two wave propagations for longer time period with larger graphs for illustration purposes.

![](./heatwave/long_time_test.gif)


![](./heatwave/long_time_test2.gif)

Data:

With 50x50 grid graph

Test data:

![](./heatwave/test_no.gif)

Graph network prediction:

![](./heatwave/prediction_no.gif)

With 50x50 grid graph with 40 random disconnected nodes

Test data:

![](./heatwave/test_rand.gif)

Graph network prediction:

![](./heatwave/prediction_random.gif)

With 50x50 grid graph with walls of disconnected nodes

Test data:

![](./heatwave/test_topbot.gif)

Graph network prediction:

![](./heatwave/prediction_topbot.gif)
