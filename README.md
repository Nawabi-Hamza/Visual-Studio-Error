# Visual-Studio-Error

# Error while installing 'Live Sass Compiler' extension. Please check the log for more details.
# This is for ignore of certificate for download file in visual Studio:

        1:go in visual studio directory or folder of visual studio which installed in there 
        cd "C:\Users\<user>\Appdata\Local\Programs\Microsoft VS Code"
        2:then open the cmd and type this then vs will open you can download every file in there
        code.exe --ignore-certificate-errors

# I got this "XHR failed" error in Visual Studio Code.
# So I changed my network settings to use Google Public DNS (instructions)
Finally following instructions (by mohamed-mokhtar) solved for me:

    Go to : Control Panel\Network and Internet\Network Connections
    Choose your connection network and ( right click on it then choose properties )
    Select " Internet Protocol Version 4 (TCP/IPv4) and then click on properties in the bottom of this section
    At General section click on " Use the following DNS Server address : "
    Make " Preferred DNS server : 8.8.8.8 " (if you face a problem check this)
    Make " Alternate DNS server : 8.8.4.4 "
    Restart VS code
