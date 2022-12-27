# hubble space telescope gan  
generative adversarial network, gan, for creating images resembling those taken by the hubble space telescope   
**unprocessed kaggle dataset**: https://www.kaggle.com/datasets/redwankarimsony/top-100-hubble-telescope-images?resource=download    

<br> 

## examples  
training sample: [opo0010a.png](./hubble_imgs_fixed/opo0010a.png)  
![**opo0010a.png**](./hubble_imgs_fixed/opo0010a.png)  

generated sample:    

### usage  


#### notes  
- the unprocessed kaggle imgs are in compressed .tif format  
- the imgs are rgba 4 color channel imgs represented in numpy as m x n x 4 tensors  
- be careful reading the imgs into a np.ndarray as some are very large  
