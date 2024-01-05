# SEMScene
PyTorch implementation for SEMScene.     
SEMScene is built on top of the [LGSGM](https://github.com/m2man/LGSGM)
# Data 
Except for the uploaded basic data in this repository, the model still need basic data including adjacency matrix based on the connection of predicates and triplets of sentence extracted through leveraging the [SceneGraphParser](https://github.com/vacancy/SceneGraphParser), which can be obtained here: [flickr30k](https://drive.google.com/drive/folders/1W02ub0UtV6wE41v59qa9pfxArKGIMtvv?usp=drive_link) and [mscoco](https://drive.google.com/drive/folders/1c0NpqlR0PypWO2JT3FnRrvKDfZa5M0Wm?usp=drive_link). Please download and place them in the **data_flickr30k/data** and **data_mscoco/data** folders, respectively. Or you can extract them by editing the paths of files in ```extract_pred_adj.py``` and ```sng_parser_process.ipynb```, then run them.
