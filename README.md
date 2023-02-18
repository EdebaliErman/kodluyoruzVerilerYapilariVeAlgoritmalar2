# kodluyoruzVerilerYapilariVeAlgoritmalar2
kodluyoruzVerilerYapilariVeAlgoritmalar2


#Merge Sort Projesi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
<hr>

[16,21,11,8,12,22] =>[16,21,11] && [8,12,22] <br>

[16,21,11]  |==| [8,12,22] <br>
[16]=[21,11] |==| [8] = [12,22]<br>
[16]=[11]=[21] |=| [8] = [12]&&[22]<br>
[16]=[11,21]|==|[8]|=|[12,22]<br>
[16,11,21]==[8,12,22]<br>
[11,16,21]==[8,12,22]<br>
[8,11,12,16,21]<br>
<hr>
<h2>Big-O=>O(n^2) </h2>

