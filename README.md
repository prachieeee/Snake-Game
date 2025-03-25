
# Snake-Game using Reinforcement Learning

This repository contains a Snake game trained using Reinforcement Learning (RL). The agent learns to play the game using Deep Q-Learning, optimizing its movements to maximize the score while avoiding collisions.

## Features
- **Deep Q-Learning**: Uses a neural network to learn optimal actions.
- **Gym Environment**: Custom-built game environment for training.
- **PyTorch Implementation**: Efficient model training using PyTorch.
- **Visualization**: Watch the agent improve over time.
- **Logging & Analytics**: Tracks rewards, losses, and scores.

## Installation

Clone the repository:
```sh
git clone https://github.com/your-username/snake-rl.git
cd snake-rl
```

Install dependencies:
```sh
pip install -r requirements.txt
```

## Usage

To train the model:
```sh
python train.py
```

To play using the trained model:
```sh
python play.py
```

## Training Details
- The agent is trained using the **Deep Q-Network (DQN)** algorithm.
- The state space consists of the snake's position, direction, food position, and obstacles.
- The reward function encourages eating food and penalizes collisions.
- Experience replay is used for stable learning.

## Results
- The agent improves over time, learning to optimize movement and avoid obstacles.
- Training logs and graphs are saved for performance analysis.

## Future Improvements
- Implement **Double DQN** for more stable learning.
- Use **Prioritized Experience Replay** to enhance training efficiency.
- Experiment with different neural network architectures.

## Contributing
Feel free to submit issues or pull requests to improve this project.

## License
This project is licensed under the MIT License.

---
Made with ❤️ by [prachieeee]
