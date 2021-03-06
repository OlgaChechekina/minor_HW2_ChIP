# minor_HW2_ChIP
 Google Collab: https://colab.research.google.com/drive/1q0ltg0UvJim5RgRiyIEv7KqCfVIVzQwu?usp=sharing

Cell line: HeLa-S3
Histone mark: H3K36me3

FastQC показал, что качество прчтений хорошее. <br>
Фильтрация\подрезание чтений не требовалось

 * Summary
     ENCFF001FKV | ENCFF001FKT | ENCFF001HNS 
     --- | --- | --- 
     ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKV_FQC_1.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKT_FQC_1.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/HNS_FQC_1.PNG)

 * Per tile
     ENCFF001FKV | ENCFF001FKT | ENCFF001HNS 
     --- | --- | --- 
     ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKV_FQC_2.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKT_FQC_2.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/HNS_FQC_2.PNG)
  
    
 * SEQ & GC content
     ENCFF001FKV | ENCFF001FKT | ENCFF001HNS 
     --- | --- | --- 
     ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKV_FQC_3.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKT_FQC_3.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/HNS_FQC_3.PNG)
  
* Per base N content & seq length distribution
     ENCFF001FKV | ENCFF001FKT | ENCFF001HNS 
     --- | --- | --- 
     ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKV_FQC_4.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/FKT_FQC_4.PNG) | ![](https://github.com/OlgaChechekina/minor_HW2_ChIP/blob/main/FastQC_pics/HNS_FQC_4.PNG)  

#3. STATS

Процент выравнивания чтений низкий в связи с тем, что мы используем только одну хромосому а не весь геном.

![image](https://user-images.githubusercontent.com/60808830/157463130-878c9b56-416f-4e4a-ac62-c1f3bc019191.png)

#Venn Diagram
Малое число пересечений говорит о том, что выравнивание производилось на одну хромосому.
![image](https://user-images.githubusercontent.com/60808830/157752379-e942865d-c93e-45b0-91db-419f16c26bde.png)

Число пересечений отличается так как рассчитывается число пиков в первом файле, которые есть и во втором файле, а затем наоборот.
