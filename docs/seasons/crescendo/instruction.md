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

### 赛前准备

- 电池最低电压：12.7V
- **每场比赛前都要换电池**
- 换下的电池立刻充电/摆在充电器旁
- 充好的电池区分存放

**开电前**检查

- 手动将主炮推拉至上下位置极限，过程中留意有无卡顿，最后将主炮手动放到最低位
- **检查主炮飞轮、Feeder滚筒、Intake滚筒能否顺畅旋转**
- Climber检查
  - 拉线是否处于绳毂两壁之间
  - 用（棘轮）扳手将线放出并收回，检查过程是否顺畅
  - 检查完毕后将Climber**收回到最低位**
- 紧固检查
  - 主炮六根横梁中心M6螺丝
  - 主炮横梁角件处螺丝
  - 主炮仰角机械限位轴承组中心螺丝
  - 穹甲上位铝管两端螺丝
  - 主炮底座贯通轴两端螺丝
  - 主炮飞轮、Feeder滚筒、Intake滚筒六角轴两端螺丝
  - 各轴承限位M5*5螺丝
  - 抽样检查底盘各处螺丝
  - 如加装Climber，至少要有中心4颗贯通M4*85螺丝和两侧共4颗固定碳板螺丝


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
