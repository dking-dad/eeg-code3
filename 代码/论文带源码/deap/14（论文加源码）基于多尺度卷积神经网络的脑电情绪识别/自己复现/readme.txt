python == 3.6 and above
torch == 1.2.0 and above
numpy == 1.16.4
h5py == 2.9.0
pathlib 

运行：
请将数据保存到文件夹中，并在"PrepareData.py"中设置数据的路径。

python PrepareData.py

运行上述脚本后，将在脚本的同一位置生成名为"data_split.hdf"的文件。请在运行之前在"Train.py"中设置data_split.hdf的位置。

python Train.py

