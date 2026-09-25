# pfa-week03
Fiori Sims Week 3 Homework for Programming for Animators FA26 
Line 1: def create_saguaro(pos, tid, body_mat, spike_mat): 
"Def" defines the function. The function is "create saguaro", meaning create a saguaro variant of the cactus. The following sequence is a list. Position, tid (tuple identifier), body material, and spike material
Line 2: px, pz = pos[0], pos[2]: 
px and pz refer to coordinates/parameters within the program to generate the object, pos[0] is the starting position
Line 3: body_h = random.uniform(DT["height_min"], DT["height_max"])
        body_r = random.uniform(DT["radius_min"], DT["radius_max"]):
"h" and "r" are parameter values (height and radius) needed for the random.uniform function to generate a random floating-point number. DT refers to Decision Tree, which controls the minimum height and maximum height and same for radius. 
  

        


  
    
