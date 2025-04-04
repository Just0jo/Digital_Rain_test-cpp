---
layout: page
title: Design
---
## Code Execution Flow 
 1. User creates a DigitalRain object with desired dimensions of the length, width and speed at which the console shows images.
  
    ![image](https://github.com/user-attachments/assets/a440025e-0ec4-4aef-be65-10ccc87e82ab)
    
    The action is called in the main and the initialisation is stored in a class in the .h file
    
    ![image](https://github.com/user-attachments/assets/2088be43-5d2d-49c9-bf1d-3237d4666873)

2. start() is called, setting running = true, once true shape images can be displayed on the console.
   
   ![image](https://github.com/user-attachments/assets/489d0a41-d38a-4aae-a521-53ec5c8144b5)

3. printDigitalRain() runs in a loop, cycling through the shapes of 1s and 0s
     Each shape is drawn on screen with colored random binary digits
   
   ![image](https://github.com/user-attachments/assets/e64bc0b0-7f15-44b9-9178-b8e40c598ae3)
   
   The above code prints the 1s and 0s
   
4. Between shapes, the code checks for keyboard input
5. 
   ![image](https://github.com/user-attachments/assets/95edd679-4135-41dd-b75a-368841cbeb0a)
   
   We use khbit() to check for a button press and use _getch() to thew take in the pressed button
   once this is done it calls the stop() function.
   
 6.Animation continues until a key is pressed or stop() is called.
 
 ![image](https://github.com/user-attachments/assets/41d584e1-24a5-4e70-82ff-c5f71aa91985)

## Colour and  Number Generation:
 
1. My code uses modern C++11 random facilities (std::mt19937, std::uniform_int_distribution) to generate random numbers but i have it to display numebers between 0 and 1
 
   ![image](https://github.com/user-attachments/assets/c2b25e21-7481-47b1-8d12-c6aed2c5d41b)
   
   so only whole number between 0 and 1 are shown.
   my code generates binary digits (0 and 1) for the Matrix-style effect.
   
2. I use a random colour generator to create random colors for visual interest.
 
   ![image](https://github.com/user-attachments/assets/0e55e5c9-aae1-4bfd-9164-eb50f87ba44b)
   
   this function is used to call for random colours to be be seen.
   
   ![image](https://github.com/user-attachments/assets/8e3ef40b-bf39-4d88-93e7-9f72c97a0218)
   
   for the random numbers seen a random colour is also assigned.



