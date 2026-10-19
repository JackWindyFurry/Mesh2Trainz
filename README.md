<img width="1311" height="591" alt="Screenshot 2026-10-19 185915" src="https://github.com/user-attachments/assets/4dd6a1bc-cc66-4178-8baf-870535a88a6a" />
# Mesh2Trainz

Mesh2Trainz is a small Windows application I made to make converting 3D models for Trainz a bit easier. Instead of running commands manually, you can select your files through the app and let it handle the conversion.

The project was originally called **IM2OBJ2TRAINZMESH**, but I renamed it to **Mesh2Trainz** because the old name was getting a little too long to remember, especially as I added support for more formats.

## Features

- **Multiple formats:** Convert between OBJ, IM, and TrainzMesh using the supported conversion options.
- **Simple interface:** Browse for your files instead of entering file paths manually.
- **Original IM reference:** Select an existing IM file when needed for OBJ-to-IM conversion.
- **Live logs:** See conversion progress, messages, and errors directly in the application, similar to what you'd see in Command Prompt.
- **V-flip option:** Adjust texture coordinates when converting models.
- **Output folder access:** Quickly open the folder containing your converted files.
- **Overwrite protection:** Helps prevent accidentally replacing your original files.
- **Standalone executable:** The app can be packaged as a Windows `.exe`, so users don't need to install Python separately.

## Supported conversions

| From | To |
|---|---|
| OBJ | IM |
| IM | OBJ |
| OBJ | TrainzMesh |
| TrainzMesh | OBJ |

## How to use

1. Open Mesh2Trainz.
2. Browse for the file you want to convert.
3. Select the original IM file if the conversion requires one.
4. Choose where to save the output file.
5. Start the conversion and watch the log for progress or errors.
6. Open the output folder to find your converted model.

## Why I made this

Working with different model formats can be a hassle when creating or modifying Trainz assets. I wanted a more convenient way to handle these conversions without having to type commands every time.

Mesh2Trainz brings the supported conversion tools together in one place, with a simple interface and a log that makes it easier to see what's happening during conversion.

The project is still focused on making the workflow more convenient, and additional improvements may come as development continues.
