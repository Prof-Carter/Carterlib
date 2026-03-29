# carterlib

<img width="640" alt="image" src="https://github.com/user-attachments/assets/9d1f7719-d0c3-456a-87b4-4a9698f30760" />
<p>
<img width="360" alt="image" src="https://github.com/user-attachments/assets/dbb325da-1946-4695-a5fb-abbf615aa675" />

<img width="360" alt="image" src="https://github.com/user-attachments/assets/75821c07-ac90-436b-a007-b0e684745b8c" />


## Update History

* ver.1.2 Release (2026/03/29)
   * Use basic Simulink blocks instead of a MATLAB Function for the "AS5601 Angle Sensor"
   * Change default "Sample Time" of "I2C Read" from 0.005s to -1 (-1 for inherited) 
* ver.1.1 Release (2026/03/19)
   * Add I2C module configuration for "AS5601 Angle Sensor"
* ver.1.0 Release (2026/01/05)

Previous versions are available here:
https://github.com/Prof-Carter/Carterlib_Release

## Citation / Usage Notice

If you use this library in a research presentation, paper, or educational material,
please include the following link as a reference:

Masakatsu Kawata: https://github.com/Prof-Carter/Carterlib

## Overview
Simulink library "carterlib" provides a set of Simulink blocks.  
* Motor driver DRV8833
* Angle sensor (magnetic absolute encoder: I2C device) AS5601

## Supported Versions
- MATLAB/Simulink R2023a or later

## Installation
1. Extract the downloaded files to any folder, for example:
C:\hoge\Carterlib-main

2. Add the folder path to MATLAB using:  
```
>> addpath('C:\hoge\Carterlib-main')
>> carterlib
```

## Disclaimer

This library is intended for research and educational purposes only.
The author assumes no responsibility for any damage or loss caused by its use.

## License

MIT License
(See the LICENSE file for details)

© 2026 Masakatsu Kawata
