```bash
echo "deb [trusted=yes] https://github.com/serhiivysotskyi/keyboard_teleop/raw/jammy-iron-amd64/ ./" | sudo tee /etc/apt/sources.list.d/serhiivysotskyi_keyboard_teleop.list
echo "yaml https://github.com/serhiivysotskyi/keyboard_teleop/raw/jammy-iron-amd64/local.yaml iron" | sudo tee /etc/ros/rosdep/sources.list.d/1-serhiivysotskyi_keyboard_teleop.list
```
