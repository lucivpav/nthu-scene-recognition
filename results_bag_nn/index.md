<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.476
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
<td>0.330</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0162.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0030.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0110.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0006.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0118.jpg" width=77 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0083.jpg" width=108 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0134.jpg" width=113 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0190.jpg" width=57 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.410</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0199.jpg" width=111 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0051.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0149.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0008.jpg" width=89 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0107.jpg" width=50 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0042.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0080.jpg" width=132 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0088.jpg" width=100 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.180</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0055.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0023.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0121.jpg" width=102 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0124.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0065.jpg" width=75 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0117.jpg" width=114 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0034.jpg" width=101 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0052.jpg" width=103 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.440</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0144.jpg" width=114 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0184.jpg" width=114 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0090.jpg" width=114 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0140.jpg" width=117 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0075.jpg" width=107 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0115.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0119.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0100.jpg" width=111 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.790</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0078.jpg" width=116 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0098.jpg" width=126 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0180.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0022.jpg" width=102 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0029.jpg" width=57 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0013.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0012.jpg" width=87 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0138.jpg" width=96 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.270</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0128.jpg" width=130 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0195.jpg" width=50 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0029.jpg" width=63 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0061.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0111.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0099.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0054.jpg" width=100 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0005.jpg" width=114 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.880</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0142.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0136.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0034.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0166.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0108.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0033.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0152.jpg" width=113 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0103.jpg" width=113 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.230</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0120.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0018.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0118.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0068.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0008.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0091.jpg" width=89 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0041.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0066.jpg" width=75 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.290</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0251.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0120.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0070.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0126.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0077.jpg" width=90 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0084.jpg" width=93 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0027.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0131.jpg" width=75 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.450</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0096.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0164.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0008.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0051.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0135.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0064.jpg" width=107 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0070.jpg" width=75 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0055.jpg" width=75 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.700</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0170.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0199.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0137.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0068.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0073.jpg" width=107 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0014.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0026.jpg" width=75 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0135.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.410</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0398.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0217.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0086.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0022.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0078.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0027.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0046.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0118.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.390</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0065.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0189.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0090.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0067.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0050.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0073.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0036.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0118.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.500</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0250.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0056.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0042.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0055.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0058.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0106.jpg" width=85 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0100.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0123.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.870</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0123.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0277.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0134.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0025.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0025.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0041.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0119.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0078.jpg" width=75 height=75><br><small>OpenCountry</small></td>
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


