# Running

There are the codes required to run the project.

## Starting the robot

You can start the robot by running the following command in your terminal:

```bash
python src/code/main.py
```

### Starting options

You can also start the robot with different options.

#### No start button

You can start the robot without the start button by running the following command:

```bash
python src/code/main.py --no-start-button
```

or

```bash
python src/code/main.py -n
```

#### Debug mode

Debug mode is useful for development and testing. If the robot is in debug mode, a web sensor monitor will be started, and you can access it by opening your web browser and navigating to `http://raspi-robot:8000`. You can start the robot in debug mode by running the following command:

```bash
python src/code/main.py --debug
```

or

```bash
python src/code/main.py -d
```