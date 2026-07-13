# SO-101 Robotics Project

## Overview
This repository contains example scripts for working with the SO-101 robotic arm, including:
- leader/follower playback for recording and replaying arm motion
- inverse kinematics examples for planning a target pose

## Project Structure
- SO-101-Cool-Codes/ contains the arm-control example script and its Python dependencies
- SO-101-Cool-Math-Codes/ contains the kinematics example script and URDF model

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Nam14j/SO-101-Robotics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SO-101-Robotics
   ```
3. Create and activate a Python virtual environment (recommended):
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
4. Install the required Python packages:
   ```bash
   pip install -r SO-101-Cool-Codes/requirements.txt
   ```

> The leader/follower example depends on the Lerobot package and its SO-101 support. If you hit installation issues, follow the official Lerobot setup instructions for your environment before running the script.

## Usage
### Leader/Follower Playback
1. Connect the leader and follower arms to your computer.
2. Update the serial ports and arm IDs in SO-101-Cool-Codes/LeaderandFollowerPlayback.py if needed.
3. Run the script:
   ```bash
   python SO-101-Cool-Codes/LeaderandFollowerPlayback.py
   ```

### Inverse Kinematics Example
1. Make sure the URDF file used by the script is available in the same directory as the script.
2. Run the example:
   ```bash
   python SO-101-Cool-Math-Codes/How_To_Get_To_A_Cord.py
   ```

## Development
This project is intended for use in a Python environment with the dependencies listed in SO-101-Cool-Codes/requirements.txt. Keep the requirements file updated whenever new dependencies are introduced.

## License
This project is licensed under the MIT License.