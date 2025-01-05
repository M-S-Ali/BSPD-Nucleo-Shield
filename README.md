# BSPD-Nucleo-Shield
Modern vehicles use an accelerator pedal to control the engine’s throttle, which regulates power output. Traditionally, this was achieved through complex mechanical linkages. However, relying solely on the accelerator pedal is not the most efficient way to determine engine power, as other factors like fuel injection and combustion also play a critical role. 

To address this, modern vehicles use **throttle-by-wire systems**, where the accelerator pedal sends electronic signals to a vehicle control unit (VCU). The VCU processes these signals along with other engine parameters to optimize power output. While this approach improves efficiency and performance, it introduces concerns such as potential wire disconnections or data transmission errors. 

In high-performance applications, like racing, safety mechanisms such as the **Brake System Plausibility Device (BSPD)** are used to mitigate risks by cutting off engine power if a fault is detected.

This project focuses on designing an **enhanced throttle-by-wire system** with integrated BSPD functionality. The system is implemented using an **STM32 Nucleo board**, programmed through **MATLAB Simulink**, and employs **fuzzy logic** for intelligent control. A custom-designed **PCB shield** ensures seamless integration with the hardware for practical implementation.
