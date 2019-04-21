# HTTP based anonymous chat
Implement anonymous chat to your website within 42 seconds.

## What is Anonymous Chat?
HTTP based anonymous chat is a simple one to one chat service where the person does not know another. Both are strangers to each other. While some one using this service, we do not track any data of the user including chat content. The service is made for fun. 

## How to use the Anonymous Chat?
It is very simple to use. If you are using php as your backend processing just use the following code. When you are using

    echo file_get_contents('https://anonymous-chat.drivebird.com/');
    
you will have default settings which we provide. However you can edit those by sending some parameters. Example: 

    echo file_get_contents('https://anonymous-chat.drivebird.com/?brd=YOUR_BRAND&hdn=1&gac=UA-42232429-6');

If you are not using PHP as your backend processing, still you can use this service as html file. First get the source code of https://anonymous-chat.drivebird.com/ by opening that site in the browser and then press ctrl + u . Copy the content from the browser and save it into a .html file. Change the parameters as you like show. At last upload this .html file to your server and you are done.  Ask me if you need any help.

The chat script does not take any server resources. Even you don't need to use any database for it. This is plug and play solutions.

## Customizations
    Example: echo file_get_contents('https://anonymous-chat.drivebird.com/?brd=YOUR_BRAND&hdn=1&gac=UA-42232429-6&hdd=0&dsu=https://your-domain.com/anonymous-chat.php');
    
Parameters:

    brd (Brand): Ex: DriveBird Network
    dsu (Display Site URL): Ex: https://www.drivebird.com/services/anonymous-chat
    gac (Google Analytics Code): Ex: UA-42232429-6
    hdn (Hide Donation): Ex: 1(yes), 0(no)
    hdd (Hide Developer Documentation): Ex: 1(yes), 0(no)
    psl (Play Store Link): Ex: #
    asl (Apple Store Link): Ex: #


## Can I use it in my website?
Yes and it will help to all of users who are using this service. When you use it on your website, the main source file belongs to a single common server. So as many people uses this service will feel more enjoyable. Most importantly, it does not have any hidden charges, its totaly free of cost to use. 

## Documentation page?
https://www.drivebird.com/services/anonymous-chat

## Need further help?
Create issue here or navigate https://www.drivebird.com/ and contact with me with your queires. I will surely help you.
