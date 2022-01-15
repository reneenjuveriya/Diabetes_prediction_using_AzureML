# DIABETES PREDICTOR
**A diabetes prediction model that is built using AZURE services.**

*  Upon providing certain information by the patient (i.e: Age, Gender, Body Mass Index, Blood Pressure, Serum 1-6, and current diabetes level - Y) the model will predict what the diabetes rate will look like in 12 months from the date of the inquire.
*  The value limits of the attributes are :
    *  AGE : 19-79 
    *  SEX : 1-2 
    *  BMI : 18-42.2 
    *  BP : 62-133 
    *  S1 : 41.6-242.4  
    *  S2 : 22-99 
    *  S3 : 2-9.09 
    *  S4 : 3.26-6.11
    *  S6 : 58-124 
    *  Y : 25-346  
 
</br>

## AZURE SERVICES THAT WERE USED IN THIS MODEL :
* **Machine Learning Studio**
* **Azure Kubernetes Service**

</br>

## HOW TO RUN : 
1. Open Postman
2. Click HEADERS button and enter Content-Type as header and application/json in value.
3. Next, click on BODY section  and copy the code from form.json file.
4. Then, Select POST from the dropdown next to the URL text box. And copy the following URL 
 ``` bash
  http://0425c800-689e-47fd-959f-21ce983b9255.eastasia.azurecontainer.io/score
  ```
5. Select raw from the buttons available below URL text box.
6. Select JSON from the following dropdown.
7. Finally, click send button to get the output.

![screenshot (3)](https://user-images.githubusercontent.com/93391666/149629320-5fd624e8-579e-45f3-94ee-f09f86a76b61.png)
</br>
## OUTPUT: 
![screenshot (4)](https://user-images.githubusercontent.com/93391666/149629325-786bf66b-4ec1-4d9a-8c37-41d8c730e94e.png)


