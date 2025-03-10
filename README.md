# ICCAD2016_ExtendCase
To evaluate the scalability of the proposed method, we extend Case1-Case4 in ICCAD 2016 Contest (ProblemC pattern classification) by generating new markers abutting each marker in four directions, i.e., left, right, up and bottom directions. 
The number of markers for each extended cases are almost 5 times than their original cases. 

The extended cases generated are in GDSII format. The files are:

Extend_case1.gds.zip

Extend_case2.gds.zip

Extend_case3.gds.zip

Extend_case4.gds.zip

The Previous ICCAD 2016 Contest information and released cases can be find in the following work.

R. O. Topaloglu, “Iccad-2016 cad contest in pattern classification for integrated circuit design space analysis and benchmark suite,” in IEEE/ACM International Conference on Computer-Aided Design (ICCAD), 2016, p. 41. 
[Online]. Available: http://cad-contest-2016.el.cycu.edu.tw/problemC/default.html

The clustering legal check can be performed using our Linux binary executable file.

usage: ./checker/noshifting_cluster_checker <input_gds_file> <clip_width> <clip_height> <ECC constrain_number> <ACC constrain_number> <overlay_gds_file>

The clustering legalization checker is designed for ACC/ECC criteria in the ICCAD 2016 Contest. The ECC check, which is more complex than ACC, is computed using the method proposed in:

[1] Xu He, Yipei Wang, Zhiyong Fu, Yao Wang, Yang Guo. Maximum Clique Based Method for Optimal Solution of Pattern Classification, ICCD, 2020.

Other related works are:

[2] Xu He, Yao Wang, Zhiyong Fu, Yipei Wang, Yang Guo, A General Layout Pattern Clustering Using Geometric Matching Based Clip Relocation and Lower-Bound Aided Optimization, ACM Transactions on Design Automation of Electronic Systems (TODAES), v28(6), 2023.

[3] Congyi Zhang, Xu He, Hao Sang, Hengzhou Yuan, Dawei Liu, Yang Guo, A general and accurate pattern search method for various scenarios, Integration, the VLSI Journal, v100(102281), 2025.
