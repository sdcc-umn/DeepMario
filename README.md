# DeepMario
Deep Reinforcement Learning with Mario NES

The code is adopted from Maxim Lapan's Deep Reinforcement Learning Hands-on book. This is a work in progress

1. Create the virtual environment. This requires some of the following packages, among others:

gym-super-mario-bros

nes-py

2. Create a folder at the same level as the python files entitled 'benches'

To Run:

python 02_dqn_mario.py

or 

python 02_dqn_mario.py --cuda

for GPU

To get video using a benchmark .dat file:

python 03_dqn_play.py -m filename.dat

To save video to folder 'vid':

python 03_dqn_play.py -m filename.dat -r vid


To run in Colab:

1. Open ipynb file in colab

2. Upload 4 other python files to colab MANUALLY. I think there should be a way to clone this repository, but I didn't take the time to look at that.

3. At the same level of these files - in colab, create a folder named <benches> (without the < and >). This can be accomplished using 'ls' and 'mkdir' like on linux.
  
That should be all that is necessary. Just run each cell in the mario ipynb from top to bottom (there might be a 'run all' command). If the gpu is working, then it should run from 40-50 frames/second.

KEEP YOUR BROWSER open, and save things once every hour or so. If you don't have your browser open for 90 minutes, then the notebook is reset. Don't take more than 12 hours even with the browser open, or the notebook will be reset. 
