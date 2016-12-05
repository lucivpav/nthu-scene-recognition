<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.596
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
<td>0.470</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0164.jpg" width=50 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0074.jpg" width=107 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0053.jpg" width=89 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0184.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0085.jpg" width=81 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0079.jpg" width=103 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0141.jpg" width=51 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0149.jpg" width=100 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.390</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0054.jpg" width=76 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0049.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0023.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0053.jpg" width=57 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0124.jpg" width=112 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0035.jpg" width=77 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0085.jpg" width=81 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0056.jpg" width=100 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.270</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0188.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0083.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0157.jpg" width=90 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0104.jpg" width=95 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0123.jpg" width=98 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0013.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0087.jpg" width=50 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0026.jpg" width=95 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.240</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0233.jpg" width=101 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0280.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0070.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0105.jpg" width=114 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0022.jpg" width=57 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0098.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0141.jpg" width=113 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0058.jpg" width=101 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.920</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0069.jpg" width=98 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0189.jpg" width=94 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0140.jpg" width=103 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0117.jpg" width=98 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0107.jpg" width=101 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0042.jpg" width=57 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0110.jpg" width=107 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0174.jpg" width=117 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.330</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0260.jpg" width=105 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0048.jpg" width=41 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0106.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0028.jpg" width=114 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0058.jpg" width=101 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0078.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0068.jpg" width=94 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0118.jpg" width=116 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.940</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0058.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0192.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0070.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0034.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0116.jpg" width=126 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0061.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0111.jpg" width=113 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0009.jpg" width=113 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.550</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0221.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0047.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0043.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0068.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0151.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0015.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0037.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0025.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.730</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0227.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0280.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0077.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0015.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0015.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0076.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0084.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0064.jpg" width=75 height=75><br><small>Store</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.600</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0139.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0257.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0010.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0144.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0138.jpg" width=125 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0146.jpg" width=57 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0022.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0062.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.750</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0021.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0193.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0155.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0006.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0061.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0057.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0136.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0142.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.210</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0124.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0141.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0120.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0026.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0005.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0054.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0057.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0024.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.810</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0231.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0117.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0041.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0068.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0119.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0142.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0014.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0114.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0102.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0169.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0031.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0093.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0021.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0017.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0101.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0032.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.930</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0327.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0318.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0134.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0131.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0100.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0079.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0110.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0036.jpg" width=75 height=75><br><small>Suburb</small></td>
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


