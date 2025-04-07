# DUST FOR DEVELOPERS

## Requirements for the SDK

To get started with the SDK, ensure you have the following installed:

- Any Unity version above 2021
- Visual Studio 2022

After installing the necessary components, download the Unity package. Open the folder, locate the empty scene, and arrange the items according to your preferences.

---

## Creating Custom Commands in Version V.1.2

In version V.3 of the SDK, you can implement custom commands by utilizing the `QFSW.QC` namespace in your code. To make your commands accessible through the console, use the `[Command]` attribute to annotate your method. This will allow for dynamic modification of commands during gameplay.

### Example Implementation

```csharp
using QFSW.QC;
...

[Command]
public static int Add(int a, int b)
{
    return a + b;
}
```

### Expanding Command Capabilities

Feel free to explore and expand your command capabilities to enhance gameplay functionality. This flexibility allows for more engaging interactions within your Unity project.

---

All text was rephrased by Grammarly. Please report any bugs with the SDK on the issues tab
