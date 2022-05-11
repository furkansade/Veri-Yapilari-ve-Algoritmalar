Proje-1

[22,27,16,2,18,6] -> Insertion Sort

1)
1- [22,27,16,2,18,6] ---> [22,27,16,2,18,6]  (22 ile 27 kıyaslaması.)

2- [22,27,16,2,18,6] ---> [22,16,27,2,18,6] ---> [16,22,27,2,18,6] (16 ile 22 ve 27 kıyaslaması.)

3- [16,22,27,2,18,6] ---> [16,22,2,27,18,6] ---> [16,2,22,27,18,6] ---> [2,16,22,27,18,6] (2 ile 2'nin solundakilerin kıyaslanması.)

4- [2,16,22,27,18,6] ---> [2,16,22,18,27,6] ---> [2,16,18,22,27,6] (16 ile solundakilerin kıyaslanması.)

5- [2,16,18,22,27,6] ---> [2,16,18,22,6,27] ---> [2,16,18,6,22,27] ---> [2,16,6,18,22,27] ---> [2,6,16,18,22,27] (6 ile solundakilerin kıyaslanması.)

2)
Big O-Notation : O(n^2)

3)
Time Complexity: 	
	Best Case: n
	Avarage Case: n^2
	Worst Case: n^2 

4)
18 sayısı aradğımız dizide ortada olduğu için "Avarage Case" kapsamına girer.

[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

1- [7,3,5,8,2,9,4,15,6]
2- [3,7,5,8,2,9,4,15,6]
3- [3,5,7,8,2,9,4,15,6]
4- [3,5,7,8,2,9,4,15,6]
