# WhatsAppNonContactMesg
Send Whatsapp message to Phone Numbers without having to add them as Contacts

## Installation & Use
No installation required, just click on [this link](https://arun-ks.github.io/WhatsAppNonContactMesg/) on your mobile.


Just click on the "Clean Number & make Link" to remove non-digit characters.
**Note**: The phone number should have +<international prefix> included.
    
Once that is done, you'd see the link. Press "Send Hi" to send the message using Whatsapp. 

## Limitations
This only works on mobile applications, which have whatsapp installed.

On 1 test, it had failed to work as required on Android's default internet explorer. But has been tested to work fine on Androids using Mozilla/Chrome. It also works fine on test iOS mobiles.

## How it works 
The page, cleans up & formats the input phone number. This is then passed to [Whatsapp API](https://faq.whatsapp.com/en/android/26000030/).
At the click of a button, the link is opened on WhatsApp.
