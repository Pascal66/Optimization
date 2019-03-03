# Optimization

Package used for mathematical optimization.
It implements multiple different stochastic gradient descent variations used
to optimize multivariate functions.

## Usage

Your object that needs to be optimized has to implement Optimizable.
Then create a new Optimizer and override keepTraining to tell it when to stop,
give it your object and call the optimization algorithm you like!
(Adam is recommended!)

## Getting Started

Simply download this repository and add it to your project as a new package!
Done!

## TODO

 - [ ] Argument validation
 - [x] Documentation

## License (MIT)

MIT License

Copyright (c) 2019 Sebastian Gössl

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
