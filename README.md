# scheduled-whatsapp-message
import pywhatkit
try:
    pywhatkit.sendwhatmsg("+91xxxxxxxxxx",
						"Hello from Shravya",
						22, 28)
    print("Successfully Sent!")

except:
       print("An Unexpected Error!")
