#!/usr/bin/python2
#coding=utf-8
#The Credit For This Code Goes To lovehacker
#If You Wanna Take Credits For This Code, Please Look Yourself Again...
#Reserved2020


import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,requests,mechanize
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser


reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(),max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]


def keluar():
	print "\x1b[1;91mExit"
	os.sys.exit()


def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(0.07)

#Dev:love_hacker
##### LOGO #####
logo = """
\033[1;                  _______________________________________________________
\033[1;                  |   █████████████████████████████████             |
\033[1;             /    |   █▄─▀█▄─▄█─▄▄─█▄─██─▄█▄─▀█▀─▄█▄─▄█             |
\033[1;            /---, |   ██─█▄▀─██─██─██─██─███─█▄█─███─██             |
\033[1;       -----# ==| |   ▀▄▄▄▀▀▄▄▀▄▄▄▄▀▀▄▄▄▄▀▀▄▄▄▀▄▄▄▀▄▄▄▀             |
\033[1;       | :) # ==| |  █𝕂𝕙𝕒𝕥𝕥𝕒𝕜█                                            |
\033[1;  -----'----#   | |______________________________________________________|
\033[;  |)___()  '#   |______====____   \___________________________________|
\033[1; [_/,-,\"--"------ //,-,  ,-,\\\   |/             //,-,  ,-,  ,-,\\ __#
\033[1;   ( 0 )|===******||( 0 )( 0 )||-  o              '( 0 )( 0 )( 0 )||
\033[1;----'-'--------------'-'--'-'-----------------------'-'--'-'--'-'--------------
	
