python3 -m venv new-env --system-site-packages
source new-env/bin/activate
sudo apt-get install libgtk2.0-dev libcanberra-gtk-module libcanberra-gtk3-module
pip install ultralytics
pip uninstall opencv-python opencv-python-headless
pip install opencv-python
python3 main.py
