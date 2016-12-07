<center>
<h1>Project 3 results visualization</h1>
<img src="confusion_matrix.png">

<br>
Accuracy (mean of diagonal of confusion matrix) is 0.532
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
<td>0.390</td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0055.jpg" width=112 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Kitchen_image_0181.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0167.jpg" width=57 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Kitchen_image_0180.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0006.jpg" width=113 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0120.jpg" width=116 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0008.jpg" width=100 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Kitchen_image_0120.jpg" width=113 height=75><br><small>Bedroom</small></td>
</tr>
<tr>
<td>Store</td>
<td>0.300</td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0064.jpg" width=57 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Store_image_0145.jpg" width=101 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0013.jpg" width=131 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Store_image_0045.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0084.jpg" width=110 height=75><br><small>LivingRoom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0146.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0127.jpg" width=118 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Store_image_0046.jpg" width=57 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Bedroom</td>
<td>0.210</td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0002.jpg" width=97 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Bedroom_image_0105.jpg" width=110 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0035.jpg" width=115 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Bedroom_image_0170.jpg" width=93 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0104.jpg" width=115 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0062.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0084.jpg" width=107 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Bedroom_image_0118.jpg" width=114 height=75><br><small>Kitchen</small></td>
</tr>
<tr>
<td>LivingRoom</td>
<td>0.220</td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0017.jpg" width=100 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/LivingRoom_image_0091.jpg" width=110 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0131.jpg" width=94 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/LivingRoom_image_0057.jpg" width=100 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0107.jpg" width=50 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0132.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0147.jpg" width=115 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/LivingRoom_image_0046.jpg" width=100 height=75><br><small>Street</small></td>
</tr>
<tr>
<td>Office</td>
<td>0.840</td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0090.jpg" width=107 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Office_image_0035.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0067.jpg" width=117 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Office_image_0059.jpg" width=116 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0116.jpg" width=100 height=75><br><small>Kitchen</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0120.jpg" width=111 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0169.jpg" width=92 height=75><br><small>Street</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Office_image_0148.jpg" width=100 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Industrial</td>
<td>0.190</td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0159.jpg" width=112 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Industrial_image_0268.jpg" width=100 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0126.jpg" width=134 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Industrial_image_0079.jpg" width=101 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0128.jpg" width=115 height=75><br><small>Bedroom</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Kitchen_image_0168.jpg" width=112 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0062.jpg" width=63 height=75><br><small>Forest</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Industrial_image_0046.jpg" width=57 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>Suburb</td>
<td>0.730</td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0231.jpg" width=113 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Suburb_image_0141.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0084.jpg" width=113 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Suburb_image_0101.jpg" width=113 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Street_image_0021.jpg" width=75 height=75><br><small>Street</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0005.jpg" width=114 height=75><br><small>Industrial</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0138.jpg" width=113 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Suburb_image_0103.jpg" width=113 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>InsideCity</td>
<td>0.450</td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0293.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/InsideCity_image_0174.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0095.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/InsideCity_image_0084.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0120.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Store_image_0111.jpg" width=100 height=75><br><small>Store</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0002.jpg" width=75 height=75><br><small>Office</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/InsideCity_image_0021.jpg" width=75 height=75><br><small>TallBuilding</small></td>
</tr>
<tr>
<td>TallBuilding</td>
<td>0.680</td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0210.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/TallBuilding_image_0343.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0057.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/TallBuilding_image_0002.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Suburb_image_0001.jpg" width=113 height=75><br><small>Suburb</small></td>
<td bgcolor=LightCoral><img src="thumbnails/LivingRoom_image_0033.jpg" width=100 height=75><br><small>LivingRoom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0092.jpg" width=75 height=75><br><small>Kitchen</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/TallBuilding_image_0123.jpg" width=75 height=75><br><small>InsideCity</small></td>
</tr>
<tr>
<td>Street</td>
<td>0.550</td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0252.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Street_image_0114.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0061.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Street_image_0087.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Office_image_0169.jpg" width=92 height=75><br><small>Office</small></td>
<td bgcolor=LightCoral><img src="thumbnails/TallBuilding_image_0094.jpg" width=75 height=75><br><small>TallBuilding</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0057.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Street_image_0138.jpg" width=75 height=75><br><small>Suburb</small></td>
</tr>
<tr>
<td>Highway</td>
<td>0.700</td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0019.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Highway_image_0145.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0105.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Highway_image_0125.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0115.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0013.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0141.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Highway_image_0032.jpg" width=75 height=75><br><small>Forest</small></td>
</tr>
<tr>
<td>OpenCountry</td>
<td>0.380</td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0271.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/OpenCountry_image_0241.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0107.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/OpenCountry_image_0006.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0133.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Bedroom_image_0156.jpg" width=99 height=75><br><small>Bedroom</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0008.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/OpenCountry_image_0030.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Coast</td>
<td>0.810</td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0108.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Coast_image_0143.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0124.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Coast_image_0060.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Highway_image_0142.jpg" width=75 height=75><br><small>Highway</small></td>
<td bgcolor=LightCoral><img src="thumbnails/OpenCountry_image_0108.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0101.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Coast_image_0096.jpg" width=75 height=75><br><small>Highway</small></td>
</tr>
<tr>
<td>Mountain</td>
<td>0.600</td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0285.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Mountain_image_0292.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0048.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Mountain_image_0068.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Industrial_image_0049.jpg" width=100 height=75><br><small>Industrial</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Coast_image_0031.jpg" width=75 height=75><br><small>Coast</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0032.jpg" width=75 height=75><br><small>Suburb</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Mountain_image_0003.jpg" width=75 height=75><br><small>Coast</small></td>
</tr>
<tr>
<td>Forest</td>
<td>0.930</td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0061.jpg" width=75 height=75></td>
<td bgcolor=LightBlue><img src="thumbnails/Forest_image_0254.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0029.jpg" width=75 height=75></td>
<td bgcolor=LightGreen><img src="thumbnails/Forest_image_0010.jpg" width=75 height=75></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0109.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=LightCoral><img src="thumbnails/Mountain_image_0013.jpg" width=75 height=75><br><small>Mountain</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0070.jpg" width=75 height=75><br><small>OpenCountry</small></td>
<td bgcolor=#FFBB55><img src="thumbnails/Forest_image_0118.jpg" width=75 height=75><br><small>Mountain</small></td>
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


