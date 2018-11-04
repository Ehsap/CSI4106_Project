# How to Simulate Keypresses using the Controller class
## Requirements
Python 3

keyboard library `pip install keyboard`

# Usage
To use the controller class, simply import it into your script like so.

```python
from Controller.Controller import Controller

controller = Controller()

# Accelerate
controller.accelerate()

# Brake
controller.brake()

# Turn Left
controller.turn_left()

# Turn Left and Accelerate at the same time
controller.turn_left_accelerate()

# Turn Right
controller.turn_right()

# Turn Right and Accelerate at the same time
controller.turn_right_accelerate()

```


