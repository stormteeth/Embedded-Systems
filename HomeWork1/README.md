對圖片進行灰階的處理並且比較在有AVX和沒有AVX的情況下open和close的加速程度  
open方面  
有使用AVX加速耗時為:0.2643Sec  
未使用AVX元耗時為  :0.3285Sec  
Close方面  
有使用AVX加速耗時為:0.0130Sec  
未使用AVX元耗時為  :0.2854Sec  
很明顯的在使用AVX的狀態下能有效提升效率
