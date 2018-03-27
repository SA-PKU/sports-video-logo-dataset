# sports-video-logo-dataset



The sports-video-logo-dataset contains two directories, and each directory contains two sub-directories. The format of each annotation .xml file is the same as VOC dataset.
:
- ./SportsLogoVideo: this directory contains the video clips and the logo annotations in each frame. We annotate 20 logo classes with high frequency.
	- ./images: each sub-directory under this direcroty is a logo image set of one logo class. The sub-directory name is the logo class name.
	- ./annotations: contains the annotations corresponding to the ./image directory.

- ./SportsLogoImage: this directory contains the corresponding logo image dataset. there are also 20 classes logos corresponds to the video directory.
	- ./images: each sub-directory under this directory is a set of video frame sequence. The order of the frame is the same as the order of the file names.
	- ./annotations: contains the annotations. Each sub-directory under ./annotations is the annotations corresponding to the sub-directory under ./images directory.



Please cite the paper below if you use the dataset:

		@inproceedings{Liao2017Mutual,
		title={Mutual Enhancement for Detection of Multiple Logos in Sports Videos},
		author={Liao, Yuan and Lu, Xiaoqing and Zhang, Chengcui and Wang, Yongtao and Tang, Zhi},
		booktitle={IEEE International Conference on Computer Vision},
		pages={4856-4865},
		year={2017},
		}
