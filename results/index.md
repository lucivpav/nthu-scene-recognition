<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.068
<p>

<table border=0 cellpadding=4 cellspacing=1>
<tr>
<th>Category name</th>
<th>Accuracy</th>
<th colspan=2>Sample training images</th>
<th colspan=2>Sample true positives</th>
<th colspan=2>False positives with true label</th>
<th colspan=2>False negatives with wrong predicted label</th>
</tr>
<tr>
<td>Kitchen</td>
<td>0.070</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0172.jpg" width=57 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0039.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0098.jpg" width=68 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0071.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0004.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0138.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0190.jpg" width=57 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0042.jpg" width=57 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.090</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0131.jpg" width=112 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0142.jpg" width=76 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0014.jpg" width=44 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0122.jpg" width=74 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0014.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0126.jpg" width=57 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0052.jpg" width=100 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0009.jpg" width=100 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.060</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0216.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0105.jpg" width=110 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0176.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0095.jpg" width=101 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0051.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0097.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0158.jpg" width=100 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0049.jpg" width=101 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.050</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0075.jpg" width=114 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0192.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0062.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0008.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0100.jpg" width=134 height=75><br><small>Office</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0174.jpg" width=117 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0003.jpg" width=114 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0102.jpg" width=113 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.080</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0189.jpg" width=94 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0056.jpg" width=130 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0120.jpg" width=116 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0179.jpg" width=103 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0128.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0078.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0003.jpg" width=115 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0029.jpg" width=102 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.100</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0136.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0212.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0052.jpg" width=105 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0116.jpg" width=126 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0094.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0027.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0028.jpg" width=114 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0059.jpg" width=111 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.030</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0010.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0097.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0015.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0172.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0084.jpg" width=107 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0046.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0101.jpg" width=113 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0023.jpg" width=113 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.050</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0101.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0281.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0132.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0100.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0023.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0053.jpg" width=57 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0130.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0029.jpg" width=75 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.050</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0060.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0258.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0043.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0038.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0070.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0024.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0075.jpg" width=75 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0070.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.050</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0209.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0123.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0078.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0047.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0002.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0059.jpg" width=110 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0034.jpg" width=75 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0086.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.040</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0209.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0145.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0062.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0052.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0096.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0028.jpg" width=57 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0133.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0070.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.100</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0367.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0291.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0106.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0015.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0018.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0122.jpg" width=101 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0125.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0080.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.080</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0290.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0354.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0084.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0105.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0180.jpg" width=78 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0123.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0044.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0074.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.120</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0208.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0102.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0079.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0077.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0026.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0083.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0045.jpg" width=75 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0023.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.050</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0309.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0193.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0080.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0118.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0066.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0089.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0101.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0088.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<th>Category name</th>
<th>Accuracy</th>
<th colspan=2>Sample training images</th>
<th colspan=2>Sample true positives</th>
<th colspan=2>False positives with true label</th>
<th colspan=2>False negatives with wrong predicted label</th>
</tr>
</table>
</center>


<h2>Extra</h2>
<h3>vocabulary size parameter (up to 3 pts)</h3>
Performance of bag of words feature representation in combination with SVM classifier has been tested under the following vocabulary size parameters: <a href="../results_vocab10/index.md">10</a>, <a href="../results_vocab20/index.md">20</a>, <a href="../results_vocab50/index.md">50</a>, <a href="../results_vocab100/index.md">100</a>, <a href="../results_vocab200/index.md">200</a>, <a href="../results_vocab400/index.md">400</a>, <a href="../results_vocab1000/index.md">1000</a>, <a href="../results_vocab10000/index.md">10000</a>

As discovered, <i>the larger the vocabulary, the better the accuracy</i> is true up to size of 400. After that, there were too many clusters to bring an extra value, and the performance was decreasing.
