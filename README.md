# High-Performance-Computing
## 高性能计算-基础并行  
程序的并行执行不仅仅和硬件相关，和算法的并行化设计分析有很大关系。  
* 并行程序设计导论：Peter,讲述MPI，pthread,openMP并行。
  * MPI可以参考mpi4py Python库，可以快速验证一些标准概念诸如（通信子，rank,数据收发，broadcast，gather，scatter等通信原语）。
  [mpi4py-examples](https://github.com/jbornschein/mpi4py-examples).  
  * pthread可以参考C++11的thread多线程并发功能和Java多线程。  
  * openMP可以参考[openMP资源](https://www.openmp.org/resources/)和[openMP简易教程-海康流行版本](http://read.pudn.com/downloads632/ebook/2565497/OpenMP%E7%AE%80%E6%98%93%E6%95%99%E7%A8%8B.pdf)
  
  
## 高性能计算-CUDA
### GPU编程优化-大众高性能计算
 * 理论篇：向量机和阵列机结构区别，英伟达GPU代次的计算能力单元硬件结构和功能差异。  
 * 入门篇：总共四个范例，对应优达学城parallel-map,reduce,stencil,shared-memory例子，对应优达学城03节课。   
 * 提高篇：讲述卷积（conv)，规约（scan),归并排血、双调排血，奇偶排序，图像处理等高阶例子。 对应优达学城04节课 。     
 * 核心篇：讲述GPU存储器体系（类似存储器山，openMP-MPI-Multi-Cuda)编程，可以和《并行编程导论》参考阅读。  
### 优达学城GPU编程  
  参考GPU编程资料中04优达城GPU编程
 * 链接: https://pan.baidu.com/s/1NZt1ZW1qenXlOOPt07ZPfA 提取码: j69p  
 
 
## 高性能计算-SIMD指令集  
当前流行的avx2和arm-NEON指令。未涉猎。参考资料：
  * 未找到相关资料
