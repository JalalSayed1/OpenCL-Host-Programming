# OpenCL-Host-Programming

- To create a simple host-side driver routine run driver() to interact with an OpenCL-compliant device (e.g. a GPU).
- run driver() routine is called from a multithreaded testbench which will take care of initialisation and shutdown of the device, creation of the data to be sent to the device and validation of the returned result.
- 
