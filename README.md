# Kodluyoruz-MergeSort </br >

### [16,21,11,8,12,22] -> Merge Sort aşamaları: </br >

                                                               [16,21,11,8,12,22] 
                                                               
                                                        [16,21,11]            [8,12,22]
                                                        
                                                    [16,21] [11]                  [8,12]  [22]
                                                    
                                                      [16] - [21] - [11] - [8] - [12] - [22]
                                                      
                                                        [16,21]       [8,11]       [12,22]
                                                        
                                                             [8,11,16,21]      [12,22]
                                                             
                                                                 [8,11,12,16,21,22]   


### Bu algoritmanın Big-O gösterimi şu şekildedir: </br >

2^x = n </br >
logn = x </br >
= O(nlogn) </br >
