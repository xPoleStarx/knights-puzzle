# Logic Puzzle Solver

This project is a logic puzzle solver implemented in Python. It uses logical sentences and symbolic representations to solve various puzzles. The main logic functionality is defined in the `logic.py` module, and the puzzles are solved in the `puzzle.py` script.

## Installation

1. Clone the repository:
   ```
   git clone <repository_url>
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

To run the logic puzzle solver, execute the following command in the terminal:

```
python puzzle.py
```

This will solve multiple puzzles and display the solutions.

## Puzzles

The logic puzzle solver currently supports four different puzzles, which are defined in the `puzzle.py` script:

1. **Puzzle 0**: A says "I am both a knight and a knave."
2. **Puzzle 1**: A says "We are both knaves." B says nothing.
3. **Puzzle 2**: A says "We are the same kind." B says "We are of different kinds."
4. **Puzzle 3**: A says either "I am a knight." or "I am a knave.", but you don't know which. B says "A said 'I am a knave'." B says "C is a knave." C says "A is a knight."

The solver uses logical inference and deduction to determine the solutions to these puzzles based on the given statements and rules.

## Customization

You can modify or create your own puzzles by editing the `puzzle.py` script. Simply define a new knowledge base using logical sentences and symbols from the `logic.py` module. Then add the knowledge base to the `puzzles` list and run the solver.

Feel free to explore and experiment with different puzzles and logical statements.


## Acknowledgments

The logic puzzle solver is based on the concepts of formal logic and was inspired by various logic puzzle books and resources.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
