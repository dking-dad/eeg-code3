请通过以下方式转到工作目录：

$ cd ./代码

请通过以下方式创建一个 anaconda 虚拟环境：

$ conda create --name TSception

通过以下方式激活虚拟环境：

$ conda activate TSception

通过以下方式安装要求：

$ pip3 install -r requirment.txt

运行：
下载 DEAP 数据集。请将"data_preprocessed_python"文件夹放在脚本的同一位置 （./code/）。

要运行唤醒维度的代码，请在终端中键入以下命令：

$ python3 main-DEAP.py --data-path './data_preprocessed_python/' --label-type 'A'

要运行valence实验，请将 --label -type设置为"V"。结果将保存到与脚本位于同一位置的"result.txt"中。