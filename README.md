### Small Object Detection Method Based on Global Multi-level Perception and Dynamic Region Aggregation

-----------

This method mainly consists of two modules: global multi-level perception module and dynamic region aggregation module. In the global multi-level perception module, self-attention is used to perceive the global region, and its linear transformation is mapped through a convolutional network to increase the local details of global perception, thereby obtaining more refined global information. The dynamic region aggregation module, devised with a sparse strategy in mind, selectively interacts with relevant features. This design allows aggregation of key features of individual instances, effectively mitigating noise interference. Consequently, this approach addresses the challenges associated with densely distributed targets and enhances the model’s ability to discriminate on a fine-grained level. This proposed method was evaluated on two popular datasets. 

#### DataSets

----------

The datasets used in this paper are TT-100K，NWPU VHR-10. The TT-100K can be found in https://cg.cs.tsinghua.edu.cn/traffic-sign/. NWPU VHR-10 can be found in https://github.com/lavish619/DeepLab_NWPU-VHR-10_Dataset_coco.

#### Requirement

-------------------

This article is implemented by Pytorch.

#### Cite

----------------------------------------------
Z. Zhu, R. Zheng, G. Qi, S. Li, Y. Li and X. Gao, "Small Object Detection Method Based on Global Multi-level Perception and Dynamic Region Aggregation," in IEEE Transactions on Circuits and Systems for Video Technology, doi: 10.1109/TCSVT.2024.3402097. 

----------------------------------------------

@ARTICLE{10542220,
  
  author={Zhu, Zhiqin and Zheng, Renzhong and Qi, Guanqiu and Li, Shuang and Li, Yuanyuan and Gao, Xinbo},
  
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  
  title={Small Object Detection Method Based on Global Multi-level Perception and Dynamic Region Aggregation}, 
  
  year={2024},
  
  volume={},
  
  number={},
  
  pages={1-1},
  
  doi={10.1109/TCSVT.2024.3402097}
  }
