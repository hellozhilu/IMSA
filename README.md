# IMSA
Binary code for the article "Iterated Multilevel Simulated Annealing for Large-Scale Graph Conductance Minimization"

1. For the source code, the format of input parameters are listed as follows,      
   **-f ./instance/luxembourg.graph -t 3600 -r 1 -g 50009947 -v 0.00013832 -n 0 -h 80 -s 10000 -y 0.98 -x 200000 -z 5 -c 60000**    
   Among them,   
   **-f ./instance/luxembourg.graph** //instancce file  
   **-t 3600**                        //maximum run time  
   **-r 1**                           //run counts  
   **-g 50009947**                    //random seed  
   **-v 0.00013832**                  //best-known result for current instance
   **-h 80**                          //Tabu tenure management factor of tabu search  
   **-s 10000**                       //Maximum number of consecutive non-improving iterations of tabu search  
   **-y 0.98**                        //Cooling ratio of SA search  
   **-x 200000**                      //Maximum number of iterations per temperature of SA search  
   **-z 5**                           //Frozen state parameter of SA search  
   **-c 60000**                       //Coarsening threshold  
   You can specify the parameters to match your needs when you execute the program.
  
2. Please make sure that the following paper is cited if you use the code in your research.    
   Lu, Z., Hao, J. K., Benlic, U., & Lesaint, D. (2021). Iterated multilevel simulated annealing for large-scale graph conductance minimization. Information Sciences, 572, 182-199.

3. The source code is distributed for academic purposes only.    
   If you wish to use it for commercial applications, please contact the authors (zhilusix@gmail.com, jin-kao.hao@univ-angers.fr).
