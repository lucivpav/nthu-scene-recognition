<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.161
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
<td>0.050</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0067.jpg" width=141 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0034.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0129.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0124.jpg" width=57 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0119.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0074.jpg" width=116 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0122.jpg" width=57 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0104.jpg" width=115 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.010</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0208.jpg" width=103 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0294.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0015.jpg" width=100 height=75></td>
<td bgcolor=LightGreen></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0010.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0124.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0004.jpg" width=60 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0087.jpg" width=107 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.110</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0139.jpg" width=50 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0089.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0035.jpg" width=115 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0037.jpg" width=95 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0023.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0101.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0067.jpg" width=70 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0135.jpg" width=114 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.080</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0170.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0018.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0037.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0107.jpg" width=129 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0023.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0129.jpg" width=110 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0041.jpg" width=113 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0025.jpg" width=57 height=76><br><small>Coast</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.180</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0039.jpg" width=126 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0098.jpg" width=126 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0158.jpg" width=121 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0020.jpg" width=105 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0109.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0128.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0164.jpg" width=103 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0103.jpg" width=104 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.110</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0022.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0184.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0025.jpg" width=118 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0114.jpg" width=49 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0085.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0044.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0076.jpg" width=100 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0105.jpg" width=113 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.170</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0019.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0110.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0079.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0116.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0071.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0182.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0117.jpg" width=113 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0098.jpg" width=113 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.080</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0199.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0028.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0126.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0004.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0083.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0026.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0015.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0001.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.080</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0186.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0118.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0056.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0111.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0107.jpg" width=101 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0107.jpg" width=75 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0021.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.300</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0228.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0123.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0082.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0145.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0001.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0029.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0105.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0034.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.490</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0066.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0189.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0063.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0011.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0067.jpg" width=70 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0018.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0002.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0030.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.380</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0366.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0214.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0097.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0014.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0089.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0156.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0039.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0050.jpg" width=75 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.220</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0261.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0127.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0094.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0063.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0134.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0098.jpg" width=91 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0114.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0129.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.130</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0002.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0034.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0077.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0032.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0141.jpg" width=113 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0036.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0108.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.020</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0228.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0162.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0091.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0059.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0180.jpg" width=78 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0106.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0043.jpg" width=75 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0062.jpg" width=75 height=75><br><small>Street</small></td>
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


