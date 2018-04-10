# Limitations 

## Unity SDK
### Headless Mode
If you enable Headless mode, you will not be able to collect visual 
observations from your agents.

### Rendering Speed and Synchronization
Currently the speed of the game physics can only be increased to 100x 
real-time. The Academy also moves in time with FixedUpdate() rather than 
Update(), so game behavior tied to frame updates may be out of sync. 

## Python API

### Python version
As of version 0.3, we no longer support Python 2. 