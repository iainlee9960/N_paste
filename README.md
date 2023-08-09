# Project Readme: Solving the n_paste Problem

## Overview

The n_paste Problem Solver is a software application designed to determine the optimal sequence of copy and paste operations to maximize the number of occurrences of a given word in a document, while minimizing the total number of operations used. This problem can be seen as an optimization challenge, where the goal is to find the best strategy for duplicating a word using the operations of selection, copy, and paste.

## Problem Statement

Given a blank document containing a single word, the following operations are available:
- Control + A: Selects all the text in the document.
- Control + C: Copies the currently selected text.
- Control + V: Pastes the copied text into the document.

The objective is to find the sequence of operations (copy, paste) that results in the highest possible number of occurrences of the word in the document, while minimizing the total number of operations used.

## Features

1. Optimal Strategy Calculation: The core functionality of this application is to determine the optimal sequence of copy and paste operations to achieve the highest number of occurrences of the word with the fewest operations.

2. User Interaction: Users can input the word they want to maximize in the document, and the application will calculate the optimal strategy accordingly.

3. Visualization: The application can provide visual feedback, showing the steps and resulting document after each operation.

4. Efficiency Analysis: The application can provide insights into the efficiency of the chosen strategy in terms of total operations used and word occurrences achieved.

## Installation

1. Clone the repository from GitHub:

```
git clone https://github.com/your-username/n-paste-problem-solver.git
cd n-paste-problem-solver
```

2. Ensure you have Python 3 installed on your system.

3. Install the required dependencies using pip:

```
pip install -r requirements.txt
```

## Usage

1. Run the program by executing the main script:

```
python main.py
```

2. Follow the on-screen instructions to input the word you want to maximize in the document.

3. The program will calculate and display the optimal sequence of copy and paste operations, along with the resulting document and relevant efficiency metrics.

## Examples

Example 1: Maximizing the word "hello" using a limited number of operations:

```
Enter the word to maximize: hello
```

Output:

```
Optimal Operations:
1. Copy (1 operation)
2. Paste (1 operation)
3. Paste (1 operation)
4. Paste (1 operation)

Resulting Document: hellohellohellohello

Total Operations Used: 4
Word Occurrences Achieved: 4
```

## Contributions

Contributions to this project are encouraged! If you have ideas for improving the algorithm, adding visualization features, or enhancing the user interface, feel free to open an issue or submit a pull request on the GitHub repository.


## Acknowledgments

We would like to acknowledge the open-source community and the developers of the Python programming language for their contributions that made this project possible. Additionally, a special thanks to those who provided insights and feedback during the development process.
