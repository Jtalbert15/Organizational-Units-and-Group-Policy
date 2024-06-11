# Organizational-Units-and-Group-Policy

To start navigate to Active Directory Users and Computers

<img width="669" alt="Screenshot 2024-06-11 at 3 26 31 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/6ada3772-3ca4-4bd1-bda5-13a1970f16f7">

We can see we already have an organizational unit called IT

Let's create another one

To do this we need to click on the button below

<img width="100" alt="Screenshot 2024-06-11 at 3 31 37 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/bf5ec0f4-53b8-4e76-b992-ae042f251f42">

Once you have done that you should be presented with this screen

<img width="381" alt="Screenshot 2024-06-11 at 3 33 05 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/89476f41-9985-48be-805d-9de9ca4021ea">

I have named my new OU Sales

Click Ok

<img width="675" alt="Screenshot 2024-06-11 at 3 33 52 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/9840a155-cf67-47fb-be2b-6860d863ce93">

Now we can see that we have created a new OU Unit and it is visible in our domain

Now using the same process let's create 2 more OU's within our sales OU for Users and Computers

<img width="670" alt="Screenshot 2024-06-11 at 3 36 09 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/f9a05cef-7311-424a-b9f2-1e63dec751dd">

Now navigate to group policy management 

<img width="659" alt="Screenshot 2024-06-11 at 3 37 49 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/0ebbf329-30c1-4a7e-9142-9f13a6e21fcf">

We can see the OU that we created within Active Directory Users and Computers 

Click on our newly created Sales OU

Now right click on the sales OU and select create a GPO in this domain and link it here

<img width="658" alt="Screenshot 2024-06-11 at 3 43 30 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/03f2c73f-9d1c-4596-9503-0d67702ec6a9">

Now that we have created a group policy Object let's create a visual policy so we can tell our server is working

Right click on the GPO and select edit...

<img width="690" alt="Screenshot 2024-06-11 at 3 48 36 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/19673cce-0642-45ad-9d40-f69c2fc337fa">

I have selected to hide and disable all items on the desktop

Now we can create a user in our sales department to see our group policy in effect

<img width="672" alt="Screenshot 2024-06-11 at 3 52 51 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/4fe87f41-5ee1-4fb2-be64-c4f736debe2b">

Now we can log into the new users account using a windows 10 VM 

<img width="638" alt="Screenshot 2024-06-11 at 3 56 14 PM" src="https://github.com/Jtalbert15/Organizational-Units-and-Group-Policy/assets/66844406/ffce84cd-c1ef-44c0-83cc-4110299d8a4e">

As you can see there are no icons on the desktop



