# Block coding tutorial

This block coding platform allows students to control the Maicat through an easy-to-use visual programming interface.

## Getting Started    

### Preparation for Block Coding

1. **Download block coding release file**   
 
    Turn on educational maicat and use terminal so that finding maicat's ip
 
2. **Find Maicat's IP Address**    

    Turn on the educational Maicat robot and open a terminal to find its IP address. Use the following command:

    ```bash
    ifconfig
    ```
 
3. **Execute the Block Coding Application**    

    Execute file named `maicat_block_coding`. The main screen will appear as shown below :    

    ![main-screen](https://github.com/user-attachments/assets/29773b59-83ef-414d-a466-7cdc53d28812)    

4. **Connect Maicat to the WebSocket**    

    Enter Maicat's IP address in the text field located at the top right. After entering the IP, click the "연결" button.    
    If the connection is successful, the "연결되지 않음" message will change to "연결됨" as shown below:

    ![textField](https://github.com/user-attachments/assets/92f6ab1b-0e13-429e-bfc1-2efc0ff545fc)    
 
    ![textField-connect](https://github.com/user-attachments/assets/1a1485f5-f473-4cef-8411-65b22147e6ec)

5. **Enter Maicat's ID**    
    
    To send commands to Maicat, you must input its unique ID. Enter Maicat's ID in the "ID를 입력하세요" text field and click the "입력" button. Once the ID is entered, the message "ID: 없음" will change to "ID: [Entered ID]" as shown below:

   ![textField-connect](https://github.com/user-attachments/assets/1a1485f5-f473-4cef-8411-65b22147e6ec)

   ![textField-id](https://github.com/user-attachments/assets/983fad1d-9ba0-4675-a62d-0c7e8b5fe229)

The preparation for block coding is now complete.

### Start Block Coding   

- '시작' Category
  
  This is the main block for Maicat's actions. When the start icon in this block is clicked, it will execute all the blocks contained within it.
    
    Any blocks not placed within this block will not be executed.

  ![start](https://github.com/user-attachments/assets/d66f5b50-f16b-42f9-93a4-6cc79dc96c3a)

- '눈 스타일' Category
  
  This category contains blocks that can change Maicat's eye expressions. The same action cannot be repeated multiple times in a single execution.

    ![eye-style](https://github.com/user-attachments/assets/33143008-fd2c-4650-92c4-c7282cdc2158)

- '이동' Category
- 
  This category contains blocks that allow Maicat to move. Each block makes Maicat take one step.
  
    ![move](https://github.com/user-attachments/assets/35c9abb7-449e-438e-a9f4-153c055d67a6)

- '울음소리' Category
  
  This category contains blocks that make Maicat meow. Each block triggers one meow.

    ![meow](https://github.com/user-attachments/assets/53d953cd-acc9-469e-8f26-fbe28b647950)

- '흐름', '판단', '계산' Category
  
   These categories contain blocks for creating logical expressions in your code.    

   ![block1](https://github.com/user-attachments/assets/edc31b63-612e-46ed-a28f-83854f9b95bf)
   ![block2](https://github.com/user-attachments/assets/eef649a4-ba5b-4da5-a7ad-0b42652abf95)
   ![block3](https://github.com/user-attachments/assets/012148e0-f157-4967-aa76-e94d622fc0b3)

- Trash Bin        

    Deletes all unnecessary blocks. Drag and drop any unwanted blocks onto this icon.   

    ![trash](https://github.com/user-attachments/assets/796d9e0e-b132-4d5f-b425-740ae434a23a)    

- Zoom, Shrink, and Center Icons    
  
    These icons allow you to zoom in, zoom out, and center the editor's position.
  
    ![zoom](https://github.com/user-attachments/assets/0fffbb61-505e-47f5-8591-8a29ce5e59d5)
