<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.619
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
<td>0.540</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0025.jpg" width=57 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0189.jpg" width=112 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0071.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0124.jpg" width=57 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0166.jpg" width=101 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0168.jpg" width=113 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0150.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0003.jpg" width=100 height=75><br><small>InsideCity</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.500</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0005.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0177.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0048.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0020.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0085.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0124.jpg" width=112 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0022.jpg" width=88 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0079.jpg" width=100 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.420</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0199.jpg" width=107 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0146.jpg" width=105 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0033.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0097.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0105.jpg" width=114 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0022.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0056.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0003.jpg" width=104 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.310</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0103.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0226.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0145.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0049.jpg" width=106 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0016.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0038.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0064.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0063.jpg" width=115 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.890</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0028.jpg" width=102 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0136.jpg" width=111 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0067.jpg" width=117 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0092.jpg" width=116 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0115.jpg" width=89 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0026.jpg" width=103 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0062.jpg" width=110 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0117.jpg" width=98 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.390</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0210.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0308.jpg" width=90 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0079.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0040.jpg" width=135 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0083.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0082.jpg" width=135 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0074.jpg" width=100 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0068.jpg" width=94 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.950</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0006.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0209.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0118.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0123.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0115.jpg" width=94 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0081.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0053.jpg" width=113 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0008.jpg" width=113 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.480</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0232.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0242.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0048.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0074.jpg" width=54 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0014.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0131.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0019.jpg" width=75 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.710</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0074.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0244.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0042.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0001.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0133.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0076.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0105.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0096.jpg" width=75 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.490</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0205.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0167.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0134.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0126.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0105.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0008.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0141.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0047.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0239.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0120.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0139.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0095.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0118.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0148.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0035.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0029.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.280</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0283.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0385.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0031.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0107.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0033.jpg" width=95 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0090.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0007.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0006.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.840</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0290.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0242.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0060.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0016.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0134.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0068.jpg" width=94 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0024.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0009.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.750</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0218.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0124.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0096.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0083.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0040.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0014.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0069.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0061.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.940</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0116.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0298.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0009.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0024.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0029.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0030.jpg" width=113 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0109.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0110.jpg" width=75 height=75><br><small>Mountain</small></td>
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


