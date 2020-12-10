# PCFuzzer
Protocol Fuzzing Test Framework for Programmable Controller

## Control program directory
It provides control programs for PLC and PAC from different manufacturers. The control program can make the output module of the programmable controller output square waves. In use, it may need to be modified with engineering software according to the specific hardware configuration.



## PCFuzzer Framework
A protocol fuzzing framework based on KITTY-Fuzzer.
Kitty-Fuzzer Structure:https://kitty.readthedocs.io/en/latest/base_structure.html
Unlike Kitty-Fuzzer, PCFuzzer is for a proprietary protocol and does not require protocol specifications or protocol reversals. The input of PCFuzzer is message traffic. We provide a simple sniffer based on Scapy. At the same time, we provide a monitoring module using a digital oscilloscope (using the Visa package).

