# ArduinoSCPIParser2
Instrument side SCPI parser

Based on https://github.com/LachlanGunn/oic

Changes from the original version

- Examples path corrected
- Error queue circular array based (no more malloc)
- SCPI SYSTEM subsystem implementation removed, it must implemented in the arduino code 

TODO

- More examples
- Implementing register to make the library SCPI IEEE 488.2 comliant
