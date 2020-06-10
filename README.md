# OSS_FINAL
# Playing Piano 

Project : Make & publish an open-source (web) service running on my rasbperry pi.
My project : open - source Piano web service
(source code :  html, javascript) 

Goals : Simple piano playing
        It is used as a toy piano for young children, and can be used as a piano for adults to perform simple or check piano notes. 

Contribution : There are many piano applications on the Internet, but there was no way to implement them directly on the website.
                So, using Raspberry Pi, I created a website where I can practice piano through a web server.  
                I used html, javascript, and css for this website, so I think anyone can use this code elsewhere, and others can modify the                 code to make a better site.
        
Code required : 
  1) html file
  2) piano notes sound (.mp3)
  3) piano picture
  4) sheet music picture

Also, there is a Demo video (playing piano).


P.S. When you need to move file to the linux server
using this comman on cmd (window)
-> pscp [File path to upload][Server access account]@[server access IP]:[Server directory path to be uploaded]
-> ex) pscp C:\Users\desktop\OSS\* pi@raspberrypi.local:/var/www/html/OSS
