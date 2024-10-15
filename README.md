
# Soccer Simulation - Organization

## Overview
The Soccer Simulation Organization is focused on developing advanced and realistic soccer simulators. Our projects focus on generating virtual soccer teams with players having dynamically generated stats, allowing users to simulate teams, analyze player performance, and explore soccer management strategies.

We leverage Python and other modern technologies to bring an immersive experience to our users, providing them with various tools to enhance their soccer simulation needs.

## Key Projects
### 1. **Soccer Simulation Backend**
This project provides the core backend logic for generating and simulating soccer teams. Players are dynamically created with realistic stats based on their positions, attributes, and roles. The backend exposes API endpoints for generating teams, retrieving player data, and more.

- **Technologies**: Python, FastAPI, Pydantic
- **Features**:
  - Randomized team and player generation
  - Dynamic stat adjustments based on player roles
  - API endpoints for fetching player and team information

### 2. **Player Stats Generator**
The Player Stats Generator is a comprehensive system that dynamically assigns attributes to players based on various factors such as position, fitness, age, and more. The system calculates individual player stats like Composure, Physical Power, Dribbling, and much more.

- **Key Features**:
  - Position-specific player attribute adjustments
  - Complex balancing algorithms for realistic player behavior
  - Customizable configurations for different positions

## Contributing
We encourage the community to contribute to the Soccer Simulation project! Here’s how you can get started:

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Open a Pull Request

We welcome contributions of all kinds, whether it’s fixing bugs, optimizing performance, or adding new features!

## Community
Join our community and be part of something bigger!

- [Discord](#)
- [Slack](#)
- [Twitter](#)
- [GitHub Discussions](#)

## Installation

### MacOS/Linux
```bash
# Clone the repository
git clone https://github.com/SoccerSimulator/Soccer-Simulation-BE.git
cd Soccer-Simulation-BE

# Install dependencies using Pipenv
pipenv install

# Run the FastAPI server
pipenv run uvicorn app.main:app --reload
```

### Windows
```bash
# Clone the repository
git clone https://github.com/SoccerSimulator/Soccer-Simulation-BE.git
cd Soccer-Simulation-BE

# Install dependencies using Pipenv
pipenv install

# Run the FastAPI server
pipenv run uvicorn app.main:app --reload
```

## License
This project is licensed under the MIT License.

## English - Hebrew positions translation
```txt
שוער -  goalkeeper
בלם - defenders
מגנים -  full backs
קשרים -  Midfielder
חלוצים - Striker
וינגר - Wingers
```

We hope this project becomes an essential part of your soccer simulation journey!
