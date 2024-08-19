# Instruction

## Operator Manual

### Pilot

#### Swerve

- Translation Motion: Left joystick
- Rotation Motion: Right joystick
- Re-Calibrate heading: Button A

#### Climber

- Left Motor Positive Rotation: Left Bumper
- Left Motor Negative Rotation: Left Trigger
- Right Motor Positive Rotation: Right Bumper
- Right Motor Negative Rotation: Right Trigger

### Copilot

#### Intake

- Intake Inject: Left Trigger
- Intake Eject: Left Bumper

#### Shooter

##### Aiming & Firing

- Aim/Pre-shooting: Right Bumper
- Load/Fire: Right Trigger

##### Pitch

- Set Target Amp: Button Y
- Set Target Speaker: Button X
- Set Passing Note: Button A
- Reset Shooter Pitch: Button B

#### Trivial

- Rotation Motion: Right Joystick

## Checklists

### Pre-Match

- Minimum Battery Voltage: 12.7V
- **CHANGE BATTERY AFTER EACH GAME**

Checklist for **BEFORE POWERING UP**

- Shooter Pitch: manually push shooter to lowest and highest possible pitch. Examine if there is visible dampening. Move to lowest possible pitch before powering up.
- Climber Check:
  - Thread condition for pulling up/down
  - Tunnel movability
- Wheel movability: check for flywheel, intake, and feeder.

Checklist for **AFTER POWERING UP**. Place robot on maintenance cart and facing pilot.

#### Swerve Check

- **PUSH** left joystick to **FRONT, BACK, LEFT, and RIGHT**. Check:
  - The four wheels are moving towards the same direction
  - The four wheels are moving with the same velocity
- **SLOWLY CHANGE DIRECTION** with left joystick. Check:
  - The four wheels are changing direction with same rate.
  - The four wheels are moving with the same velocity
- **PUSH LEFT JOYSTICK WITH DIFFERENT VELOCITY**. Check:
  - The four wheels are moving with the same velocity
  - The wheel velocities are changing with positive correlation with pilot's joystick.
- **PUSH RIGHT JOYSTICK WITH DIFFERENT VELOCITY**. Do not move left joystick during this check. Check:
  - The four wheels are moving with the same velocity magnitude
  - The velocity direction of the four wheels are orthogonal to respective neighboring wheel and opposite parallel.
  - Right joystick turning right indicates clockwise movement, and vice versa.

#### Vision Check

See [Vision Guide](https://github.com/FRC-Team-Defiant/Vision-Guide/blob/main/docs/Troubleshooting.md) for details

#### Shooter Check

- Initial pitch: 30 degrees, Copilot press button B
- Standard pitch: 66.5 degrees, Copilot press intake inject/eject
- Passing pitch: 45 degrees, Copilot press button A. Designed for passing notes across field

### On-Field Reminders

- Manually shooter pitch to the lowest before powering up the machine
- Calibrate/reset headless mode with shooter facing friendly alliance wall.
- Open `Shuffleboard`, turn to `Commander` tab
- Allow robot to calibrate position with vision at least once before beginning to shoot.
