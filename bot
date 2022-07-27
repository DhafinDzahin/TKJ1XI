import os
import telebot
from keep_alive import keep_alive

keep_alive()
my_secret = os.environ['token']
bot = telebot.TeleBot(my_secret) 

@bot.message_handler(commands=['absen'])
def absen(message):

	try:
		 
			bot.send_photo(message.chat.id, r'https://ibb.co/TwVbC6S')

		  
			  
	except:
		pass 
		
@bot.message_handler(commands=['senin'])
def senin(message):

	try:
		 
			bot.send_message(message.chat.id,   'Upacara = 07:00-07:45 \nAIJ = 07:45-10:00 \nIstirahat = 10:00-10:15 \nMatematika = 10:15-12:30 \nIstirahat = 12:30-13:00 \nMatematika = 13:00-13:45 \nAgama = 13:45-16:00')
		  
			  
	except: 
		pass	
	 
@bot.message_handler(commands=['selasa'])
def selasa(message):

	try:
		 
			bot.send_message(message.chat.id,   "Bhs. Indo = 07:00-08:30 \nAIJ = 08:30-10:00 \nIstirahat = 10:00-10:15 \nPenjas = 10:15-11:45 \nASJ = 11:45-12:30 \nIstirahat = 12:30-13:00 \nASJ = 13:00-16:00 \n\nMandiri = WAN, ALJ, ASJ")
		  
			  
	except:
		pass

@bot.message_handler(commands=['rabu'])
def rabu(message):

	try:
		 
			bot.send_message(message.chat.id,   "Inggris = 07:00-09:15 \nWAN = 09:15-10:00 \nIstirahat = 10:00-10:15 \nPPKN = 10:15-11:45 \nWAN = 11:45-12:30 \nIstirahat = 12:30-13:00 \nWAN = 13:00-15:15 \nBhs. Indo 15:15-16:00 \n\nMandiri = PKWU, TLJ")
		  
			  
	except:
		pass
	 
@bot.message_handler(commands=['kamis'])
def kamis(message):

	try:
		 
			bot.send_message(message.chat.id,   "PKWU = 07:00-10:00 \nIstirahat = 10:00-10:15 \nPKWU = 10:15-11:00 \nBK = 11:00-11:45 \nTLJ = 11:45-12:30 \nIstirahat = 12:30-13:00 \nTLJ = 13:00-16:00")
		  
			  
	except:
		pass

@bot.message_handler(commands=['jumat'])
def jumat(message):

	try:
		 
			bot.send_message(message.chat.id,   "Senam = 07:00-08:00 \nLiterasi = 08:00-09:30 \nEskul = 09:30-SELESAI")
		  
			  
	except:
		pass

bot.polling(none_stop=True)
