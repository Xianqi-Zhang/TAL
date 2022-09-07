# M3

This project is a PyTorch implementation of the paper "A Memory-Related Multi-Task Method Based on Task-Agnostic Exploration".


## 
| Ground Truth | Model Output | Visualization |
| [{'name': 'pushTo', 'args': ['orange', 'box']}, {'name': 'pick', 'args': ['chair']}, {'name': 'drop', 'args': ['chair']}, {'name': 'pickNplaceAonB', 'args': ['sponge', 'table']}] | [{'name': 'pushTo', 'args': ['orange', 'box']}, {'name': 'pickNplaceAonB', 'args': ['sponge', 'table']}])  | ![](docs/assets/1.gif) |
| [{'name': 'pushTo', 'args': ['orange', 'paper']}, {'name': 'pickNplaceAonB', 'args': ['book', 'cube_green']}, {'name': 'pushTo', 'args': ['chair', 'stool']}] | [{'name': 'pushTo', 'args': ['orange', 'paper']}, {'name': 'pickNplaceAonB', 'args': ['book', 'stool']}, {'name': 'pickNplaceAonB', 'args': ['book', 'stool']}, {'name': 'pickNplaceAonB', 'args': ['book', 'cube_green']}, {'name': 'pushTo', 'args': ['chair', 'stool']}])) | ![](docs/assets/2.gif) |
| [{'name': 'pickNplaceAonB', 'args': ['bottle_blue', 'table']}, {'name': 'pushTo', 'args': ['tray2', 'mop']}, {'name': 'moveTo', 'args': ['cube_red']}] | [{'name': 'pickNplaceAonB', 'args': ['bottle_blue', 'table']}, {'name': 'pushTo', 'args': ['tray2', 'mop']}]) | ![](docs/assets/3.gif) |
| [{'name': 'pickNplaceAonB', 'args': ['apple', 'couch']}, {'name': 'pushTo', 'args': ['cube_gray', 'tray']}, {'name': 'pushTo', 'args': ['chair', 'book']}, {'name': 'moveTo', 'args': ['bottle_red']}, {'name': 'pickNplaceAonB', 'args': ['orange', 'chair']}] | [{'name': 'pickNplaceAonB', 'args': ['apple', 'couch']}, {'name': 'pickNplaceAonB', 'args': ['cube_gray', 'tray']}, {'name': 'pushTo', 'args': ['cube_gray', 'cube_green']}, {'name': 'pickNplaceAonB', 'args': ['orange', 'chair']}]) | ![](docs/assets/4.gif) |
| [{'name': 'pushTo', 'args': ['cube_red', 'orange']}, {'name': 'pushTo', 'args': ['orange', 'couch']}, {'name': 'pushTo', 'args': ['mop', 'cupboard']}] | [{'name': 'pushTo', 'args': ['mop', 'cupboard']}, {'name': 'pickNplaceAonB', 'args': ['orange', 'couch']}]) | ![](docs/assets/5.gif) |


## Running Code
Code will be publicly released after paper review period.





## References
* This implementation based on the following repo
* tango: https://github.com/reail-iitd/tango/wiki/Training-your-own-models
* CQL: https://github.com/BY571/CQL
* min-decision-transformer: https://github.com/nikhilbarhate99/min-decision-transformer
