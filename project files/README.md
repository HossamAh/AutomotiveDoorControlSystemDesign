
```
project files
├─ ECU1
│  ├─ APP
│  │  └─ main.c
│  ├─ Lib
│  │  ├─ common_macros.h
│  │  └─ std_types.h
│  ├─ MCAL
│  │  ├─ ADC
│  │  │  ├─ ADC.c
│  │  │  ├─ ADC.h
│  │  │  ├─ ADC_cfg.c
│  │  │  └─ ADC_cfg.h
│  │  ├─ CAN
│  │  │  ├─ CAN.c
│  │  │  ├─ CAN.h
│  │  │  ├─ CAN_cfg.c
│  │  │  └─ CAN_cfg.h
│  │  ├─ DIO
│  │  │  ├─ DIO.c
│  │  │  ├─ DIO.h
│  │  │  ├─ DIO_cfg.c
│  │  │  └─ DIO_cfg.h
│  │  └─ Timer
│  │     ├─ Timer.c
│  │     ├─ Timer.h
│  │     ├─ Timer_cfg.c
│  │     └─ Timer_cfg.h
│  ├─ on_board
│  │  ├─ Door_sensor
│  │  │  ├─ Door_sensor.c
│  │  │  └─ Door_sensor.h
│  │  ├─ Lights_Switch
│  │  │  ├─ Lights_Switch.c
│  │  │  └─ Lights_Switch.h
│  │  └─ Speed_sensor
│  │     ├─ Speed_sensor.c
│  │     └─ Speed_sensor.h
│  ├─ OS
│  │  ├─ inc
│  │  └─ src
│  └─ Services
│     ├─ BCM.c
│     └─ BCM.h
└─ ECU2
   ├─ APP
   │  └─ main.c
   ├─ Lib
   │  ├─ common_macros.h
   │  └─ std_types.h
   ├─ MCAL
   │  ├─ CAN
   │  │  ├─ CAN.c
   │  │  ├─ CAN.h
   │  │  ├─ CAN_cfg.c
   │  │  └─ CAN_cfg.h
   │  ├─ DIO
   │  │  ├─ DIO.c
   │  │  ├─ DIO.h
   │  │  ├─ DIO_cfg.c
   │  │  └─ DIO_cfg.h
   │  └─ Timer
   │     ├─ Timer.c
   │     ├─ Timer.h
   │     ├─ Timer_cfg.c
   │     └─ Timer_cfg.h
   ├─ on_board
   │  ├─ Buzzer
   │  │  ├─ Buzzer.c
   │  │  └─ Buzzer.h
   │  ├─ LL
   │  │  ├─ LL.c
   │  │  └─ LL.h
   │  └─ RL
   │     ├─ RL.c
   │     └─ RL.h
   ├─ OS
   │  ├─ inc
   │  └─ src
   └─ Services
      ├─ AlarmManager
      │  ├─ AlarmManager.c
      │  └─ AlarmManager.h
      └─ BCM
         ├─ BCM.c
         └─ BCM.h

```