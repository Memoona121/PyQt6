# PyQt6 Basic Application

This repository contains a simple PyQt6 application that demonstrates the basic setup and structure of a PyQt6 GUI application.

## Description

The code creates a minimal PyQt6 application that:
- Initializes a `QApplication` object to manage the application's control flow and main settings.
- Creates a `QWidget` window.
- Displays the window using the `show()` method.
- Runs the application's event loop.

This serves as a starting point for building more complex PyQt6 applications.

## Code Overview

### Components
1. **PyQt6 Modules**:
   - `QApplication`: Handles the application's event loop.
   - `QWidget`: Provides the basic building block for all UI objects.

2. **sys Module**:
   - Used to handle command-line arguments.

### Code

```python
# Importing the components we need
from PyQt6.QtWidgets import QApplication, QWidget

# The sys module is responsible for processing command-line arguments
import sys

# Create the application object
app = QApplication(sys.argv)

# Create a basic window
window = QWidget()
window.show()

# Start the event loop
app.exec()
