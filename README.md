# WhatsAppNonContactMesg
Enable sending Whatsapp messages to Phone Numbers without having to add them as Contacts.
 
## Installation & Use
No installation required, just click on [this link](https://arun-ks.github.io/WhatsAppNonContactMesg/) on your mobile.

Type in the phone number you want to message & click the button to send whatsapp.

Alternately, you can generate QR Code, to share with others users. Scaning this QR Code will allow them to send whatsapp messages too.

**Note**: The phone number should have "international prefix" included  
   

## Limitations
This only works on mobile phones, which have whatsapp installed.

On 1 instance, it had failed in systems which used Android default internet browser. It has been tested to work fine on Androids using Mozilla/Chrome. It also works fine on test iOS mobiles.

## How it works 
The page, cleans up & formats the input phone number. This is then passed to [Whatsapp API](https://faq.whatsapp.com/en/android/26000030/).
At the click of a button, the link is opened on WhatsApp.

The page also uses [jquery.qrcode.js](http://jeromeetienne.github.io/jquery-qrcode/) to generate QR code. 
The QR code can be scanned to send Whatsapp message.
