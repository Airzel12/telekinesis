# Telekinesis Mod for Lethal Company

## Description

The **Telekinesis Mod** adds a telekinetic ability to your character in **Lethal Company**. With this mod, you can grab and throw objects or enemies using psychic powers, making gameplay more dynamic and fun!

### Features:
- **Grab Objects & Enemies**: Use **E** to grab objects or enemies within your range.
- **Throw Objects & Enemies**: Use **F** to throw the grabbed objects or enemies with force.
- **Carry Up to 2 Objects**: You can carry a maximum of 2 objects at once.
- **Customizable Range & Force**: The grab range and throw force can be easily adjusted within the code (default values: 5 units for range and 10 force for throw).

## Requirements

- **BepInEx**: The mod requires **BepInEx** to work. Make sure you have it installed before using this mod.
- **Lethal Company**: This mod is designed to work with the **Lethal Company** game.

## Installation

1. **Install BepInEx**:
   - If you haven't already, install **BepInEx** into your **Lethal Company** directory. This is required for the mod to function.
   
2. **Download the Telekinesis Mod DLL**:
   - After compiling the mod or downloading the DLL file, navigate to your **Lethal Company** directory.
   
3. **Place the DLL in the Plugins Folder**:
   - Copy the **Telekinesis Mod DLL** into the **BepInEx/plugins** folder inside your **Lethal Company** directory.
   
4. **Run the Game**:
   - Launch **Lethal Company** with **BepInEx** running. The mod should now be active and ready to use.

## How to Use

- **Grab an Object/Enemy**:
  - Press **E** to grab an object or enemy within range. The object must have a Rigidbody component and must be tagged as **"Interactable"** or **"Enemy"**.
  
- **Throw an Object/Enemy**:
  - Press **F** to throw the grabbed object or enemy. The object will be thrown with a force, and gravity will be re-enabled upon release.

- **Max Objects**:
  - You can carry up to 2 objects at once. If you try to grab more than that, the mod will log a message.

## Configuration

The mod allows you to adjust the following settings in the code:
- **MaxGrabbedObjects**: The maximum number of objects you can carry at once (default: 2).
- **GrabRange**: The range within which you can grab objects (default: 5 units).
- **ThrowForce**: The force with which objects are thrown (default: 10 force units).

You can change these values by opening the code and adjusting the respective constants.

## Troubleshooting

- **Object Not Grabbing**:
  - Ensure that the object you’re trying to grab has a **Rigidbody** and is tagged as either **"Interactable"** or **"Enemy"**.
  
- **Error Logs**:
  - If the mod isn’t working as expected, check the **BepInEx log files** for any error messages. They can help identify any issues with the mod or its configuration.

## Credits

- **BepInEx Team**: For creating the modding framework that powers this mod.
- **Lethal Company Developers**: For creating the game.

## License

This mod is open-source and available for free use. Feel free to modify and distribute it as long as you credit the original authors.

---

**Enjoy the Telekinesis Mod and have fun using your psychic powers in Lethal Company!**
