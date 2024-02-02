# IMSA
Binary code for the article "Iterated Multilevel Simulated Annealing for Large-Scale Graph Conductance Minimization"

1. For the binary code, you can specify the parameters to match your needs when you execute the code. The code was tested on a computer under the Linux operating system.  
   The format of input parameters is listed as follows,      
   **./src/IMSA.exe -f ./instance/luxembourg.graph -t 3600 -r 1 -n 0 -g 50009947 -v 0.00013832 -c 60000 -x 200000 -y 0.98 -z 5 -s 10000 -h 80**    
   Among them,  
   **./src/IMSA.exe**                 //binary code  
   **-f ./instance/luxembourg.graph** //input instance file  
   **-t 3600**                        //cutoff time per run (3600 seconds)  
   **-r 1**                           //run counter  
   **-n 0**                           //input MQI file no.  
   **-g 50009947**                    //random seed  
   **-v 0.00013832**                  //best-known result for the current instance  
   **-c 60000**                       //coarsening threshold  
   **-x 200000**                      //maximum number of iterations per temperature of SA search  
   **-y 0.98**                        //cooling ratio of SA search  
   **-z 5**                           //frozen state parameter of SA search  
   **-s 10000**                       //maximum number of consecutive non-improving iterations of tabu search  
   **-h 80**                          //tabu tenure management factor of tabu search  
   If you have any questions feel free to contact me (Zhi Lu: zhilusix@gmail.com).
  
2. Please make sure that the following paper is cited if you use the code in your research.    
   Lu, Z., Hao, J. K., Benlic, U., & Lesaint, D. (2021). Iterated multilevel simulated annealing for large-scale graph conductance minimization. Information Sciences, 572, 182-199.

3. The binary code is distributed for academic purposes only.    
   If you wish to use it for commercial applications, please contact the authors (Zhi Lu: zhilusix@gmail.com, Jin-Kao Hao: jin-kao.hao@univ-angers.fr).
