# Exploring the Depths of 3D Semantic Novelty Detection

## Abstract 
_In the last years with the rise of autonomous driving in passenger vehicles and the need for fine processing of the 
data coming from the perception sensors, semantic novelty detection (out of distribution semantic classes) has become a really 
important task in safety-critical applications. It's important for the autonomous system to classify known object, meaning classes 
the model is trained on, but also to have a 'low-confidence' on samples that have unknown classes. In this paper the specific case of 
3D point clouds semantic novelty detection will be targeted, training two main backbones and evaluating their performances and then comparing 
them also to some already existing pre-trained models. 3D point clouds data is what usually comes from LiDAR scanners and stereo cameras present 
on autonomous systems, such as passenger vehicles, industrial robots, etc._

## Repository description

The repository contains almost the same files present in the original repository https://github.com/antoalli/SemNov_AML_DAAI_23-24 but some files have been added or 
modified such as **/utils/ood_utils.py** and **/classifiers/trainer_cla_md**.<br> 
Also **B32_Eval_Final**, **G14_Eval_Final**, were added, which are the codes for the OpenShape pre-trained models. <br>
The pre-trained models are not present due to their size but can be downloaded from the OpenShape repository https://github.com/Colin97/OpenShape_code <br>
The files that were used on Google Colab for the failure analysis and pre-trained models evaluation are also present as .ipynb files


