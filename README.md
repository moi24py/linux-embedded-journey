# linux-embedded-journey
My journey towards becoming a Linux embedded developer.

<p>:pushpin: Goal<br>
Develop professional skills in the embedded field with an emphasis on industrial tools, hardware communication, and user space.</p>
:date: started on August 2025

---

## Roadmap
| #      | Project                          | Date        | Tech used                                         |
| :----- | -------------------------------- | ----------- | -------------------------------------------------
| 1   | [Hello + Make](https://github.com/moi24py/hello-c)           | 15 08 2025 | `gcc`, `Makefile`
| 2   | [File Logger](https://github.com/moi24py/file-logger)                      | 20 08 2025 | `fopen`, `fprintf`, `fclose`                    |
| 3   | [Mini menu](https://github.com/moi24py/mini-embedded-system-menu)| 25 09 2025 | `fgets`, `strtol`, `read`, `buffer input`          | 
| 4   | Use of `struct` + array + malloc | ... 2025 | `struct`, `array`, `malloc`, `pointers`           |
| 5   | Signal Handling (`Ctrl+C`, ecc)  | ... 2025 | `signal`, `sigaction`, `kill`                   | 
| 6   | Timer e misurazione del tempo    | ... 2025 | `time.h`, `clock_gettime`, `sleep`, `usleep`      | 
| 7   | Thread Logger                    | ... 2025 | `pthread`, `mutex`, `pthread_join`                |
| 8   | IPC with pipe (\`cat grep\`)     | ... 2025 | `pipe`, `fork`, `dup2`, `exec` | `c-ipc-pipe`     |  
| 9   | TCP Server                       | ... 2025 | `socket`, `bind`, `listen`, `accept`, `send/recv` |
| 10  | GPIO LED Blinker                 | ... 2025 | `/sys/class/gpio`, `open()`, `write()`            |                 
| 11  | I2C Temp Logger                  | ... 2025 | `/dev/i2c-X`, `ioctl`, TMP102                     |          
| 12  | SPI Accelerometer Reader         | ... 2025 | `/dev/spidevX.X`, `ioctl`, `read/write`           |           
| 13  | Configurable CLI Logger         | ... 2025 | `getopt`, `config file`, `argv/argc`               |              
| 14  | Real-Time Logger                 | ... 2025 | `SCHED_FIFO`, `clock_nanosleep`, `priority`       |                    
| 15  | MQTT Weather Station             | ... 2025 | `libmosquitto`, `i2c`, `json`, `mqtt`             |                 
| 16  | Cross Compilation Toolchain      | ... 2025 | `arm-none-eabi`, `CMake`, `toolchain.cmake`       |       
| 17  | Yocto Minimal Image              | ... 2025 | `bitbake`, `core-image-minimal`, `meta-layer`     |         
| 18  | Deploy & Daemon                  | ... 2025 | `scp`, `systemd service`, `bash`                  |     
