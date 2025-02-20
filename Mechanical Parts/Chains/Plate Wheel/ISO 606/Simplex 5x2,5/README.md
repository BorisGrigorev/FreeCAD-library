# Chain Plate Wheels ISO606 simplex 5 x 2,5 from z 8 to z 50

This folder contains the 3D models of the plate wheels for ISO 606 chains simplex 5 x 2,5 with number of teeth ranging from z=8 to z=50.

![Image](screenshot.png "Plate Wheel Simplex")

The model is parametric and the values are contained in the spreadsheet `Data`.

The parameters refer to the plate wheel dimensions as in the drawing below:

![Drawing](drawing.png "Drawing")

### Table of dimensions in millimeters:

P (Pitch)|Wc (Chain width)|Dr (Roller diameter)|Tr (Tooth radius)|Rw (Radius width)|Wt (Tooth width)|z (Number of teeth)|De (External Diameter)|Dp (Pitch diameter)|D (Hole diameter)|H (Total height)
---|---|---|---|---|---|---|---|---|---|---
5|2,5|3,2|5|0,6|2,3|8|15,2|13,06|4|2,3
5|2,5|3,2|5|0,6|2,3|9|16,8|14,62|4|2,3
5|2,5|3,2|5|0,6|2,3|10|18,3|16,18|4|2,3
5|2,5|3,2|5|0,6|2,3|11|19,9|17,75|5|2,3
5|2,5|3,2|5|0,6|2,3|12|21,5|19,32|5|2,3
5|2,5|3,2|5|0,6|2,3|13|23|20,89|5|2,3
5|2,5|3,2|5|0,6|2,3|14|24,6|22,47|5|2,3
5|2,5|3,2|5|0,6|2,3|15|26,2|24,04|5|2,3
5|2,5|3,2|5|0,6|2,3|16|27,8|25,63|6|2,3
5|2,5|3,2|5|0,6|2,3|17|29,4|27,2|6|2,3
5|2,5|3,2|5|0,6|2,3|18|30,9|28,79|6|2,3
5|2,5|3,2|5|0,6|2,3|19|32,5|30,38|6|2,3
5|2,5|3,2|5|0,6|2,3|20|34,1|31,96|6|2,3
5|2,5|3,2|5|0,6|2,3|21|35,7|33,54|8|2,3
5|2,5|3,2|5|0,6|2,3|22|37,3|35,13|8|2,3
5|2,5|3,2|5|0,6|2,3|23|38,9|36,72|8|2,3
5|2,5|3,2|5|0,6|2,3|24|40,5|38,3|8|2,3
5|2,5|3,2|5|0,6|2,3|25|42|39,89|8|2,3
5|2,5|3,2|5|0,6|2,3|26|43,6|41,48|8|2,3
5|2,5|3,2|5|0,6|2,3|27|45,2|43,07|8|2,3
5|2,5|3,2|5|0,6|2,3|28|46,8|44,65|8|2,3
5|2,5|3,2|5|0,6|2,3|29|48,4|46,25|8|2,3
5|2,5|3,2|5|0,6|2,3|30|50|47,83|8|2,3
5|2,5|3,2|5|0,6|2,3|31|51,5|49,42|8|2,3
5|2,5|3,2|5|0,6|2,3|32|53,2|51,01|8|2,3
5|2,5|3,2|5|0,6|2,3|33|54,8|52,6|8|2,3
5|2,5|3,2|5|0,6|2,3|34|56,3|54,19|8|2,3
5|2,5|3,2|5|0,6|2,3|35|57,9|55,78|8|2,3
5|2,5|3,2|5|0,6|2,3|36|59,5|57,37|8|2,3
5|2,5|3,2|5|0,6|2,3|37|61,1|58,96|8|2,3
5|2,5|3,2|5|0,6|2,3|38|62,7|60,54|8|2,3
5|2,5|3,2|5|0,6|2,3|39|64,3|62,13|8|2,3
5|2,5|3,2|5|0,6|2,3|40|65,9|63,73|8|2,3
5|2,5|3,2|5|0,6|2,3|41|67,5|65,31|8|2,3
5|2,5|3,2|5|0,6|2,3|42|69,1|66,91|8|2,3
5|2,5|3,2|5|0,6|2,3|43|70,6|68,49|8|2,3
5|2,5|3,2|5|0,6|2,3|44|72,2|70,09|8|2,3
5|2,5|3,2|5|0,6|2,3|45|73,8|71,68|8|2,3
5|2,5|3,2|5|0,6|2,3|46|75,4|73,27|8|2,3
5|2,5|3,2|5|0,6|2,3|47|77|74,86|8|2,3
5|2,5|3,2|5|0,6|2,3|48|78,6|76,45|8|2,3
5|2,5|3,2|5|0,6|2,3|49|80,2|78,03|8|2,3
5|2,5|3,2|5|0,6|2,3|50|81,8|79,63|8|2,3

The 3D model configuration of each plate wheel can be dynamically retrieved using a preset `Configuration table`.
The file name of the 3D model containing the `Configuration table` is **`Plate Wheel simplex 5x2,5.FCStd`**.

To obtain the 3D model of the desidered plate wheel, click the spreadsheet `Data` in the Tree View and then select the `Teeth Number` in the property editor. If nothing changes try to `Refresh` the model.

See the following image for details

![Drawing](configuration.png "Configuration")

### Notes for developers
If you add a row in the `Configuration table` of the `Data` spreadsheet, then add that row in the above table of this `README.md` file, without the first cell.
