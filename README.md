# pixid Auto Export Plugin for Lightroom

## Installation Instructions

### Requirements
- Adobe Lightroom Classic 5.0 or later
- Windows or macOS

### Installation Steps

1. **Download the Plugin**
   - Download `pixid-auto-export-vX.X.X.zip` from the releases page
   - DO NOT unzip the file

2. **Install in Lightroom**
   - Open Lightroom Classic
   - Go to `File → Plug-in Manager`
   - Click `Add` button
   - Navigate to and select the downloaded ZIP file
   - Click `Add Plug-in`

3. **Access the Plugin**
   - Go to `File → Plug-in Extras → pixid Auto Export`
   - Configure your settings
   - Click "Start Auto-Processing" to begin

## Configuration

### Basic Settings
- **Session Selection**: Choose which session folder to monitor
- **Output Folder**: Where to save exported JPEGs
- **Photo Size**: Export size (1500px to 4000px or original)

### Processing Options
- **Apply Presets**: Automatically apply presets from Favorites folder
- **File Size Limit**: Optionally limit JPEG file size
- **Batch Size**: Number of photos to process at once
- **Wait Time**: Seconds to wait between batches

### FTP Upload (Optional)
- Enable FTP upload to pixid servers
- Enter your pixid username and password

## Usage

### One-Time Processing
Click "Process Once Now" to process all pending photos immediately

### Continuous Auto-Processing
1. Click "Start Auto-Processing" to begin monitoring
2. Plugin will check for new photos every 30 seconds
3. Processes photos in batches to avoid blocking tethering
4. Click "Stop Auto-Processing" to end monitoring

## How It Works

The plugin monitors your selected session folder for photos with rating = 0 and:
1. Applies develop presets from your Favorites folder
2. Exports as JPEG to your specified output folder
3. Optionally uploads to pixid FTP server
4. Updates photo rating to track progress (0→1→2→3)

## Support

For issues or questions, please open an issue on GitHub.