# vits-singing-voice-conversion
vits singing voice conversion based on ppg &amp; hubert

VI-SVC model is just VITS without MAS and DurationPredictor. Big data [more and more wave] make things to be interesing!

# data-sets
KiSing      http://shijt.site/index.php/2021/05/16/kising-the-first-open-source-mandarin-singing-voice-synthesis-corpus/

PopCS 		  https://github.com/MoonInTheRiver/DiffSinger/blob/master/resources/apply_form.md

opencpop 	  https://wenet.org.cn/opencpop/download/

OpenSinger 	https://github.com/Multi-Singer/Multi-Singer.github.io

M4Singer	  https://github.com/M4Singer/M4Singer/blob/master/apply_form.md


CSD 		    https://zenodo.org/record/4785016#.YxqrTbaOMU4

KSS		      https://www.kaggle.com/datasets/bryanpark/korean-single-speaker-speech-dataset

JVS MuSic	  https://sites.google.com/site/shinnosuketakamichi/research-topics/jvs_music

PJS		      https://sites.google.com/site/shinnosuketakamichi/research-topics/pjs_corpus

JUST Song	  https://sites.google.com/site/shinnosuketakamichi/publication/jsut-song


MUSDB18		  https://sigsep.github.io/datasets/musdb.html#musdb18-compressed-stems

DSD100 		  https://sigsep.github.io/datasets/dsd100.html


Aishell-3 	http://www.aishelltech.com/aishell_3

VCTK 		    https://datashare.ed.ac.uk/handle/10283/2651



# framework

![base_train](/assets/SVC1.png)

![base_infer](/assets/SVC2.png)

![pro_train](/assets/SVC1_pro.png)

![pro_infer](/assets/SVC2_pro.png)

![unix_infer](/assets/SVC2_unix.png)

# demo
https://www.bilibili.com/video/BV1bY4y1M7NX

https://www.bilibili.com/video/BV1wB4y1n7WE

# 鹿鸣
【VI-SVC】鹿鸣复刻与歌声生成，音色对比

https://www.bilibili.com/video/BV1ue4y187Ci

【VI-SVC歌声生成】原神一梦千宵，米哈游鹿鸣复刻

https://www.bilibili.com/video/BV1He411u7Pa

【VI-SVC歌声转换】能唱能跳的鹿鸣你见过吗？

https://www.bilibili.com/video/BV1PG41137KB

[虚拟歌姬]数字人鹿鸣音色复刻，跨语言测试

https://www.bilibili.com/video/BV1n14y1v7oQ

[虚拟歌姬]数字人鹿鸣音色复刻《如愿》

https://www.bilibili.com/video/BV1ue4y187Ci

# train
[VI-SVC](/svc/README.md)

# how to clone your voice
use base model and your voice data to fine tune, just voice data without lables.(**无需标注**)

