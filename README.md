<h1> Insertion Sort </h1>
<h2>[22,27,16,2,18,6]</h2>
<h3>1- <p> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</p>
</h3>
    <ol>
        <li>[22,27,16,2,18,6] n</li>
        <li>[2,27,16,22,18,6] n-1
        </li>
        <li>
            [2,6,16,22,18,27] n-2</li>
        <li>[2,6,16,18,22,27] 1</li>
    </ol>

<h3>2-Big-O gösterimi;</h3>
<p>
    n + (n-1) + (n-2) + 1 = n.(n+1) / 2 

    ( n² +n) / 2 =  O(n²)
</p>
<h3>
    3-Time Complexity: Average Case, Worst Case, Best Case durumları;
</h3>
<p>
    [2,6,16,18,22,27]
   <ul>
       <li>Average Case--> 16,18</li>
       <li>
        Worst Case--> 2 </li>
       <li>
        Best Case--> 2
       </li>
   </ul>

</p>
<h3>4-Dizi sıralandıktan sonra 18 sayısı Average Case kapsamına girer
</h3>

<h3>
    [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımı;
</h3>
<ul>
    <li>[7,3,5,8,2,9,4,15,6]--> n </li>
    <li>[2,3,5,8,7,9,4,15,6]--> n-1 </li>
    <li>[2,3,4,8,7,9,5,15,6]--> n-2 </li>
    <li>[2,3,4,5,7,9,8,15,6]--> n-3 </li>
    <li>[2,3,4,5,6,9,8,15,7]--> n-4 </li>
</ul>
<hr>
<h1>Merge Sort</h1>
<h2>
    [16,21,11,8,12,22]
</h2>
   
     Yukarıdaki dizinin sort türüne göre aşamaları;
  <br>

    
```
        [16,21,11,8,12,22]

    [16,21,11]       [8,12,22]

 [16]   [21,11]       [8,12]   [22]

[16]   [21]  [11]    [8]  [12]  [22]

 [16]  [11,21]         [8,12]  [22]

    [11,16,21]       [8,12,22]

         [8,11,12,16,21,22]
         
 ```

<h3> 2. Big-O gösterimi;</h3>
<p>O(nlogn)</p>

<hr>

<h1>Binary Search Tree Projesi</h1>
<h3>[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları;</h3>


Binary Search  diziyi manipüle ederek aşağıdaki ifadeye dönüştürür;

[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]

9 en büyük sayı,
4 ortanca sayı,
0 en küçük sayı ilan edilir.

Bu şekilde;
"Root: 4 / Solunda: 3 / Sağında: 5" bulunur.


```
Binary Search Tree: 

        4
      /   \
     3     5 
   /      /  \
  1      7    8
 / \    /      \
0   2   6       9

```

<br>
<hr>
<br>


```
