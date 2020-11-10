# 3D-Vision-Automatic
Small stereoscopic sample demonstrating how to use 3D Vision Automatic Mode using DX11.  

This is just a simple spinning box sample in DX11, that emulates the way a lot of games create
their swapchains and devices.  If running in fullscreen mode, this will be automatically be
stereoized by 3D Vision.
<br>
<br>

This is based upon the Microsoft DX11 Tutorial sample:   
https://code.msdn.microsoft.com/windowsdesktop/Direct3D-Tutorial-Win32-829979ef

Newest version:  
https://github.com/walbourn/directx-sdk-samples/tree/master/Direct3D11Tutorials
<br>
<br>

The piece used here is only Tutorial_07, which shows the full tutorial with a spinning cube, drawn using shaders and vertex buffer.

The old Tutorial07 was modifed as little as possible, but is not remotely like the newest version which uses DXGI factories
instead of the CreateDeviceAndSwapChain.

