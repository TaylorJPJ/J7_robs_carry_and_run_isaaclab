# J7_robs_carry_and_run_isaaclab

- *thisdoc* is a problems and solutions found while setting and running the isaaclab.
- there are lots codes files in the isaaclab, not all functions is mentioned.
- author runs the IsaacLab in Window11 now, while it is more suitable in Linux environment.

## version problem 
the universal and easy way of setting the environment is creating the conda envrionment.
while the version of the python is closely related to the IsaacSim,.
For *IsaacSim* 5.X, the version of python is 3.11.
For *IsaacSim* 4.X, the version of python is 3.10.

## Run the isaaclab
In the doc of isaaclab, if you want to setup the lab of reinforcement learning, run 
'''
isaaclab.bat --install :: or "isaaclab.bat -i"
'''
If this can't work, change this code as
'''
./isaaclab.bat --install
'''
What's more, if some lab can't run, use the code 
'''
./isaaclab.bat --install XXXXX
'''
*XXXXX* can be **rl_game**, **rsl_rl** etc, install **rl_game** may not availible for user of China mainland, change the web of download path. 
