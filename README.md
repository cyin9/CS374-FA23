# CS374-FA23: Industrial Visualizer

## Getting Started

### Prerequisites
- A compatible radar device is required.
- Python with necessary libraries (numpy, matplotlib, scipy, etc.) installed.
- Industrial_Visualizer should be present and properly set up.

### Testing with Existing Data
To test the application with pre-existing data:
1. Modify the `binDirPath` variable in the `draw` function to point to the desired folder inside the `test_data` directory.
2. Run the script to visualize this test data.

### Running with Your Own Radar
To use the tool with your radar:
1. Connect your radar to your computer.
2. Execute `Industrial_Visualizer` with the `fp.cfg` configuration.
3. Position a corner reflector in front of the radar within the range and azimuth plane.
4. Capture data across 100 frames.
5. Post-capture, update the `binDirPath` to the corresponding folder in the `binData` results directory.
6. Execute the `draw` function to visualize your captured data.

## Features
- **Data Visualization**: Transforms radar data into an easy-to-understand visual format.
- **Point Cloud Processing**: Analyzes 3D point cloud data, highlighting key points and movement patterns.
- **On-Off Switchpoint Detection**: Demonstrates basic on-off switchpoint detection (note: this feature has limited capabilities).

## Limitations
- The on-off switchpoint detection is rudimentary and might not represent complex situations adequately.
- Proper radar setup and configuration are crucial for accurate data capture.
