# Paper of Logic-In-Memory
Collection of lecture about logic-in-memory(mostly based on RRAM) in these years（mostly 2015-2022）
About：

Some famous team of logic in memory
  - TEAM~[Shahar Kvatinsky](https://scholar.google.com.au/citations?user=6KHkduEAAAAJ&hl=en), Israel Institute of Technology
  - TEAM~[Tajana Simunic Rosing](https://scholar.google.com/citations?hl=en&user=3smyfesAAAAJ&view_op=list_works&sortby=pubdate), UC San Diego
  - TEAM~[Said Hamdioui](https://scholar.google.com/citations?user=La560wQAAAAJ&hl=fr), Delft University of Technology
  - TEAM~[Giovanni De Micheli](https://scholar.google.com/citations?user=7SUnVDsAAAAJ&hl=en), EPFL
  - TEAM~[Rolf Drechsler](https://scholar.google.com/citations?hl=en&user=9v_MAAIAAAAJ&view_op=list_works&sortby=pubdate), University of Bremen
  - TEAM~[Rickard Ewetz](https://scholar.google.com/citations?hl=en&user=h_RaG-8AAAAJ&view_op=list_works&sortby=pubdate), University of Central Florida
  - TEAM~[Anupam Chattopadhyay](https://scholar.google.com/citations?user=TIt4ggwAAAAJ&hl=en&oi=ao), Nanyang Technological University
  - TEAM~[Guojie Luo](https://scholar.google.com/citations?user=8-mT29YAAAAJ&hl=zh-CN), Peking University
  - TEAM~[Xiaoming Chen](https://scholar.google.com/citations?user=Qkyxst8AAAAJ&hl=zh-CN), Institute of Computing Technology, CAS
  - ...
## LOGIC STRUCTURE: In compilation process of logic synthesis, code in HDL will be translate into uniform DAG expression for the following optimization
  - SOP(sum of product),example paper : " SAID : A Supergate-Aided Logic Synthesis Flow for Memristive Crossbars " [PDF](https://ieeexplore.ieee.org/document/8714939)
    - Valerio Tenace; Roberto G. Rizzo; Debjyoti Bhattacharjee; Anupam Chattopadhyay; Andrea Calimera (DATE 2019)
  - BDD(Binary decision diagrams): " Graph-Based Algorithms for Boolean Function Manipulation " [PDF](https://ieeexplore.ieee.org/document/1676819)
    - Bryant (TC 1986)
  - AIG(And inverte graph)

## logic family design
**Survey:**
  - Memristive Logic: A Framework for Evaluation and Comparison [PDF](https://ieeexplore.ieee.org/document/8106959)
    - John Reuben; Rotem Ben-Hur; Nimrod Wald; Nishil Talati; Ameer Haj Ali; Pierre-Emmanuel Gaillardon; Shahar Kvatinsky  .(PATMOS 2017)   

**compute-in-crossbar:**
**the output is written in output RRAM while computing**
- 'Memristive' switches enable 'stateful' logic operations via material implication [PDF](https://www.nature.com/articles/nature08940)
  - Julien Borghetti, Gregory S. Snider, Philip J. Kuekes, J. Joshua Yang, Duncan R. Stewart & R. Stanley Williams	.(NATURE 2010)
- Complementary resistive switches for passive nanocrossbar memories [PDF](https://www.nature.com/articles/nmat2748#citeas)
  - Eike Linn, Roland Rosezin, Carsten Kügeler & Rainer Waser. (Nature Materials 2010)
- Crossbar Logic Using Bipolar and Complementary Resistive Switches [PDF](https://ieeexplore.ieee.org/document/5749689)
  - R. Rosezin, E. Linn, C. Kügeler, R. Bruchhaus, and R. Waser.  (IEEE Electron Device Letters 2011)
- Beyond von Neumann—logic operations in passive crossbar arrays alongside memory operations [PDF](https://iopscience.iop.org/article/10.1088/0957-4484/23/30/305205/meta)
  - E Linn, R Rosezin, S Tappertzhofen, U Böttger and R Waser	.(Nanotechnology 2012)
- MAGIC—Memristor-Aided Logic [PDF](https://ieeexplore.ieee.org/document/6895258)
  - Shahar Kvatinsky, Dmitry Belousov, Slavik Liman, Guy Satat, Nimrod Wald, Eby G. Friedman, Avinoam Kolodny, Uri Weiser	.(TCAS-II 2014)
- Boolean Logic Operations and Computing Circuits Based on Memristors [PDF](https://ieeexplore.ieee.org/document/6895305)
  - Georgios Papandroulidakis; Ioannis Vourkas; Nikolaos Vasileiadis; Georgios Ch. Sirakoulis (TCAS-II 2014)
- Fast boolean logic mapped on memristor crossbar [PDF](https://ieeexplore.ieee.org/document/7357122)
  - Lei Xie; Hoang Anh Du Nguyen; Mottaqiallah Taouil; Said Hamdioui; Koen Bertels (ICCD 2015)
- Logic Design Within Memristive Memories Using Memristor-Aided loGIC (MAGIC) [PDF](https://ieeexplore.ieee.org/document/7471529)
  -  Nishil Talati;Saransh Gupta;Pravin Mane;Shahar Kvatinsky	(TNANO 2016)
- Crossbar-Based Memristive Logic-in-Memory Architecture [PDF](https://ieeexplore.ieee.org/document/7893787)
  - Georgios Papandroulidakis; Ioannis Vourkas; Angel Abusleme; Georgios Ch. Sirakoulis; Antonio Rubio .(TNANO 2017)
- MAD Gates—Memristor Logic Design Using Driver Circuitry [PDF](https://ieeexplore.ieee.org/document/7448841)
  - Lauren Guckert; Earl E. Swartzlander (TCAS-II 2017)
- FELIX: Fast and Energy-Efficient Logic in Memory [PDF](https://ieeexplore.ieee.org/document/8587724) (based-on MAGIC,fast)
  - Saransh Gupta; Mohsen Imani; Tajana Rosing (ICCAD 2018)
- Memristive Computational Memory Using Memristor Overwrite Logic (MOL) [PDF](https://ieeexplore.ieee.org/document/9160878)
  - Khaled Alhaj Ali;Mostafa Rizk;Amer Baghdadi;Jean-Philippe Diguet;Jalal Jomaah;Naoya Onizawa;Takahiro Hanyu	.(TVLSI 2020)
- RIME: A Scalable and Energy-Efficient Processing-In-Memory Architecture for Floating-Point Operations [PDF](https://ieeexplore.ieee.org/document/9371583)
  - Zhaojun Lu; Md Tanvir Arafin; Gang Qu (ASP-DAC 2021)



**push-to-periphery**:
**RRAM in crossbar is voltage dividers, input/output are voltages**
- Nanowire-based programmable architectures [PDF](https://dl.acm.org/doi/10.1145/1084748.1084750) (Note: need inverters to be logical completeness)
  - ANDRE´ DEHON. (ACM Journal on Emerging Technologies in Computing Systems 2005)
- MRL–Memristor Ratioed Logic [PDF](https://ieeexplore.ieee.org/document/6331426)
  - Shahar Kvatinsky; Nimrod Wald; Guy Satat; Avinoam Kolodny; Uri C. Weiser; Eby G. Friedman. (CNNA 2012)
- Logic operations in memory using a memristive Akers array [PDF](https://dl.acm.org/doi/10.1016/j.mejo.2014.06.006)
  - Yifat Levy, Jehoshua Bruck, Yuval Cassuto, Eby G.Friedman, Avinoam Kolodny, Eitan Yaakobi, Shahar Kvatinsky. (Microelectronics Journal 2014)
- Computation of Boolean Formulas Using Sneak Paths in Crossbar Computing .[PDF](https://www.google.com.hk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwjB0Ymv2OOAAxWk6jgGHdZiA7YQFnoECBIQAQ&url=https%3A%2F%2Fstars.library.ucf.edu%2Fcgi%2Fviewcontent.cgi%3Farticle%3D2831%26context%3Dhonorstheses1990-2015&usg=AOvVaw1LZd-7zj6rPb4AVmjuHdnX&opi=89978449) (interesting paper,using sneak path for logic)
  - Alvaro Velasquez (Advisor: Sumit Kumar Jha, Honors Theses of UCF, 1990-2015)
- Pinatubo: A processing-in-memory architecture for bulk bitwise operations in emerging non-volatile memories
  - Shuangchen Li; Cong Xu; Qiaosha Zou; Jishen Zhao; Yu Lu; Yuan Xie  .DAC 2016	[PDF](https://ieeexplore.ieee.org/document/7544414)
- Reconfigurable In-Memory Computing with Resistive Memory Crossbar [PDF](https://ieeexplore.ieee.org/document/7827697) (two level logic,basic of L-Si)
  - Yue Zha, Jing Li (ICCAD 2016)
- MPIM: Multi-Purpose In-Memory Processing Using Configurable Resistive Memory [PDF](https://ieeexplore.ieee.org/document/7858415)
  - Mohsen Imani; Yeseong Kim; Tajana Rosing (ASP-DAC 2017)
- Scouting Logic: A Novel Memristor-Based Logic Design for Resistive Computing [PDF](https://ieeexplore.ieee.org/document/7987515)
  - Lei Xie; H.A. Du Nguyen;Jintao Yu;Ali Kaichouhi;Mottaqiallah Taouil;Mohammad Gh. Alfailakawi;Said Hamdioui. (ISVLSI 2017) 
- A Parallel-friendly Majority Gate to Accelerate In-memory Computation [PDF](https://ieeexplore.ieee.org/document/9153277)  (time-based SA)
  - John Reuben; Stefan Pechmann (ASAP 2020)
 



**search-after-storage** :
**RRAM can be used to store the truth table of function, In a narrow sense, this is not memory computing but more like Non-volatile FPGA**
- Fpga based on integration of CMOS and RRAM [PDF](https://ieeexplore.ieee.org/document/5560770)
  - Sansiri Tanachutiwat; Ming Liu; Wei Wang .(TVLSI 2011)
- Nonvolatile 3D-FPGA with monolithically stacked RRAM-based configuration memory [PDF](https://ieeexplore.ieee.org/document/6177067)
  - Young Yang Liauw; Zhiping Zhang; Wanki Kim; Abbas El Gamal; S. Simon Wong .(ISSCC 2012)
- An Offset-Tolerant Fast-Random-Read Current-Sampling-Based Sense Amplifier for Small-Cell-Current Nonvolatile Memory [PDF](https://ieeexplore.ieee.org/document/6407149)
  - Meng-Fan Chang, Shin-Jang Shen, Chia-Chi Liu, Che-Wei Wu, Yu-Fan Lin, Ya-Chin King, Chorng-Jung Lin, Hung-Jen Liao, Yu-Der Chih, and Hiroyuki Yamauchi. (JSSC 2013)
- Merging Everything (ME): A Unified FPGA Architecture Based on Logic-in-Memory Techniques [PDF](https://ieeexplore.ieee.org/document/8806845)
  - Xiaoming Chen, Longxiang Yin, Bosheng Liu, and Yinhe Han.	(DAC 2019)
- Meltrix: A RRAM-Based Polymorphic Architecture Enhanced by Function Synthesis [PDF](https://ieeexplore.ieee.org/document/10323544)
  - Boyu Long, Libo Shen, Xiaoyu Zhang, Yinhe Han, Xian-He Sun, Xiaoming Chen. (ICCAD 2023)


### synthesis design
- A General Logic Synthesis Framework for Memristor-based Logic Design [PDF](https://ieeexplore.ieee.org/document/8942111)
  - Zhenhua Zhu; Mingyuan Ma; Jialong Liu; Liying Xu; Xiaoming Chen; Yuchao Yang; Yu Wang; Huazhong Yang (ICCAD 2019)

- An MIG-based Compiler for Programmable Logic-in-Memory Architectures [PDF](https://ieeexplore.ieee.org/document/7544359)
  - Mathias Soeken; Saeideh Shirinzadeh; Pierre-Emmanuel Gaillardon; Luca Gaetano Amarú; Rolf Drechsler; Giovanni De Micheli (DAC 2016)

- SAID : A Supergate-Aided Logic Synthesis Flow for Memristive Crossbars  [PDF](https://ieeexplore.ieee.org/document/8714939)
    - Valerio Tenace; Roberto G. Rizzo; Debjyoti Bhattacharjee; Anupam Chattopadhyay; Andrea Calimera (DATE 2019)

- Meltrix: A RRAM-Based Polymorphic Architecture Enhanced by Function Synthesis [PDF](https://ieeexplore.ieee.org/document/10323544)
  - Boyu Long, Libo Shen, Xiaoyu Zhang, Yinhe Han, Xian-He Sun, Xiaoming Chen. (ICCAD 2023)

- LIM-GEN: A Data-Guided Framework for Automated Generation of Heterogeneous Logic-in-Memory Architecture. [PDF](https://ieeexplore.ieee.org/document/10323837)
  - Libo Shen; Boyu Long; Rui Liu; Xiaoyu Zhang; Yinhe Han; Xiaoming Chen (ICCAD 2023) 

### architecture design
- Deep Learning Acceleration using Digital-Based Processing In-Memory [PDF](https://ieeexplore.ieee.org/document/8980299)
  - Mohsen Imani; Saransh Gupta; Yeseong Kim; Tajana Rosing (ISCA 2019)
- FloatPIM: In-Memory Acceleration of Deep Neural Network Training with High Precision [PDF](https://ieeexplore.ieee.org/document/9524776)
  - Mohsen Imani; Saransh Gupta; Yeseong Kim; Tajana Rosing (SOCC 2020)

- The Programmable Logic-in-Memory (PLiM) computer [PDF](https://ieeexplore.ieee.org/abstract/document/7459349)
  - Pierre-Emmanuel Gaillardon; Luca Amarú; Anne Siemon; Eike Linn; Rainer Waser; Anupam Chattopadhyay; Giovanni De Micheli (DATE 2016)
- ReVAMP: ReRAM based VLIW architecture for in-memory computing [PDF](https://ieeexplore.ieee.org/abstract/document/7927095)
  - Debjyoti Bhattacharjee; Rajeswari Devadoss; Anupam Chattopadhyay (DATE 2017)

- LIM-GEN: A Data-Guided Framework for Automated Generation of Heterogeneous Logic-in-Memory Architecture. [PDF](https://ieeexplore.ieee.org/document/10323837)
  - Libo Shen; Boyu Long; Rui Liu; Xiaoyu Zhang; Yinhe Han; Xiaoming Chen (ICCAD 2023) 





