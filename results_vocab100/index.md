<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.582
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
<td>0.410</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0082.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0106.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0006.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0156.jpg" width=91 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0088.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0131.jpg" width=114 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0125.jpg" width=114 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0183.jpg" width=100 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.430</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0261.jpg" width=112 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0097.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0080.jpg" width=132 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0010.jpg" width=104 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0075.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0061.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0076.jpg" width=54 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0048.jpg" width=100 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.280</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0085.jpg" width=92 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0132.jpg" width=112 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0128.jpg" width=115 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0077.jpg" width=90 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0046.jpg" width=57 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0090.jpg" width=113 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0043.jpg" width=101 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0162.jpg" width=113 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.200</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0121.jpg" width=110 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0289.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0042.jpg" width=105 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0105.jpg" width=114 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0132.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0026.jpg" width=95 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0062.jpg" width=100 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0107.jpg" width=129 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.910</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0085.jpg" width=85 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0054.jpg" width=109 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0119.jpg" width=108 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0174.jpg" width=117 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0066.jpg" width=101 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0126.jpg" width=57 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0127.jpg" width=119 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0083.jpg" width=108 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.290</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0136.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0078.jpg" width=105 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0135.jpg" width=77 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0107.jpg" width=50 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0019.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0177.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0115.jpg" width=94 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0123.jpg" width=120 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.920</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0095.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0091.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0081.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0031.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0114.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0036.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0103.jpg" width=113 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0053.jpg" width=113 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.510</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0258.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0227.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0037.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0100.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0016.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0066.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0131.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0096.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.670</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0293.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0014.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0111.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0129.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0072.jpg" width=107 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0164.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0006.jpg" width=75 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0099.jpg" width=75 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.610</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0202.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0117.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0143.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0133.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0126.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0116.jpg" width=51 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0055.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0066.jpg" width=75 height=75><br><small>InsideCity</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.730</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0187.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0072.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0042.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0070.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0115.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0053.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0015.jpg" width=75 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0144.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.220</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0053.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0232.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0032.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0103.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0103.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0101.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0030.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0038.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.830</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0307.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0091.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0099.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0055.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0150.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0042.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0088.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0036.jpg" width=75 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0181.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0267.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0119.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0077.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0023.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0029.jpg" width=63 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0061.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0030.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.920</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0190.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0092.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0079.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0038.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0025.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0046.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0118.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0109.jpg" width=75 height=75><br><small>Mountain</small></td>
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


