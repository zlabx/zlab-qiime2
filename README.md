# zlab-qiime2
one-click qiime2 analysis 

#将本文件存为zlab.sh，可在home目录下创建soft/qiime2这个目录，然后
cd在所在目录如 ~/soft/qiime2

chmod +x zlab.sh

修改环境变量让zlab.sh在任何位置均可以使用

vi ~/.bashrc

在最下面添加这行

export PATH=$PATH:$HOME/soft/qiime2

更新缓存生效

source ~/.bashrc

在端口输入

zlab.sh -h

查看使用帮助。
完整的执行输入格式为

zlab.sh 
-i /mnt/d/16S/split/pe-33-manifest-2 
-o /mnt/d/16S/amp_results 
-m /mnt/d/16S/split/sample-metadata.tsv 
-n 4 
-d deblur 
-a gg_v4


#如果使用了本脚本，请引用文章

Zhou, Jian, et al. "Dietary lysozyme alters sow’s gut microbiota, serum immunity and milk metabolite profile." Frontiers in microbiology 10 (2019): 177.
