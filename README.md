# ML-ScikitLearn-Train
Machine Learning  -ScikitLearn-Train-DigitsExample

## Package
* Pandas
~~~
pip install pandas
~~~
* Matplotlib
~~~
# Ubuntu 
sudo apt-get install python-matplotlib
~~~
## 主成份分析（Principal Component Analysis, PCA）
* 面對這種高維度的資料（實務上還有其他很多像是財務或者氣候資料也都屬於高維度資料），需要用一些方法找出特別重要的二到三個變數，或者將許多的變數組合成更容易理解且視覺化的幾個維度。這種方法稱作降維（Dimensionality Reduction）
* 主成份分析的精神在於找出變數之間的線性關係組成新的一個主成份，然後使用這個主成份取代原有的變數，屬於一種最大化資料變異性的線性轉換方法
