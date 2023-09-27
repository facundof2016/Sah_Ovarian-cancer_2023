# Code base for the paper: `Serum Lipidome Profiling Reveals a Distinct Signature of Ovarian Cancer in Korean Women.`

Two environments were used in this work, for other machine learning methods except autoML, please see the folder `ML-code`
For the autoML method, please see the folder `autoML-code`.

## Instructions for running the code.

For the `ML-code`:<br>
- To replicate the code, use the version of libraries as indicated in the paper and in the jupyter notebooks. 

For the `autoML-code`: 
- Clone the repository. <br>
- Build the docker. 
`docker build -t Dockerfile.`
- Run the docker container. 
- Run jupyter notebook. <br>
Note that the autoML model is saved as `askl_17_OC_3600.pkl`, you will need to unzip. 
