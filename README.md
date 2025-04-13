# Catan Balancer

This project is a Python-based tool for generating balanced Catan game boards. It ensures that the placement of tiles, ports, and dice roll numbers adheres to specific rules to create a fair and enjoyable game experience.

## Rules for Balanced Board Generation

The following rules are followed to ensure a balanced Catan board:

1. No two brick or stone tiles next to one another.
2. No three sheep, wheat, or wood tiles connected to each other.
3. No resource tiles too close to their matching port.
4. No two of the same number next to each other.
5. No sixes or eights next to each other.
6. No two of the same number on the same resource.
7. No sixes or eights on the same resource.

## Requirements

- Python 3.7 or higher
- Matplotlib
- NumPy

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## Usage

Run the script to generate and visualize a balanced Catan board:

```bash
python HALAT-CatanBalancer.py
```

The script will display the board and print the number of failed attempts to balance tiles and numbers.

## Configuration

- `defaultPortLocations`: Set to `1` to use predefined port locations, or `0` to randomize them.
- `portCheck`: Set to `1` to enforce port-related tile restrictions, or `0` to disable them.

## Output

- A visual representation of the Catan board, including:
  - Hexagonal tiles with resource types.
  - Ports with their respective resource types.
  - Dice roll numbers on each tile.
- Console output showing the number of failed attempts to balance the board.

## License

This project is based on the original repository [CatanBalancer](https://github.com/haveaLukeatthis/CatanBalancer). Please refer to the original repository for licensing details.