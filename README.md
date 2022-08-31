# LB-YouTube-Link-Handler
- Originally is an extension call "YouTube Video Duration" by Christina K.
- Specially modified/enhanced for the purpose of use by myself and/or Epi's LioranBoard gang

what this extension do ?  
Pass a youtube link to extension, and it will return 3 variable for you. 
1. Extract Youtube's VideoID from link
2. Return "Left Over" duration in milliseconds
   - if t= params not detect in url link, return full video duration.
   - if t= params is detected in url link,  return "Left Over" duration by using full video length minus starting second from t= params.
3. Check if Video is having some restriction by checking :
   - Is embeddable
   - Is require Age Verify (18+)
   - Is restricted on your country
   - Is a live stream
   
enable Debug if extension is not function correctly for view more info

----

Original Message by Christinna K: 

# LB-YouTube-Duration
 Retrieve duration of any YouTube video in milliseconds.

**How to install an extension:**
1. Download the .lbe extension file from **Releases** section (please do not right click and save) 
2. Click on Install Extension in your LioranBoard Receiver
3. Select the extension file you downloaded 
4. Select your default Transmitter you are using. Make 100% sure it is the correct one. 
5. Refresh your Transmitter or close and reopen Lioranboard Receiver. 
6. Most extensions include a premade deck with buttons. If you do not see one, create a new button, add "Send to Extensions" command and select the extension you just installed. If you can only see the extension name with no input fields, it means it was not installed correctly. Repeat steps above.    

[![](https://github.com/christinna9031/LioranBoard-Files/blob/main/img/paypal.png?raw=true)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3YWXYQE3HKWHQ)

DISCLAIMER: The extension is provided as is. The developer has no obligation to provide maintenance and support services or handle any bug reports.
Feel free to edit the extension for your own use. You may not distribute, sell or publish it without the author’s permission.