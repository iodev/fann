# Fast Artificial Neural Network Library

This is a fork of [libfann](https://github.com/libfann/fann) intended to keep the library maintained as the original author no longer
seems to be maintaining the project.  This is a fork of FANN git as of Jan. 2017.  It includes several bug fixes and additional features.  Pull requests are welcome.

## FANN

**Fast Artificial Neural Network (FANN) Library** is a free open source neural network library, which implements multilayer artificial neural networks in C with support for both fully connected and sparsely connected networks.

Cross-platform execution in both fixed and floating point are supported. It includes a framework for easy handling of training data sets. It is easy to use, versatile, well documented, and fast. 

Bindings to more than 15 programming languages are available. 

An easy to read introduction article and a reference manual accompanies the library with examples and recommendations on how to use the library. 

Several graphical user interfaces are also available for the library.

## FANN Features

* Multilayer Artificial Neural Network Library in C
* Backpropagation training (RPROP, Quickprop, Batch, Incremental)
* Evolving topology training which dynamically builds and trains the ANN (Cascade2)
* Easy to use (create, train and run an ANN with just three function calls)
* Fast (up to 150 times faster execution than other libraries)
* Versatile (possible to adjust many parameters and features on-the-fly)
* Well documented (An easy to read introduction article, a thorough reference manual, and a 50+ page university report describing the implementation considerations etc.)
* Cross-platform (configure script for linux and unix, dll files for windows, project files for MSVC++ and Borland compilers are also reported to work)
* Several different activation functions implemented (including stepwise linear functions for that extra bit of speed)
* Easy to save and load entire ANNs
* Several easy to use examples
* Can use both floating point and fixed point numbers (actually both float, double and int are available)
* Cache optimized (for that extra bit of speed)
* Open source, but can still be used in commercial applications (licenced under LGPL)
* Framework for easy handling of training data sets
* Graphical Interfaces
* Language Bindings to a large number of different programming languages
* Widely used (approximately 100 downloads a day)

## To Install

### On Linux

#### From Source

First you'll want to clone the repository:

`git clone https://github.com/libfann/fann.git`

Once that's finished, navigate to the Root directory. In this case it would be ./fann:

`cd ./fann`

Then run CMake

`cmake .`

After that, you'll need to use elevated priviledges to install the library:

`sudo make install`

That's it! If everything went right, you should see a lot of text, and FANN should be installed!

## To Learn More

To get started with FANN, go to the [FANN help site](http://leenissen.dk/fann/wp/help/), which will include links to all the available resources. 

For more information about FANN, please refer to the [FANN website](http://leenissen.dk/fann/wp/)
