# STM32 Studio

Interactive 3D exploded architectural explorer for the STM32F40xxx family, inspired by Model X Studio.

## Run

```bash
npm install
npm run dev
```

Drag to rotate, scroll to zoom, click blocks to isolate them, and use the Explode slider to separate the architecture.

> This is an educational architectural visualization based on the STM32F40xxx functional block diagram. It does not represent the literal physical floorplan of the silicon die.

## Current blocks
Cortex-M4/FPU/NVIC, Flash, SRAM, AHB bus matrix, DMA, GPIO, timers, ADC/DAC, USART/UART, SPI/I2C, CAN, USB OTG, Ethernet MAC, FSMC, RCC/power.

## Next
Pin-level alternate-function tracing, APB1/APB2/AHB relationship visualization, signal-path highlighting, detailed peripheral panels, and package pins.
