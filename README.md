
# macOS Services Reset Script

This script safely restarts essential macOS services, including Finder, Dock, SystemUIServer, and networking services, to resolve common UI and network issues.

## How to Run

1. **Download the script** or create a new file and copy the script into it.
2. **Make it executable**:
   ```bash
   chmod +x reset_macos_services.sh
   ```
3. **Run the script**:
   ```bash
   ./reset_macos_services.sh
   ```

## Notes
- Some actions require administrator privileges. If prompted, enter your password.
- Works on modern macOS versions
- Running this script will briefly refresh macOS UI components.
