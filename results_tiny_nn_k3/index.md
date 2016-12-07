<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.145
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
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0065.jpg" width=61 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0112.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0018.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0128.jpg" width=115 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0088.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0144.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0182.jpg" width=100 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0156.jpg" width=91 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.010</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0103.jpg" width=106 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0064.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0015.jpg" width=100 height=75></td>
<td bgcolor=LightGreen></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0074.jpg" width=109 height=75><br><small>Office</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0088.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0057.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0008.jpg" width=89 height=75><br><small>Forest</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.090</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0032.jpg" width=101 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0151.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0054.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0121.jpg" width=102 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0081.jpg" width=101 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0076.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0157.jpg" width=90 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0037.jpg" width=95 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.090</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0076.jpg" width=101 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0044.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0023.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0027.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0001.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0100.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0131.jpg" width=94 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0094.jpg" width=64 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.160</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0049.jpg" width=103 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0149.jpg" width=108 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0023.jpg" width=90 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0075.jpg" width=103 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0012.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0031.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0001.jpg" width=101 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0103.jpg" width=104 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.100</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0265.jpg" width=103 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0004.jpg" width=117 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0027.jpg" width=92 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0125.jpg" width=46 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0044.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0115.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0047.jpg" width=100 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0115.jpg" width=94 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.140</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0016.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0207.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0119.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0023.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0039.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0024.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0053.jpg" width=113 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0065.jpg" width=113 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.070</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0155.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0115.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0004.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0059.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0082.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0135.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0039.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0131.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.080</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0320.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0251.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0115.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0117.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0066.jpg" width=101 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0013.jpg" width=131 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0036.jpg" width=75 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0122.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.290</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0183.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0160.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0007.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0048.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0029.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0070.jpg" width=101 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0056.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0018.jpg" width=75 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.390</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0152.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0254.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0123.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0133.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0013.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0107.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0041.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0005.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.340</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0390.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0168.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0034.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0073.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0141.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0131.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0079.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0098.jpg" width=75 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.220</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0015.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0120.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0126.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0057.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0100.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0057.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0115.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0093.jpg" width=75 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.120</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0263.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0099.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0017.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0085.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0016.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0091.jpg" width=57 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0072.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0100.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.030</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0205.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0184.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0091.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0059.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0134.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0004.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0062.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0035.jpg" width=75 height=75><br><small>Kitchen</small></td>
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


