## WinWing FCU GUI
To run the app make sure you have python3 and pip installed.

1. Install the required packages:
   pip install PyQt6 pyusb

2. Place these file in the same directory:
   - winwing_fcu_gui.py
3. Run the app:
   - python3 winwing_fcu_gui.py

4. Click "Start FCU Controller" to begin

5. Use the "Output: On/Off" toggle to control debug messages

## Features

- Real-time connection status monitoring
- Easy start/stop control
- Debug output toggle
- User-friendly interface
- Automatic hardware detection
- X-Plane UDP communication management

## Troubleshooting

- Ensure X-Plane is running with a Toliss aircraft loaded
- Verify USB permissions are correctly set
- Check that all required Python packages are installed
- Confirm the WinWing hardware is properly connected

## Contributing

This GUI enhancement is built on top of the original [WinWing FCU project](https://github.com/schenlap/winwing_fcu). Please submit issues and pull requests to the original repository.

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Original WinWing FCU project by [schenlap](https://github.com/schenlap)
- Contributors to the original project
- Toliss for their excellent Airbus aircraft simulations

## Thanks
Thanks to schenlap for the WinWing FCU project. Check in with the project page for more information and updates.