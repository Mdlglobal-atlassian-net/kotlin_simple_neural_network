# Kotlin Simple Neural Network

This is a simple neural network application that will suggest a LIGHT or DARK font for a given background color.

The training/predicting user interface was built with [TornadoFX](https://github.com/edvin/tornadofx).

![](demo.gif)


Currently there are three implementations: 

1) [Simple RGB formula](https://stackoverflow.com/questions/1855884/determine-font-color-based-on-background-color#1855903) 
2) My feed-forward brute force implementation (no backpropagation)
3) [ojAlgo! Neural Network](http://www.ojalgo.org/)
4) [DeepLearning4J](https://deeplearning4j.org/)

For this simple toy example, ojAlgo seems to perform the best (and is the most lightweight and simplest to implement). DL4J is definitely more heavyweight (and has many dependencies) but is a more robust framework for larger, data-intensive deep learning problems in production. 

Note also there is now a button to pre-train 1345 categorized colors. 

Tariq Rashid's book [Build Your Own Neural Network](https://www.amazon.com/Make-Your-Own-Neural-Network/dp/1530826608/) is a tremendous resource, as well as [3Blue1Brown's Video](https://www.youtube.com/watch?v=aircAruvnKk&list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi). [Grokking Deep Learning](https://www.manning.com/books/grokking-deep-learning) is probably the most thorough and useful resource when you are ready to deep-dive into neural network.s 


