<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.439
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
<td>0.200</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0193.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0162.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0173.jpg" width=98 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0024.jpg" width=57 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0174.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0039.jpg" width=101 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0002.jpg" width=100 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0159.jpg" width=60 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.200</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0255.jpg" width=102 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0103.jpg" width=106 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0034.jpg" width=106 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0016.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0058.jpg" width=140 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0046.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0013.jpg" width=131 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0121.jpg" width=57 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.480</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0145.jpg" width=102 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0002.jpg" width=97 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0135.jpg" width=114 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0160.jpg" width=111 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0084.jpg" width=112 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0078.jpg" width=113 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0013.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0018.jpg" width=101 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.030</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0271.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0125.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0042.jpg" width=105 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0015.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0132.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0119.jpg" width=108 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0084.jpg" width=110 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0107.jpg" width=129 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.850</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0190.jpg" width=110 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0202.jpg" width=107 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0034.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0183.jpg" width=109 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0135.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0081.jpg" width=107 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0144.jpg" width=115 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0084.jpg" width=107 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.280</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0120.jpg" width=98 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0284.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0055.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0003.jpg" width=50 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0111.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0072.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0138.jpg" width=100 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0142.jpg" width=54 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.100</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0158.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0163.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0160.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0012.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0073.jpg" width=107 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0137.jpg" width=120 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0034.jpg" width=113 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0103.jpg" width=113 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.480</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0009.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0226.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0065.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0130.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0010.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0090.jpg" width=112 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0069.jpg" width=75 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0057.jpg" width=75 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.660</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0124.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0315.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0031.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0078.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0114.jpg" width=49 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0071.jpg" width=112 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0077.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0013.jpg" width=75 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.280</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0195.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0206.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0087.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0048.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0070.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0007.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0136.jpg" width=75 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0111.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.640</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0038.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0242.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0080.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0040.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0032.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0037.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0014.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0162.jpg" width=75 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.070</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0229.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0156.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0006.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0050.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0034.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0114.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0083.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0018.jpg" width=75 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.790</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0326.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0267.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0040.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0063.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0036.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0019.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0041.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0088.jpg" width=75 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.570</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0349.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0131.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0045.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0097.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0046.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0020.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0086.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0006.jpg" width=75 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.950</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0164.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0279.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0062.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0024.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0070.jpg" width=101 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0093.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0118.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0036.jpg" width=75 height=75><br><small>Mountain</small></td>
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


