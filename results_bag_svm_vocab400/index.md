<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.621
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
<td>0.500</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0014.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0139.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0053.jpg" width=89 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0091.jpg" width=94 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0071.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0024.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0012.jpg" width=100 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0150.jpg" width=100 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.410</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0232.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0172.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0046.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0122.jpg" width=74 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0171.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0063.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0074.jpg" width=54 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0026.jpg" width=103 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.370</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0194.jpg" width=114 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0127.jpg" width=115 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0090.jpg" width=108 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0035.jpg" width=115 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0094.jpg" width=64 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0046.jpg" width=57 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0053.jpg" width=110 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0040.jpg" width=113 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.320</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0157.jpg" width=98 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0137.jpg" width=111 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0126.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0023.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0110.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0168.jpg" width=113 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0074.jpg" width=100 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0046.jpg" width=100 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.880</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0104.jpg" width=102 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0031.jpg" width=96 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0048.jpg" width=118 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0055.jpg" width=108 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0148.jpg" width=102 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0040.jpg" width=135 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0138.jpg" width=96 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0120.jpg" width=116 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.300</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0136.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0287.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0016.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0127.jpg" width=96 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0180.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0177.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0046.jpg" width=57 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0074.jpg" width=100 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.960</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0135.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0029.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0166.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0003.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0125.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0115.jpg" width=94 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0013.jpg" width=113 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0020.jpg" width=113 height=75><br><small>Office</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.530</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0236.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0180.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0132.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0053.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0032.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0043.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0128.jpg" width=75 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0013.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0014.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0074.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0025.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0032.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0140.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0114.jpg" width=49 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0085.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0024.jpg" width=75 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.560</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0033.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0081.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0008.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0137.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0072.jpg" width=107 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0062.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0049.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0098.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0019.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0135.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0144.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0148.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0115.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0006.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0035.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.280</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0207.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0070.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0108.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0077.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0112.jpg" width=133 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0047.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0005.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0079.jpg" width=75 height=75><br><small>Forest</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.830</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0284.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0032.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0121.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0040.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0006.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0019.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0070.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0036.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.850</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0232.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0057.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0006.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0034.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0030.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0124.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0085.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0009.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.930</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0172.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0290.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0053.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0073.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0032.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0070.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0017.jpg" width=75 height=75><br><small>Mountain</small></td>
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


