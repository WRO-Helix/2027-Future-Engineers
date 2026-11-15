# 2027-Future-Engineers by team Helix

This is the team Helix's github repository for the WRO 2027 Future Engineers category.

## Table of Contents

- [Who are we?](#who-are-we)

- [Our project](#our-project)

- [Installation](#installation)

- [Running](#running)


## Who are we?

We are a team of students from Budai Ciszterci Szent Imre Gimnázium in Budapest, Hungary. We participate in the World Robot Olympiad (WRO) to showcase our skills and creativity in robotics.

### Team Members

- **Janzsó Gábor** - Our team leader and coach
- **Vlasits Benedek** - Responsible for programming and electronics
- **Wacha János** - Responsible for mechanical design, construction, programming and documentation

### Team photos

There are some photos of our team in the [`images/team`](images/team) directory.

## Our project

There are the files required for our project in the [`src`](src) directory. The main file is [`main.py`](src/code/main.py), which contains the code to control the robot. The other files are used for various purposes, such as configuration, sensor reading, and testing.

There are three main directories in the project: [`src`](src), [`autostart`](autostart), and [`images`](images). The `src` directory contains the source code, the `autostart` directory contains the instructions for autostarting the robot, and the `images` directory contains images for the project.

### Src directory

The [`src`](src) directory contains the source code for the robot. The main file is [`main.py`](src/code/main.py), which contains the code to control the robot. The other files are used for various purposes, such as configuration, sensor reading, and testing.

#### Code directory

The [`code`](src/code) directory contains the code files for sensor reading, motor control, and other functionalities.

##### Files

[`main.py`](src/code/main.py) - The main file that contains the code to control the robot.

#### Testing directory

The [`testing`](src/testing) directory contains the code files for testing the robot's functionalities.

##### Files

### Autostart directory

The [`autostart`](autostart) directory contains the instructions for autostarting the robot. It includes a README file with detailed instructions on how to set up the robot for competition.

#### Files

[`start-robot.sh`](autostart/start-robot.sh) - A shell script to start the robot automatically.

[`stop-robot.sh`](autostart/stop-robot.sh) - A shell script to disable autostart.

### Images directory

The [`images`](images) directory contains images for the project, such as team photos and robot design images.

#### Robot directory

The [`robot`](images/robot) directory contains images of the robot design and construction.

#### Team directory

The [`team`](images/team) directory contains images of the team members and their activities.

#### Files

[`youtube-urls.md`](images/youtube-urls.md) - A list of YouTube URLs related to the robot design.

## Installation

To install the project, follow these steps:

- Clone the repository to your local machine:

```bash
git clone https://github.com/WRO-HELIX/2027-Future-Engineers.git
```

- Navigate to the project directory:

```bash
cd 2027-Future-Engineers
```

- install the required dependencies:

```bash
pip install -r requirements.txt
```

## Running

To run the project, you have two options: for development and for production. The development option is recommended for testing and debugging, while the production option is recommended for running the robot in the competition.

- Development: Please refer to the [`Running`](src/README.md) section for detailed instructions.

- Production: Please refer to the [`Autostart`](autostart/README.md) section for detailed instructions.