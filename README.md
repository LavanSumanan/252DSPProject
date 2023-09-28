# Project Description
Investigation into using filtering to create 1) a filter for 60hz noise in signals and 2) a robotic voice filter for human speech signals collected in a wav file.

Overall Breakdown:
1. Downsampling
2. Time Chunking
3. Filtering
4. Voice Synthesis


# Project Config

1. Ensure virtualenv is installed, and if not, run ` python3 -m pip install --user -U virtualenv`
2. Within the root folder "Project," create a virtual environment by running `virtualenv env` and activate it by running `.\env\Scripts\activate` on Windows or `source env/bin/activate` on Mac/Linux
3. Install dependencies by running `python3 -m pip install -U jupyter matplotlib numpy pandas scipy`
4. In VSCode, open up a jupyter notebook and ensure you are using the correct python environment by clicking on "kernel" in the top right and selecting "env (Python 3.x.x)"
