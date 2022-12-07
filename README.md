Matrix Multiplication Kernel
==================================================

**Texas Tech University, CS5375 Computer Systems Organization and Architecture, Project**

  * (TODO) Sravani Manduva
  * (TODO) R11800063.
  * (TODO) smanduva@ttu.edu.


   ### Normal CPU Code Execution

* Connect to the hppc
* Clone the Project https://github.com/shravani-radhakrishnan/COA_Project2.git
* cd COA_Project2
* ls 
* g++ matrixMul_cpu.cpp -o matrixMul_cpu.exe
* ./matrixMul_cpu.exe
* time ./matrixMul_cpu.exe
* All results are saved in results folder in Original file


    ### PART 1 

* interactive -p gpu-build 
* nvcc matrix_Mul_gpu_part1.cu -o matrix_Mul_gpu_part1.exe 
* ./matrix_Mul_gpu_part1.exe
* nvprof ./matrix_Mul_gpu_part1.exe
* Results are stored in Results folder in part1 file


    ### PART 2

* nvcc matrix_Mul_gpu_part2.cu -o matrix_Mul_gpu_part2.exe 
* ./matrix_Mul_gpu_part2.exe
* nvprof ./matrix_Mul_gpu_part2.exe
* Results are stored in Results folder in part2 file

    ### PART 3

* nvcc matrix_Mul_gpu_part3.cu -o matrix_Mul_gpu_part3.exe
* ./matrix_Mul_gpu_part3.exe
* nvprof ./matrix_Mul_gpu_part3.exe
* Results are stored in Results folder in part3 file

    ### PART 4

* nvcc matrix_Mul_gpu_part4.cu -o matrix_Mul_gpu_part4.exe 
* ./matrix_Mul_gpu_part4.exe 
* nvprof ./matrix_Mul_gpu_part4.exe 
* Results are stored in Results folder in part4 file




