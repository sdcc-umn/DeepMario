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

