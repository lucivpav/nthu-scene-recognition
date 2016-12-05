<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.550
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
<td>0.370</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0034.jpg" width=57 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0139.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0116.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0057.jpg" width=105 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0166.jpg" width=101 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0138.jpg" width=96 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0134.jpg" width=113 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0023.jpg" width=57 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.220</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0223.jpg" width=94 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0133.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0016.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0021.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0073.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0017.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0063.jpg" width=57 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0065.jpg" width=100 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.430</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0169.jpg" width=115 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0183.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0054.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0020.jpg" width=101 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0059.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0131.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0067.jpg" width=70 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0166.jpg" width=101 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.310</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0162.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0172.jpg" width=114 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0098.jpg" width=114 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0129.jpg" width=55 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0140.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0095.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0100.jpg" width=111 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0124.jpg" width=112 height=75><br><small>Industrial</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.840</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0033.jpg" width=108 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0194.jpg" width=126 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0062.jpg" width=110 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0148.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0021.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0126.jpg" width=57 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0084.jpg" width=107 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0176.jpg" width=109 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.290</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0128.jpg" width=130 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0286.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0148.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0021.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0059.jpg" width=110 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0168.jpg" width=113 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0072.jpg" width=122 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0135.jpg" width=77 height=75><br><small>InsideCity</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.690</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0131.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0158.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0128.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0123.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0102.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0081.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0167.jpg" width=113 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0003.jpg" width=113 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.560</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0262.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0274.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0001.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0104.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0006.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0085.jpg" width=81 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0056.jpg" width=75 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0092.jpg" width=75 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.670</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0076.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0336.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0117.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0032.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0041.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0130.jpg" width=109 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0113.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0095.jpg" width=75 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.460</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0276.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0267.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0042.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0089.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0088.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=LightCoral><img src="thumbnails/InsideCity_image_0029.jpg" width=75 height=75><br><small>InsideCity</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0025.jpg" width=75 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0101.jpg" width=75 height=75><br><small>LivingRoom</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.640</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0047.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0154.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0051.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0060.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0032.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0104.jpg" width=112 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0147.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0029.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.240</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0398.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0364.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0104.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0061.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0122.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0081.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0100.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0113.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.800</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0228.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0203.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0130.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0084.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0118.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0136.jpg" width=70 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0110.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0088.jpg" width=75 height=75><br><small>Mountain</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.790</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0178.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0139.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0003.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0022.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Forest_image_0109.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0099.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0100.jpg" width=75 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0061.jpg" width=75 height=75><br><small>OpenCountry</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.940</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0103.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0071.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0073.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0022.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0070.jpg" width=101 height=75><br><small>Store</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0041.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0110.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0002.jpg" width=75 height=75><br><small>Mountain</small></td>
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


