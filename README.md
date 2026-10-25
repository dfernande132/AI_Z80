# Artificial Intelligence for the Z80

**"If you can build it in 8 bits, you really understand it"**

This repository contains the programs and resources of the book **"Artificial Intelligence for the Z80: Computer Science in BASIC"**, written by **José Daniel Fernández Santos**.

Here you'll find source code designed for the ZX Spectrum (classic and Next) that lets you explore everything from the foundations of computing to modern neural networks, all on the architecture of the legendary Zilog Z80 processor.

> Spanish edition: *Inteligencia Artificial para el Z80* — repository [IA_Z80](https://github.com/dfernande132/IA_Z80).

---

## 📖 About the Book
Is it possible to combine the raw simplicity of 1980s BASIC with the theoretical sophistication of Artificial Intelligence? This book shows that it is.

Using a Z80 processor, we'll take an educational journey to demystify AI, breaking open the "black box" of today's algorithms. You'll learn to optimize code, manage memory and build, line by line, regression and classification algorithms and neural networks. It's a book for programmers, retro enthusiasts and students who want to understand the essence of computing without the distractions of modern libraries.

---

## 📂 Repository Contents
This repository is a companion for readers of the book. The files are organized by chapter to make it easy to follow the lessons.

### File formats:
* **`.bas.txt`**: Plain text files. Ideal for reading the code on a PC, copying snippets or studying the logic without an emulator.
* **`.bas`**: Files in **+3DOS** system format. Ready to be loaded directly on a **ZX Spectrum Next or 128K**, on emulators, or written to floppy disks/SD cards.
* **`.tap`**: Tape files, ready to be loaded on a classic ZX Spectrum or an emulator.

### Usage policy:
These files are shared so that those who have bought the book can run all the tests they want, modify the code and experiment with the parameters of the algorithms as they please. The best way to learn is by breaking the code and rebuilding it!

---

## 🚀 Programs by Chapter

### Part I: Foundations and Tools
* **Chapter 1**: `Bernoulli.bas` (The first algorithm: Ada Lovelace).
* **Chapter 2 (Algorithms)**:
    * Efficiency labs: `steps.bas`, `steps2.bas`, `steps3.bas`.
    * Visualization: `drawG.bas`, `drawGwithTimes.bas`.
    * Sorting: `bubble.bas`, `shell.bas`, `quick.bas`, `quickR.bas`, with `sorting.bas` and `genRand.bas` to combine them using `MERGE`.
    * Fixed-point arithmetic: `fixedPoint.bas`.

### Part II: Classical (Symbolic) AI
* **Chapter 3 (Expert Systems)**: `inference.bas` (Inference engine for diagnosis).
* **Chapter 4 (NLP)**: `Eliza.bas` (Implementation of the famous conversational chatbot).
* **Chapter 5 (Heuristic Search)**: `randomGame.bas`, `treeGame.bas`, `minimaxGame.bas` and `pruningGame.bas` (Evolution of the AI for tic-tac-toe).

### Part III: Supervised Learning
* **Chapter 6 (Linear Regression)**: `regression.bas` and `Moa.bas` (Analysis of CO2 trends).
* **Chapter 7 (k-NN Classification)**: `knn.bas` (Nearest-neighbor classifier).
* **Chapter 8 (Naive Bayes)**: `Bayes.bas` (Probabilistic classification).

### Part IV: Unsupervised Learning
* **Chapter 9 (Clustering)**: `intuition.bas`, `kmeans.bas` and `classification.bas` (Data clustering).

### Part V: Neural Networks
* **Chapter 10 (The Perceptron)**:
    * `TheMachineEye.bas` (Shape recognition with a single neuron).
    * `seeingFives.bas` (Recognition of the digit 5).
* **Chapter 11 (Multilayer Networks)**:
    * `sigmoid.bas` (Calculation of the sigmoid LUT).
    * `multiClass.bas` (Multiclass systems).
    * `digitTraining.bas` and `viewer.bas` (Backpropagation in 8 bits).
    * `digitPredFILE.bas` (Digit recognizer that loads the model from files).
    * `digitPredDATA.bas` (Digit recognizer that loads the model from DATA).
    * `A.DAT`, `B.DAT`, `C.DAT` and `D.DAT` (Trained weights and biases, so you don't have to wait for the training).

### Part VI: Simulation and Life
* **Chapter 12**: `GameOfLife` (Conway's Game of Life).
    * Bonus: `GameLifeZX.tap` (Game of Life in assembler for the ZX Spectrum, by Juan Antonio Rubio García) and `GameLifeCPC.cdt` (version for the Amstrad CPC 6128).

---

## 🛠️ Recommended Requirements
Although many programs run on a standard 48K/128K Spectrum, for the Neural Networks and Regression chapters we recommend a **ZX Spectrum Next** (or emulators such as CSPECT or ZESARUX) to take advantage of the 28 MHz speed and reduce training times.

---
**I hope you enjoy exploring artificial intelligence in its purest form!**

## Happy coding! 📟
