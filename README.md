# Simple Data Viewer

A lightweight VS Code extension for visualizing PyTorch tensors, NumPy arrays, and NetworkX graphs during Python debugging sessions. No additional Python dependencies required!

## Features

- **View variables directly from the debug Variables panel** - Right-click any variable and select "View variable"
- **Support for multiple data types:**
  - PyTorch tensors
  - NumPy arrays
  - NetworkX graphs
- **Zero Python dependencies** - Only requires the package corresponding to the visualized variable (PyTorch, NumPy, or NetworkX), which should already be installed in your project
- **Interactive visualization** - Opens in a dedicated webview panel
- **Works during debugging** - Inspect variables in real-time while stepping through code

## Requirements

- VS Code 1.107.0 or higher
- Python debugger session active
- At least one of: PyTorch, NumPy, or NetworkX installed in your Python environment

## Usage

1. Start a Python debugging session
2. Set a breakpoint and pause execution
3. In the Variables panel, right-click on a PyTorch tensor, NumPy array, or NetworkX graph
4. Select "View variable" from the context menu
5. The data will be visualized in a new panel

## Supported Variable Types

- **PyTorch**: `torch.Tensor`
- **NumPy**: `numpy.ndarray`
- **NetworkX**: Graph objects

## Extension Settings

This extension does not require any configuration.

## Known Issues

Please report issues at: https://github.com/YOUR_USERNAME/simple-data-viewer/issues

## Release Notes

### 0.0.1

Initial release of Simple Data Viewer

- View PyTorch tensors during debugging
- View NumPy arrays during debugging
- View NetworkX graphs during debugging
- Right-click context menu in Variables panel

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This extension is licensed under the MIT License.