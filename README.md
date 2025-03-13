# NEAT Flappy Bird

## Overview
This project is an implementation of the Flappy Bird game where an AI learns to play using the NeuroEvolution of Augmenting Topologies (NEAT) algorithm. The NEAT algorithm enables the AI to evolve over generations, improving its ability to navigate through pipes in the game.

## Features
- Flappy Bird gameplay with AI control
- Uses the NEAT algorithm for training
- Visual representation of AI learning progress
- Adjustable hyperparameters for fine-tuning the AI's performance
- Logs and statistics tracking for performance evaluation

## Requirements
Ensure you have the following dependencies installed:

```bash
pip install pygame neat-python
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/neat-flappy-bird.git
   cd neat-flappy-bird
   ```
2. Run the game:
   ```bash
   python flappy_neat.py
   ```

## Configuration
The NEAT algorithm settings are defined in the `config-feedforward.txt` file. You can modify parameters such as:
- Population size
- Mutation rates
- Number of generations

## How NEAT Works
1. A population of neural networks is initialized.
2. Each neural network controls a bird in the game.
3. The fitness function rewards birds that survive longer.
4. The best-performing networks are selected and evolved using crossover and mutation.
5. Over multiple generations, the AI improves at playing the game.

## Customization
- Modify `flappy_neat.py` to tweak game mechanics.
- Adjust `config-feedforward.txt` to experiment with different NEAT parameters.
- Implement additional visualizations to track AI performance.

## Acknowledgments
This project uses the NEAT-Python library, inspired by Kenneth O. Stanley’s NEAT algorithm for evolving neural networks.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

---
Happy coding! 🚀
