### Abstract submission
* [Latex Project](https://tiny.one/latexZip)
* [Abstract PDF](https://tiny.one/AbstractPaper)

### Video Demo
* Download/Watch video demo of [results](https://tiny.one/ProjectVideo)

### Requirements

* python 3.8
* opencv-python
* pygame

### Installation

1. Step 1: Download and install [libraqm](https://github.com/HOST-Oman/libraqm)
   ```sh
   $ sudo apt-get install libfreetype6-dev libharfbuzz-dev libfribidi-dev meson gtk-doc-tools
   $ git clone https://github.com/HOST-Oman/libraqm.git
   $ cd libraqm
   ```
   ```sh
   $ meson build
   $ ninja -C build
   $ ninja -C build install
   ```   


2. Step 2: Download, extract and install [pygame](https://tiny.one/pyGame)

   ```sh
   $ sudo apt-get install python3-dev python3-numpy libsdl-dev libsdl-image1.2-dev  libsdl-mixer1.2-dev libsdl-ttf2.0-dev libsmpeg-dev libportmidi-dev libavformat-dev libswscale-dev libjpeg-dev libfreetype6-dev libsdl-ttf2.0-0
   ```
   ```
   $ cd pygame
   $ python3 setup.py
   ```
3. Step 3: Download and install [requirements](https://tiny.one/requirements)

    ```
    pip install -r requirements.txt
    ```
4. Step 4: Download and extract Dataset [Part A](https://tiny.one/PartA) and [Part B](https://tiny.one/PartB)
5. Step 5: Download and extract [project file](https://tinyurl.com/FilesCode)
6. Step 6: Edit path/directories and run project
### Acknowledgement
* [SynthText](https://github.com/ankush-me/SynthText)
* [SRNet](https://github.com/youdao-ai/SRNet)
