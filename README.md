# Indoor-Location-Navigation-Silver-Solution

Indoor Location &amp; Navigation 2% Silver Solution

Address of the competition：https://www.kaggle.com/dingshiqi/competitions?tab=completed

1 Download the data to the input folder

2 floor forecast code

   part1 data preprocessing
   run code/wifi-features.ipynb
   Run code/create-unified-wifi-features-example.ipynb

   part2 Deep Learning Model
   run code/floor-model-blstm.ipynb

3 Coordinate prediction code

   part1 data preprocessing
   run code/wifi-label-encode.ipynb
   run code/data_abstract_sensor.ipynb
   run code/data_abstract_wifi.ipynb
   run code/gen_accl.ipynb

   part2 Deep Learning Model
   Run code/lstm-wifi-encode-wifi.ipynb to predict using only wifi data
   Run code/lstm-wifi-encode-wifi-sensor.ipynb to predict using wifi+sensor data

4 Result fusion
   Run code/combine_v1.ipynb to model linear fusion

5 Post-processing
   run code/post_process.ipynb

6 Rule prediction code
   run code/rules_infer.ipynb

7 Results fusion
   Run the code/combine_v2.ipynb model linear fusion to get the final final.csv prediction file
