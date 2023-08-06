# SETI: Systematicity Evaluation of Textual Inference
We introduce SETI (Systematicity Evaluation of Textual Inference), which to our knowledge is the first benchmark to comprehensively evaluate the systematicity capabilities of PLMs when performing NLI. Here, we provide datasets for three NLI challenge tasks that evaluate systematicity, with controlled splits for seen vs. unseen information.
 
## Data
#### Data Format
```
{
"verdical_label": "yes",        
"sick_label": "entailment",    
"sent1": "He realizes a boy is jumping into the water", 
"sent2": "A kid is jumping into the water", 
"label": "entailment"   
}
```

* For a compositional inference sample, we provide its inference label ("label"), and its constituted primitive inference labels ("verdical_label" and "sick_label").
* For a primitive inference sample, we provide its inference label ("label").

#### Data for Evaluation
We provide datasets for three NLI challenge tasks that evaluate **Compositional Generalization** (systematicity), with controlled splits for seen vs. unseen information. If you need to do **In-Distribution** evaluation for one specific task: i) merging train and test data for the compositional test; ii) produce random splits 

## Download
**Method: OneDrive**
link: https://mailnankaieducn-my.sharepoint.com/:f:/g/personal/fuxiyan_mail_nankai_edu_cn/EkyQ0riCClFGvmXokN3dFdsBaOscHHnWgcaHOO0s20APYQ?e=04fMhI


## Citations
Please cite our paper if you are using this dataset.
```
@inproceedings{fu-frank-2023-seti,
    title = "{SETI}: Systematicity Evaluation of Textual Inference",
    author = "Fu, Xiyan  and
      Frank, Anette",
    booktitle = "Findings of the Association for Computational Linguistics: ACL 2023",
    month = jul,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-acl.252",
    pages = "4101--4114",
}
```

