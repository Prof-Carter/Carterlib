# carterlib


<img width="720" alt="image" src="https://github.com/user-attachments/assets/dbffd446-bd03-4182-9ac4-e59cb0c2416d" />
<p><p>

<img width="360" alt="image" src="https://github.com/user-attachments/assets/ee927bca-5184-4695-a641-32033a473da1" />
<img width="360" alt="image" src="https://github.com/user-attachments/assets/2b4a2255-46a2-47ea-99af-7d687071da25" />

<p>
  
<img width="360" alt="image" src="https://github.com/user-attachments/assets/876a4a15-1cef-4970-a3eb-53721fc1329c" />
<img width="360" alt="image" src="https://github.com/user-attachments/assets/ee072a51-633d-4f9f-87b0-afc7f7f49941" />


## Update History

* ver.1.5 Release (2026/11/20)
   * Add I2C address configuration for "MT6701 Angle Sensor"
   * Fix a bug in "AS5048B Angle Sensor (relative angle detection [deg])"
* ver.1.4 Release (2026/11/10)
   * Add I2C module configuration for "MT6701 Angle Sensor" (14-bit magnetic absolute encoder)
* ver.1.3 Release (2026/11/03)
   * Add I2C module configuration for "AS5048B Angle Sensor" (14-bit magnetic absolute encoder)
* ver.1.2 Release (2026/03/29)
   * Use basic Simulink blocks instead of a MATLAB Function for the "AS5601 Angle Sensor"
   * Change default "Sample Time" of "I2C Read" from 0.005s to -1 (-1 for inherited) 
* ver.1.1 Release (2026/03/19)
   * Add I2C module configuration for "AS5601 Angle Sensor" (12-bit magnetic absolute encoder)
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
* Angle sensor (12-bit magnetic absolute encoder: I2C device) AS5601
* Angle sensor (14-bit magnetic absolute encoder: I2C device) AS5048B
* Angle sensor (14-bit magnetic absolute encoder: I2C device) MT6701

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
