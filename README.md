# MoSe2-DefectAnalysis
Create Feature using following commands

For training <br><br>
`cd construct_tensor` <br>
`./c_feature ../train.xyz 121000 1` <br>
mv dcnn_feature.txt ../2H_1T.txt
`cd ..` <br>

<br>For testing<br><br>
`cd construct_tensor` <br>
`./c_feature ../test.xyz 25000 1` <br>
mv dcnn_feature.txt ../test_2H_1T.txt
`cd ..` <br>
<br>

Follow the notebooks for further analysis
