<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.586
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
<td>0.490</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0126.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0101.jpg" width=95 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0123.jpg" width=114 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0127.jpg" width=114 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0024.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0053.jpg" width=110 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0073.jpg" width=107 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0003.jpg" width=100 height=75><br><small>InsideCity</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.340</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0007.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0172.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0081.jpg" width=131 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0079.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0118.jpg" width=114 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0190.jpg" width=57 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0135.jpg" width=114 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0118.jpg" width=77 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.230</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0164.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0174.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0035.jpg" width=115 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0088.jpg" width=57 height=76></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0024.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0046.jpg" width=57 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0119.jpg" width=113 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0104.jpg" width=95 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.280</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0154.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0052.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0096.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0070.jpg" width=101 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0104.jpg" width=115 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0134.jpg" width=57 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0025.jpg" width=57 height=76><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0008.jpg" width=100 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.970</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0035.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0021.jpg" width=105 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0083.jpg" width=108 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0037.jpg" width=108 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0138.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0158.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0092.jpg" width=116 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0120.jpg" width=116 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.370</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0292.jpg" width=101 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0306.jpg" width=50 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0117.jpg" width=102 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0006.jpg" width=114 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0013.jpg" width=100 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0156.jpg" width=99 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0110.jpg" width=74 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0049.jpg" width=100 height=75><br><small>Forest</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.900</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0010.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0073.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0108.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0137.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0076.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0135.jpg" width=114 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0020.jpg" width=113 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0103.jpg" width=113 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.580</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0232.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0278.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0055.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0025.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0088.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0048.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0004.jpg" width=75 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.720</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0148.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0315.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0017.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0083.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0048.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0116.jpg" width=71 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0046.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0105.jpg" width=75 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.530</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0043.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0003.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0111.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0137.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0038.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0100.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0137.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0118.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0248.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0074.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0153.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0081.jpg" width=105 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0056.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0034.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0140.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.140</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0075.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0236.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0083.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0107.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0047.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0105.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0057.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0112.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.820</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0111.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0336.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0129.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0083.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0053.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0149.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0088.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0014.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.670</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0067.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0044.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0040.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0104.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0003.jpg" width=104 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0040.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0103.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0098.jpg" width=75 height=75><br><small>Forest</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.950</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0250.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0108.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0095.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0106.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0044.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0084.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0036.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0124.jpg" width=75 height=75><br><small>Mountain</small></td>
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


