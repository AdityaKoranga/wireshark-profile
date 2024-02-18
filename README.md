# wireshark-profile

# Wireshark Profile Configuration and Sharing

This documentation provides a step-by-step guide on how to create, modify, save, and share a Wireshark profile. Profiles in Wireshark allow users to save a set of configuration settings that can be easily transferred to another installation of Wireshark.

## Creating a New Profile

1. Open Wireshark.
2. On the start page or within the application window, look for the profile selection menu (usually located at the bottom right corner or in the main menu bar).
3. Select `New` or `Manage Profiles...` from the profile list.
4. Give your profile a name. It will be populated with the default or current settings.

## Modifying a Profile

1. Adjust any necessary settings within Wireshark under `Edit -> Preferences -> Protocols` or any other relevant section.
2. Customize your profile settings as needed.
3. All changes are saved automatically to the profile as they are made.

## Saving a Profile

- Wireshark automatically saves your settings to your profile as you make changes.

## Locating the Profile on Your Computer

- Profiles are stored in the Wireshark user data directory.
- For Windows: `%APPDATA%\Wireshark\profiles\`
- For macOS and Linux: `~/.config/wireshark/profiles/`

## Sharing a Profile

1. Navigate to the profiles directory on your file system.
2. Compress the profile directory that you wish to share.
3. Send the compressed file to your colleague.

## Using a Shared Profile

1. Decompress the received profile file.
2. Place the profile directory into the corresponding Wireshark profiles directory on your system.
3. Select the profile from the Wireshark profile menu to use it.

---

For additional help or support, consult the Wireshark documentation or the Wireshark community forums.
