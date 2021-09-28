# kimo.ipa
تشكير تيك توك
# kimo1157
# kimo_ipa
import requests
import os
import time
import string
import random
import requests
import sys as n
import time as mm
import webbrowser

def slow(M):
    for c in M + '\n':
        n.stdout.write(c)
        n.stdout.flush()
#        mm.sleep(1. / 10000)
sa = 'https://kimotik.000webhostapp.com/kimo'
ld = '\033[1;32m'
f = '\033[1;35m'
jd = 'https://kimotik.000webhostapp.com/kimo'
r = requests.get(jd).text
t = requests.get(sa).text
req = requests.session()
Check =('Check')
print(ld+"━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━")
slow(""" 
\033[1;36m
                  /  |            /  |                                    
                   $$ |          $$/        ___  __          ____  
                   $$ |  /  |      /  |      /     \/    \        /      \ 
                   $$ |_/$$/       $$ |      $$$$$$ $$$$  |      /$$$$$$  |
                   $$   $$<        $$ |      $$ | $$ | $$ |      $$ |  $$ |
                   $$$$$$  \       $$ |      $$ | $$ | $$ |      $$ \__$$ |
                   $$ | $$  |      $$ |      $$ | $$ | $$ |      $$    $$/ 
                   $$/   $$/       $$/       $$/  $$/  $$/        $$$$$$/
""")
slow(f+r)
print(ld+"━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━")
webbrowser.open('https://t.me/kimo_ipa')
print('تشكير تيك توك ')
username = input("\nLIST USAR :")
id = input('ايدي [+]')
use = username
headers = {
            "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9",
            "User-Agent": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.83 Safari/537.36",
            "Connection": "close",
            "Host": "www.tiktok.com",
            "Accept-Encoding": "gzip, deflate",
            "Cache-Control": "max-age=0"
}
bh= '1960325282:AAHfu7NIHV_7FE7opbx_AFg7i95ADCUFRzo'

file = open(username, "r")
while True:
  Check = file.readline().split('\n')[0]
  tiklog = f'https://www.tiktok.com/@{Check}'
  rq = requests.get(tiklog, headers=headers)
  if rq.status_code == 404:
    tlg =(f'https://api.telegram.org/bot{bh}/sendMessage?chat_id={id}&text=\n✥ CHECKER TIKTOK V1✥\n━━━━━━━━━━━━\n✥. 𖣨.user : {Check} \n━━━━━━━━━━━━\n ; {t} ')
    req = requests.post(tlg)                
    print("متاح:  ✅ " + Check)
  elif rq.status_code == 200: 
     print("[!]  غير متاح ❌ -> : " + Check)
     if (Check == ""): 
       break
       webbrowser.open('https://t.me/kimo_ipa')
