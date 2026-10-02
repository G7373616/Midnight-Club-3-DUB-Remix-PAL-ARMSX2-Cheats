# Midnight Club 3: DUB Edition Remix PAL – FreeCam

FreeCam patch for the **PAL PlayStation 2 version** of *Midnight Club 3: DUB Edition Remix*.

**Release:** V2  
**PAL CRC:** `208183AF`  
**Game ID:** `SLES-53717`  
**Patch file:** `208183AF_FREECAM_PAL_TELEPORT_AIR_ANCHOR_RELEASE.pnach`

## Features

- Switch between the normal PlayerCam and FreeCam at any time
- Full FreeCam movement and rotation
- Adjustable movement speed
- Camera roll
- Adjustable FOV
- Cinematic / inertial camera movement
- Garage support
- Garage controls are isolated while FreeCam is active
- Garage HUD is hidden in FreeCam and restored in PlayerCam
- Safe cold-start behavior: the game starts in PlayerCam
- FreeCam FOV is reset when FreeCam is activated
- PlayerCam retains its normal FOV
- Teleport the player's vehicle directly to the FreeCam position
- Vehicle rotation is preserved during teleport
- Air Anchor mode can teleport and hold the vehicle in mid-air
- Air Anchor can be released manually
- Air Anchor automatically releases when leaving FreeCam
- Teleport and Air Anchor are protected from activation outside FreeCam

## Controls

| Input | Function |
|---|---|
| **L3 + R3** | Switch PlayerCam / FreeCam |
| **Left Stick** | Move FreeCam |
| **Right Stick** | Rotate / look around |
| **R2 / L2** | Move camera up / down |
| **D-Pad Left / Right** | Camera roll |
| **D-Pad Up / Down** | Increase / decrease movement speed |
| **R1 / L1** | Change FOV |
| **L3** | Toggle Cinematic Mode / camera inertia |
| **X** | Teleport vehicle to the current FreeCam position |
| **Square** | Teleport vehicle to FreeCam position and enable Air Anchor |
| **Square again** | Release Air Anchor |

## Teleport

While **FreeCam is active**, press **X** once.

The player's vehicle is teleported to the current FreeCam position.

- Vehicle rotation is preserved.
- Normal vehicle physics remain active after teleporting.
- Holding X does not continuously teleport the vehicle.
- X teleport is inactive while using PlayerCam.
- The teleport system is protected against activation in unsupported menu / Garage situations.

This makes it possible to position the FreeCam anywhere in the world and then instantly move the player's vehicle to that location.

## Air Anchor

While **FreeCam is active**, press **Square**.

The player's vehicle is teleported to the current FreeCam position and held there using **Air Anchor**.

This allows the vehicle to remain suspended in mid-air while the FreeCam continues to move independently.

Press **Square again** to release Air Anchor and restore normal vehicle physics.

Air Anchor also includes an automatic safety release:

- Enable Air Anchor with **Square**
- Switch from FreeCam back to PlayerCam
- Air Anchor automatically releases
- The vehicle immediately returns to normal physics

## Garage Support

The FreeCam can also be used inside the Garage.

While FreeCam is active:

- Camera controls do not navigate the Garage menu.
- D-Pad Left / Right remains available for camera roll without moving the Garage menu.
- The Garage HUD is hidden.
- Teleport / Air Anchor are protected from unsupported Garage activation.

Switching back to PlayerCam restores the normal Garage controls and HUD.

## Installation

1. Download `208183AF_FREECAM_PAL_TELEPORT_AIR_ANCHOR_RELEASE.pnach`.
2. Copy the PNACH file to the cheats folder used by your PS2 emulator.
3. Enable cheats / PNACH patches in the emulator.
4. Start *Midnight Club 3: DUB Edition Remix PAL*.
5. The game should start normally in PlayerCam.
6. Press **L3 + R3** to activate FreeCam.

> This patch is intended for the PAL game revision with CRC `208183AF` and Game ID `SLES-53717`.

## Tested

Release V2 has been tested with:

- Cold game starts
- Repeated PlayerCam ↔ FreeCam switching
- Normal Freeroam gameplay
- Race gameplay
- Garage use
- Leaving and re-entering the Garage
- FreeCam movement and rotation
- Vertical camera movement
- Camera roll
- Movement-speed adjustment
- FOV adjustment and restoration
- Cinematic Mode
- Repeated X teleports
- Vehicle rotation preservation during teleport
- Square Air Anchor activation
- Square Air Anchor release
- Automatic Air Anchor release when leaving FreeCam
- Repeated Air Anchor activation / release cycles
- Extended stability testing

## Credits

**Original NTSC-U FreeCam:** Racing Service TEARS

Special thanks to **Racing Service TEARS** for creating the original *Midnight Club 3: DUB Edition Remix* FreeCam.

**PAL Port (CRC `208183AF`):** Ported and adapted for the PAL version, including Garage integration, FOV behavior, safe PlayerCam cold-start support, vehicle teleportation and Air Anchor functionality.

### Testing

- **G7373616**
- **NFS0007**

Both testers helped verify the PAL FreeCam in gameplay and its release behavior.

## Version

**Release V2 – FreeCam + Teleport + Air Anchor**  
**PAL CRC:** `208183AF`  
**Game ID:** `SLES-53717`
