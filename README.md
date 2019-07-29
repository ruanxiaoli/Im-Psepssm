# Im-Psepssm

Im-psepssm is an effective feature extraction method, which has lower dimensional features than tradition Psepssm under the same parameters.
To make it more convenience and simple for researchers to use the proposed feature extraction, a software localization service, namely SD-Psepssm Builder, is developed freely for researcher. The users needn’t have professional programming skills and model construction ability, and only select some follow feature extraction methods base on personal needs and data distribution characteristics to enrich their feature expression of relevant research. It unlike existing servers, which is unlimited the number of protein sequences uploaded by users. The homepage of SD-Psepssm is shown in Fig. 1
 
  ![image](https://github.com/ruanxiaoli/Im-Psepssm/blob/master/image/homepage.png)




    Fig. 1. The screenshot of SD-Psepssm Builder homepage
The user guide is providing as follows:
    
    
    Step1: Open the website and to find and download the DF-Psepssm Builder package, additional, besides the system, the source code of feature extraction and the experimental data used in the paper are also provided to facilitate the users to improvement this method.
    Step2: The local software need not to install. According to the instructions, this can find the ‘dist’ folder, clicking .exe file and staying for several seconds to enter the homepage shown in Figure 5.
    Step3: Click the ‘choose’ button to select PSSM file, then the file name selected by the user will appear in the text box for the user to again confirm the input information. Secondly, based on the data characteristics and requirements, users input parameter   and select the feature expression method in the check box. 
    Step4: Click the ‘Submit’ button. Based on the parameter settings in Step3, each protein sequence will generate a new feature vector and automatically store it in RXL-Feature Extraction file of disk C, and is not required for users to download. 
    
    The source codes were written in the programming language Python 3.6.4 on PC with Intel i5 7400 3.00 GHz CPU, 16 GB RAM and GTX1080ti GPU.
