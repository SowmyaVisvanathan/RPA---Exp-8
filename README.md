### Name : Sowmya V
### Reg no : 212222110045
### Date : 
# Exercise 8 - Basic Web Automation - Fill a Web Form 

### Aim:
To automate filling a simple web form with user data and submit.

### Software required:
UiPath Studio-community edition

### Procedure:

1. **Use Application/Browser**:
   - Drag a **Use Application/Browser** activity from the **Activities** panel to your workflow.
   - In the **URL** property, enter the URL of the web form you want to fill in (e.g., `"https://form.jotform.com/2425508..."`).
   - Select your preferred browser type, such as Chrome or Edge.

2. **Type Into - Enter URL**:
   - Inside the **Use Application/Browser** activity, add a **Type Into** activity.
   - Set this activity to type the URL into the browser’s address bar if it’s not already open.
   - Type the URL directly into the **Text** field of the **Type Into** activity, or use a variable if you want to store the URL separately.

3. **Type Into - Full Name Field**:
   - Use another **Type Into** activity to type a sample name into the "Full Name" field.
   - Click **Indicate on Screen** in the **Type Into** activity and select the "Full Name" field on the web form.
   - Enter the name you want to input, such as `"John"`.

4. **Type Into - Last Name Field**:
   - Add another **Type Into** activity for the "Last Name" field.
   - Indicate the "Last Name" field on the web form using **Indicate on Screen**.
   - Set the **Text** property to a value, like `"Doe"`.

5. **Fill Other Fields (Repeat as Necessary)**:
   - Use additional **Type Into** activities to enter data into other fields as needed.
   - For each field, use **Indicate on Screen** to select the correct target and set the appropriate text in the **Text** property.

6. **Click Submit Button**:
   - To submit the form, add a **Click** activity.
   - Use **Indicate on Screen** to select the "Submit" button on the form.
   - Ensure the **Click Type** is set to "Single" and the **Mouse Button** is "Left."


### Main.xaml:

![image](https://github.com/user-attachments/assets/431b57a5-051f-44c4-ad3f-e508f82f7deb)

![image](https://github.com/user-attachments/assets/5533216a-9c64-4565-9b99-200b67d17812)

![image](https://github.com/user-attachments/assets/f3c51067-de81-4c0a-af4b-0fcf847ffb08)


### Output:

![Screenshot 2024-11-12 113550](https://github.com/user-attachments/assets/a470f85c-c799-4f7e-8711-9014683d4dca)


### Results:
Thus, the automation process successfully accessed the web form, entered the specified data in each field, and submitted the form.


