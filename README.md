# OCR_Detection
ID card parsing using Online OCR Space API
https://ocr.space/ocrapi  
Free OCR API Endpoint (POST)
https://api.ocr.space/parse/image  
Deployed Link:https://ocrfront-ml5t.onrender.com


# Clone Repository
```bash
git clone https://github.com/saurabhs402/OCR_Parsing.git
```

# Folders
-Client Folder - Frontend  
-Server Folder - Backend using MongoDB  
  
-Open two terminal to run Server and Client separately.

# Run the Server(Running at  http://localhost:${PORT})

 **First Terminal Run Commands**  
 - Change the directory
```bash
    cd server
```
- Install the dependencies
```bash
npm i
```
- Start the server
    
```bash
    nodemon dbConnect.js
```
  
(**Note**: The port number suggested by your nodemon require to update the PORT variable in config.js and you can find config.js inside the OCR_Detection/client
/src/ )

# Render Frontend
 **Second Terminal Run Commands**  
- Change the directory
```bash
cd client
```
- Install the dependencies
```bash
npm i
```
- Start the Client
```bash
 npm start
```  

  (Now application starts Running)

# Screenshots
- **Evauationg the THAI id card using above mentioned API and showing the result of parsed image**

    
![Example Screenshot](screenshots/client1.jpg)  








                
- **ID card values stored in Datasbe can perform delete also using delete button**

    
![Example Screenshot](screenshots/client2.jpg)




