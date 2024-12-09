# 🎮 Unity Input System (Package)

The Unity Input System package is an extension for the [Unity Platform](https://unity.com/products/unity-platform) that provides tools to configure game actions and access input devices for interaction with Unity content. It serves as a more powerful, flexible, and configurable replacement for the [Unity Input API](https://docs.unity3d.com/ScriptReference/Input.html) (the `UnityEngine.Input` class).

---

## 🔧 Prerequisites

To use the Input System, ensure you have:

- **Unity Versions**: Unity 2019 LTS, Unity 2020 LTS, Unity 2021, or Unity Beta (may have instabilities).
- **Unity Hub**: [Download Unity Hub](https://unity3d.com/get-unity/download) for recommended installation.

---

## 📖 Getting Started

Follow these resources to get started:

- **[Input System Manual - Installation](https://docs.unity3d.com/Packages/com.unity.inputsystem@latest/index.html?subfolder=/manual/Installation.html)**
- Tutorials:
  - [Unity Learn - Using the Input System in Unity](https://learn.unity.com/project/using-the-input-system-in-unity) 🎥 Video tutorials.
  - [Warriors Demo Project](https://github.com/UnityTechnologies/InputSystem_Warriors) 🔄 Demonstrates tools and features like local multiplayer.

### 📚 Example Projects

Explore these included samples:

- **[Custom Composite](Assets/Samples/CustomComposite)**: Create and register a custom `InputBindingComposite`.
- **[Custom Device](Assets/Samples/CustomDevice)**: Add and author custom devices.
- **[Custom Device Usages](Assets/Samples/CustomDeviceUsages)**: Bind actions to devices with specific custom usages.
- **[Gamepad Mouse Cursor](Assets/Samples/GamepadMouseCursor)**: Navigate UI using gamepad input.
- **[In-game Hints](Assets/Samples/InGameHints)**: Display action bindings and interactions.
- **[Input Recorder](Assets/Samples/InputRecorder)**: Use [`InputEventTrace`](https://docs.unity3d.com/Packages/com.unity.inputsystem@latest/index.html?subfolder=/api/UnityEngine.InputSystem.LowLevel.InputEventTrace.html).
- **[On-screen Controls](Assets/Samples/OnScreenControls)**: Set up and use on-screen gamepad-like controls.
- **[Rebinding UI](Assets/Samples/RebindingUI)**: Reconfigure bindings during runtime.
- **[Simple Demo](Assets/Samples/SimpleDemo)**: Basic character controller with `PlayerInput`.
- **[Simple Multiplayer](Assets/Samples/SimpleMultiplayer)**: Split-screen local multiplayer setup.
- **[UI vs Game Input](Assets/Samples/UIvsGameInput)**: Resolve input ambiguities with UI overlays.
- **[Visualizers](Assets/Samples/Visualizers)**: Visualize input data from common devices.

---

## 🚀 Using Released Versions

To use the Input System package in your project:

1. Open Unity.
2. Use the Unity Package Manager to fetch and install the package:
   - See [`Input System Manual - Installation`](https://docs.unity3d.com/Packages/com.unity.inputsystem@latest/index.html?subfolder=/manual/Installation.html).

---

## 🔄 Using the Latest Changes

To try out the latest (unreleased) changes:

1. Clone the [develop branch](https://github.com/Unity-Technologies/InputSystem/tree/develop). Note: This branch may contain bugs or unstable features.
2. Add the local package to your project:
   - Follow the steps in [Installing a package from a local folder](https://docs.unity3d.com/Manual/upm-ui-local.html).

---

## 🎩 Developing with the Input System

For advanced development:

1. Clone the [develop branch](https://github.com/Unity-Technologies/InputSystem/tree/develop) or desired release tag.
2. Open the repository in the Unity Editor for access to tests and samples excluded from the package.
3. Run automated tests via `Window > General > Test Runner`:
   - **PlayMode** or **EditMode**: Select `Run All` to validate functionality.

---

## 📢 Contribution & Feedback

Unity Technologies welcomes contributions and feedback:

- Join discussions on the [Unity Forums](https://forum.unity.com/forums/new-input-system.103/).
- Refer to [CONTRIBUTIONS.md](https://github.com/Unity-Technologies/InputSystem/blob/develop/CONTRIBUTIONS.md) for contribution guidelines.

---

## 🔒 License

This package is distributed under the [Unity Companion License for Unity-dependent projects](LICENSE.md), with additional [third-party licenses](Third%20Party%20Notices.md) applying to certain examples (e.g., [Assets/Samples/RebindingUI](Assets/Samples/RebindingUI)).
