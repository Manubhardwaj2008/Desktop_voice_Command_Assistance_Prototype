# Desktop Voice Command Assistance Prototype

A Python-based desktop voice command assistant prototype designed to listen to spoken commands and perform actions from a predefined command library, such as opening applications or webpages.

> **Status:** Prototype / Work in Progress

## Overview

The goal of this project is to make common desktop actions easier and more natural through voice commands. Instead of manually navigating to an application or website, the assistant can interpret a supported spoken command and trigger the corresponding action.

The project is currently structured as a prototype, with the main command, assistance, and utility modules being developed incrementally.

## Features

- 🎙️ Voice-command based interaction
- 🖥️ Designed for desktop use
- 🚀 Open supported applications using voice commands
- 🌐 Open supported webpages using voice commands
- 🧩 Command library approach for extending supported actions
- 🐍 Built with Python
- 🔧 Modular structure for future development

## Project Structure

```text
Desktop_voice_Command_Assistance_Prototype/
│
├── assistance.py              # Assistant functionality (under development)
├── command.py                 # Command handling and command library
├── utils.py                   # Utility/helper functions
├── requirements.txt           # Python dependencies
├── TODO.md                    # Development notes / tasks
├── start_iris.bat.disabled    # Disabled Windows startup script
├── LICENSE                    # MIT License
└── README.md                  # Project documentation
```

## How It Works

The intended workflow is:

```text
User speaks a command
        ↓
Voice input is captured
        ↓
Command is interpreted
        ↓
Command is matched with the supported library
        ↓
Requested desktop action is executed
```

For example, a supported command could be used to open an application or webpage that has been registered in the command library.

## Requirements

- Windows desktop environment
- Python 3.x
- A working microphone for voice input
- Python packages listed in `requirements.txt`

The dependency file is currently a work in progress, so additional packages may need to be added as the voice-recognition functionality is implemented.

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Manubhardwaj2008/Desktop_voice_Command_Assistance_Prototype.git
cd Desktop_voice_Command_Assistance_Prototype
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

> If `requirements.txt` is empty, install the required voice-recognition/audio packages after they are added to the project.

## Running the Project

The project is currently under active development. The main Python modules are being built as the command-processing and voice-assistance functionality is implemented.

Once the entry-point script is finalized, the project can be launched from the terminal with the corresponding Python command.

## Current Development Status

| Component | Status |
|---|---|
| Project structure | 🟡 Prototype |
| Command module | 🟡 Under development |
| Voice recognition | 🟡 Under development |
| Application launching | 🟡 Planned / prototype stage |
| Webpage launching | 🟡 Planned / prototype stage |
| Utility functions | 🟡 Under development |
| Dependency management | 🟡 Under development |
| Documentation | 🟢 Available |

## Future Improvements

- Add reliable speech-to-text recognition
- Add a wake-word or activation mechanism
- Expand the command library
- Add custom user-defined commands
- Add application discovery instead of relying only on predefined paths
- Add webpage shortcuts
- Add confirmation for potentially disruptive actions
- Add error handling for unknown commands
- Add a graphical user interface
- Add command history and logging
- Improve cross-platform compatibility
- Package the assistant as a standalone Windows application

## Use Cases

This project can be used as a learning prototype for exploring:

- Python automation
- Speech recognition
- Natural-language command processing
- Desktop automation
- Modular software design
- Human-computer interaction

## Contributing

Contributions and suggestions are welcome. If you want to improve the project, consider opening an issue describing the proposed change before submitting a pull request.

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Author

**Manu Bhardwaj**

GitHub: https://github.com/Manubhardwaj2008

---

⭐ If you find this project interesting, consider starring the repository and following its development.
