# SO-101 Robotics Project

## Overview
The SO-101 Robotics project involves controlling a leader and follower robotic arm setup. The leader arm captures joint positions, which are then replicated by the follower arm.

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/Nam14j/SO-101-Robotics.git
   ```
2. Navigate to the project directory:
   ```
   cd SO-101-Robotics
   ```
3. Install the required Python packages:
   ```
   pip install -r requirements.txt
   ```

## Usage
1. Connect the leader and follower arms to your computer.
2. Run the playback script:
   ```
   python LeaderandFollowerPlayback.py
   ```
3. Follow the on-screen instructions to record and playback movements.

## Development
This project uses a development container for a consistent development environment. Ensure you have Docker installed and follow the instructions in the `.devcontainer` directory to set it up.

## License
This project is licensed under the MIT License.