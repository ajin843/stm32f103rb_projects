## stm32f103rb
 
- internal flash  = 128 KB
- 128KB = 0x20000, page size 0x400
- Non-volatile
- Flash = settings / logs / checkpoints, not live streaming.
- Avoid float in Flash if you can.
- Pick where in flash you’ll store data
- Understand flash write rules for STM32F1
- Decide storage format
- 

- **HAL_Init()** : for sysTick clock.
- **SystemClock_Config()** : CPU still needs a clock to execute instructions.
- **MX_GPIO_Init()** : Init all GPIO pheripherals.
  
