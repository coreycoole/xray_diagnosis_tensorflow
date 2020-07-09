# Xray-Classification-TensorFlow-Keras
Process chest x-ray image data, varified and labeled by medical professionals.
Using TensorFlow and the Keras API, create and validate convolution neural networks that learn to recognize the presence of pnuemonia in the lungs.

The purpose of this study is to assist in the use and interpretation of chest X-ray images (anterior-posterior), as well as in the clinical referral and treatment of pediatric pneumonia.
Pneumonia kills approximately 2 million children under 5 years old every year. It is consistently estimated as the single leading cause of childhood mortality globally.     
The World Health Organization reports that nearly all cases (95%) of new-onset childhood clinical pneumonia occur in developing countries, particularly in Southeast Asia and Africa.(i) 
Bacterial and viral pathogens are the leading causes of pneumonia, but each require very different forms of management.(ii)

Bacterial pneumonia requires urgent referral for immediate antibiotic treatment, while viral pneumonia is treated with supportive care. 
Accurate and timely diagnosis is imperative.
A key element of diagnosis is radiographic data. Chest x-rays are routinely obtained as a standard of care and can help differentiate between unhealthy and healthy patients and further, the differents forms of pneumonia.  
However, rapid radiological interpretation of images is not always available, particularly in low-resource settings where childhood pneumonia has the highest incidence and highest rates of mortality.  

Cases of delayed, missed, and incorrect diagnosis are common, with an incidence in the range of 10% to 20%. Some errors in diagnosis stem from mistakes in the interpretation of diagnostic tests. For example, pathology, radiology, and the clinical laboratory each have error rates of 2% to 5%.(iii)
It is the goal of this study to create a robust and precise neural network that facilitates screening programs and supports a more efficient referral system in diagnosis of pneumonia, particularly in remote, or low-resource areas, leading to a broad clinical and public health impact. 

Dataset: 5232 pediatric chest x-rays selected from groups of pediatric patients of 1 to 5 years old from Guangzhou Women and Children’s Medical Center, China. The x-rays were classified by medical experts and a label assigned to each image. Classifications are either Normal(healthy), or Pneumonia.  

The following analysis asks with the image data provided, if can we classify with reasonable accuracy and precision, the presence of pneumonia in the lungs and what structure of neural network best encompasses the features and target data within the image dataset. 
A successful model will be highly accurate with minimal required processing time, as well as minimal difference between the training and testing datasets by resulting type one and type two errors. 


i - Epidemiology and Etiology of childhood pneumonia: Bulletin of the WHO; 2008

ii - Respiratory disease and its management: A. McLuckie, 2009   

iii - Bringing Diagnosis Into the Quality and Safety Equations: Graber M.D. et al., 2012
