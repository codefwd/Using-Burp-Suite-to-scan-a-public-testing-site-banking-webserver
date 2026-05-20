

# Using Burp Suite to scan a public testing banking site webserver
Showing a temporary project with the free edition of Burp suite to scan a testing banksite

## Overview: Using Burp suite free edition to test a bank website. The free edition only allows temporary projects. Only the license version allows you to save projects.

I selected Burp Suite from the Kali application launcher/search bar

<img width="571" height="301" alt="1" src="https://github.com/user-attachments/assets/737f3d4d-197b-4041-9d54-5abcd570305e" />

This is where it shows you the free edition only allows temporary projects. The license version allows you to save projects

Select next We'll go to the Target tab.  The target tab has three sub tabs **-Site map- -scope- -issues-** 

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

To start web scanning, we first need to go to our web browser to network settings and make sure that we're on manual proxy configuration<br/><br/>

<img width="1582" height="735" alt="51" src="https://github.com/user-attachments/assets/f8ac80ba-3acf-476e-b84b-7b3df440f0df" />
<img width="1082" height="681" alt="52" src="https://github.com/user-attachments/assets/b70e3842-de18-46ad-bc48-8cbd6f707ba6" />
<img width="759" height="583" alt="53" src="https://github.com/user-attachments/assets/978ac2d5-9c79-4240-ad5e-86e32c5a1da7" />

 It should read:
 HTTP proxy is 127.0.0.1 and port 8080 

Now that we finished that, we can go to the bank site - the public testing site. We will login with the credentials: username and password. 

<img width="1224" height="609" alt="13" src="https://github.com/user-attachments/assets/69c19cf9-929c-482c-864c-6f643f54c8e8" />
<img width="710" height="415" alt="14" src="https://github.com/user-attachments/assets/26f366bb-95b2-4afa-ac56-58495c5a856e" />
<img width="1195" height="595" alt="15" src="https://github.com/user-attachments/assets/5cef9aae-13a6-4644-8fab-d2e9c7f914be" />
Now that we got to see our balance and investment accounts shown above, let's go back to burp and see what it captured.<br/><br/>


Back at burp suite, we can see on the Target and site map tab, the bank website has been captured.

<img width="1596" height="733" alt="16" src="https://github.com/user-attachments/assets/93c5a587-92a1-4faa-a91a-bfbc8c99c3eb" />

In the above picture, You can see to the left, the bank site tab. The image below shows a closer detail look: You can see the structure of the website that was loaded.

<img width="271" height="386" alt="17" src="https://github.com/user-attachments/assets/b080d6b1-6473-4447-9591-66d21eb04e53" /><br/><br/>


In the right hand panel you can see
The messages that have come in and gone out from the web site.
Below, you can see the browser request and server response details.
