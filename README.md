# std::venom

std::venom is a custom Battle Snake built using C++ to compete in the Battle Snake arena! This project is designed to be efficient and adaptive, leveraging algorithms for real-time decision making in a competitive snake environment.

## Features
- Pathfinding algorithms to navigate the snake arena
- Real-time decision-making for avoiding obstacles and enemies
- Efficient handling of game state updates

## Getting Started

### Prerequisites
- **C++17** or higher
- **CMake** (for building the project)
- **Make** (for building on Linux/macOS) or **Visual Studio** (for building on Windows)

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/std-venom.git
    cd std-venom
    ```

2. Build the project:

    For Linux/macOS:
    ```bash
    mkdir build
    cd build
    cmake ..
    make
    ```

    For Windows (using Visual Studio):
    ```bash
    mkdir build
    cd build
    cmake ..
    ```

3. Run the Battle Snake server:
    ```bash
    ./std-venom
    ```

## Configuration
To configure the snake's behavior, modify the settings in `config.json`. Adjust parameters like snake speed, decision timeout, and pathfinding preferences.

## Usage
Once the server is running, deploy your snake on the [Battle Snake](https://play.battlesnake.com/) platform by entering the server URL in the game's custom snake settings.

## Contributing
Feel free to open issues or submit pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
