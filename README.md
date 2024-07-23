# 3D-Rendering-Camera-Rotation-Torch

### Overview

This project renders images of a 3D cube from different angles by rotating the camera around it (using PyTorch). The rendered images are saved in a directory and zipped for easy download and sharing.

### Example Output

The script will render images of a cube as seen from different angles by moving the camera in a circular path around the cube. Each image represents a different view angle of the stationary cube.

### Customization

- **Field of View (FOV)**: Adjust the `fov` variable to change the field of view of the camera.
- **Aspect Ratio**: Change the `aspect_ratio` variable to adjust the aspect ratio of the projection.
- **Radius Range**: Modify the `radius_range` variable to change the range of radii for the camera's circular path.
- **Number of Steps**: Change the `num_steps` variable to alter the number of steps (frames) in one complete rotation.

### Notes

- Ensure the output directories exist before running the script.
- The script will automatically create the directories if they do not exist.
