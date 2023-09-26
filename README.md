# REST_API_PDF_ROTATE

## How to run  

- git clone 
```bash
    git clone https://github.com/hemantp88/Rest_pdf_rotate.git
```

- Have dependencies in requirements.txt (`pip install -r requirments.txt`)  
- run uvicorn using command uvicorn main:app   
 <img src="./images of execution/server_sunning.png">
- Go to : http://localhost:8000/docs  
    then select post /rotate  

- Try and execute 
        by clicking try it out and changes in schemna  
        "pdf":"adreess of pdf file"  
        "rotate": input angle of rotation  
        "page": input the page t be rotated  
<img src ="./images of execution/SwaggersUI.png" > 

- Execute  
<img src ="./images of execution/successful_execution.png" > 
- output will be generated 
- before exection
<img src ="./images of execution/before execution.png" > 


-After execution
<img src ="./images of execution/resultant pdf.png" > 




