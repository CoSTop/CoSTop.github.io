## Replica Package

Paper: *A Topic Guided Pointer-Generator Model for Generating Natural Language Code Summaries*

### Describe
We provide data and files used in paper as follows:

#### The Sequential Data for Dataset:

| File List | Brief Description |
| ---- |  ---- |  
| ToPNN-dataset/train/ | sequential data for original training data <br> (i.e., class, method, code topics, code summary) | 
| ToPNN-dataset/valid/ | sequential data for original validation data <br> (i.e., class, method, code topics, code summary) | 
| ToPNN-dataset/test/ | sequential data for original test data <br> (i.e., class, method, code topics, code summary) | 

#### The Packed Data for Dataset:

| File List | Brief Description |
| ---- |  ---- | 
| ToPNN-dataset/pkl/dats.tok | vocabulary for code tokens | 
| ToPNN-dataset/pkl/smls.tok | vocabulary for code topics | 
| ToPNN-dataset/pkl/coms.tok | vocabulary for code summary | 
| ToPNN-dataset/pkl/dataset.pkl | packed data for method, code topics, code summary | 

#### Source Code of Our Model

| File List | Brief Description |
| ---- |  ---- | 
| ToPNN-sourcecode/ToPNN-full | ToPNN model |


### Download
* Get sequential and packed dataset from this link: [dataset](https://drive.google.com/drive/folders/1wlITPt_QOI9ZbAfdsxrUfJQ5i95dG3hk?usp=sharing) 
* Get source code of ToPNN model from this link: [model](https://drive.google.com/drive/folders/1HB1IefhgF6UnZxTPnUk030XXC6dxVqu8?usp=sharing) 
