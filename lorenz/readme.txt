########### Experiment ####################
Initialize 200 random points
Intialize random z inputs
Bound them to x(-20,20) y(-30,30) z(0,50) using sigmoid
Add perturbation (eps = 0.01).
Now we have xA and xB (with perturbation)
Get the trajectories from the  2 model for T = 100
Optimize using loss function 
After optimization find the average separation of 200 points 
Repeat it for time steps ranging from 100 to 1500
Plot the graph

####### NIO_theory_exp_3D ####################
perturbation in x y z and optimizes x,y,z.
plotting the avg separation at T
compare it with eps * e^(lambda * dt * T) for different time step


####### NIO_theory_exp_1D ####################
perturbation in x and optimizes only x.
y and z are initialized random first and kept constant during optimization
plotting the avg separation at T
compare it with eps * e^(lambda * dt * T) for different time step