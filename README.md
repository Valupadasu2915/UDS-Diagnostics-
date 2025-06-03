# UDS-Diagnostics-
This repository demonstrates the implementation and automation of UDS (ISO 14229) diagnostic services for validating ECU behavior in a HIL test environment. The goal is to simulate and verify diagnostic requests/responses as per OEM specifications using CAPL/Python scripts and CANoe/dSPACE platforms.

Technologies & Tools

#CANoe with CAPL scripting

#dSPACE ControlDesk/AutomationDesk

#Python (UDS libraries / custom automation)

#A2L file parsing and DBC file interpretation

#CAN, LIN, and FlexRay protocols

Implemented UDS services: 0x10, 0x11, 0x22, 0x2E, 0x31, 0x34, 0x3E, etc.
Real-time validation of diagnostic responses using CAPL test cases
Automated diagnostic sequences and logging for regression testing
Fault injection and negative test scenarios (e.g., NRC handling)
Visualization of ECU response times and DTC reporting
