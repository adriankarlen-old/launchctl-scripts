# launchctl-scripts
## KeyRemapper
Put this file in ~/Library/LaunchAgents/com.example.KeyRemapping.plist to automatically remap your keys when macOS starts. See https://developer.apple.com/library/archive/technotes/tn2450/_index.html for the key "usage IDs". Take the usage ID and add 0x700000000 to it before putting it into a source or destination (HIDKeyboardModifierMappingSrc and HIDKeyboardModifierMappingDst respectively).

The ProductID of you Keyboard can be found @ About This Mac -> System Report... -> Hardware/USB/USB-port