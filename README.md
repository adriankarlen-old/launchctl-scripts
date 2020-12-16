# launchctl-scripts
## Usage
Put the script you want file in ~/Library/LaunchAgents/com.example.ExampleFunctionality.plist to run the script when your mac boots.

To run the script without having to reboot, type: `launchctl load ~/Library/LaunchAgents/com.example`. You might need to unload the script first using: `launchctl unload ~/Library/LaunchAgents/com.example`
## KeyRemapper
This script automatically remap your keys. See https://developer.apple.com/library/archive/technotes/tn2450/_index.html for the key "usage IDs". Take the usage ID and add 0x700000000 to it before putting it into a source or destination (HIDKeyboardModifierMappingSrc and HIDKeyboardModifierMappingDst respectively).

The ProductID of you Keyboard can be found @ About This Mac -> System Report... -> Hardware/USB/USB-port

