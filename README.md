# Using Burp Suite to scan a public testing banking site webserver
Showing a temporary project with the free edition of Burp suite to scan a testing banksite

## Overview: Using Burp suite free edition to test a bank website. The free edition only allows temporary projects. Only the license version allows you to save projects.

I selected Burp Suite from the Kali application launcher/search bar

<img width="571" height="301" alt="1" src="https://github.com/user-attachments/assets/737f3d4d-197b-4041-9d54-5abcd570305e" />

This is where it shows you the free edition only allows temporary projects. The license version allows you to save projects

Select next 

<img width="794" height="571" alt="2" src="https://github.com/user-attachments/assets/4df23646-b805-4aac-90c4-c1ca14c9c761" />

select start burp

<img width="765" height="559" alt="3" src="https://github.com/user-attachments/assets/05493fc3-565c-45a6-ae54-49a2db071893" /><br/>



Burp suite creates a new project and then shows you the main screen<br/>

<img width="1594" height="737" alt="4" src="https://github.com/user-attachments/assets/aeb127a8-80f7-43df-98d3-b325fed34733" />

We'll go to the Target tab.  The target tab has three sub tabs **-Site map- -scope- -issues-** 

<img width="545" height="229" alt="5" src="https://github.com/user-attachments/assets/fee3c0e9-2629-460a-9317-4baa03e1437e" />


The site map tab is empty at the moment, but it shows the construction of the website your testing.


<img width="1595" height="739" alt="6" src="https://github.com/user-attachments/assets/3d60aeae-cd3b-4f89-a729-add03461f50a" />

In the scope tab, this sets up the targets for testing.

To include in your scope you select Add:

<img width="1062" height="676" alt="7" src="https://github.com/user-attachments/assets/0e9cc27a-4a10-42f9-9f04-6623a86eef8e" />

 I'm going to place a banking website to test which is the public testing server site I used in a previous example.

<img width="832" height="366" alt="8" src="https://github.com/user-attachments/assets/e6c24b06-3de6-431a-8201-dd2ca429d954" />

<img width="543" height="80" alt="9" src="https://github.com/user-attachments/assets/c9119d84-a771-4514-97f3-6152860229c6" />

after clicking ok, select yes on the proxy pop up.

<img width="499" height="235" alt="10" src="https://github.com/user-attachments/assets/422bc1d8-bf20-4e70-b47f-673079a34131" />

now go to the proxy tab

<img width="1592" height="739" alt="11" src="https://github.com/user-attachments/assets/7a87a67f-e45c-4e8c-bd4d-8cd820b3cb0c" />
Shown above in the proxy tab, interception is off. That's where I want to be to let traffic flow through.<br/><br/><br/>

while in the proxy tab, go into proxy settings which shows listeners on port 8080 
<img width="630" height="187" alt="50" src="https://github.com/user-attachments/assets/1c632450-e249-4f33-888e-887b8d4ca7c2" />

<img width="1174" height="706" alt="12" src="https://github.com/user-attachments/assets/9b56665e-d8f4-4cb8-89aa-f9ec1271609e" />


