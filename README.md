# Python-Phonenumber-check-Cli


## CodeAx

 - [Telegram](https://t.me/avekgaming)
 - [instagram](https://instagram.com/codeax1?utm_medium=copy_link)
 - [Youtube](https://youtube.com/channel/UC-Q6ZcOtcx1gZ9fI5MDDt3w)


## important to check

- First Of All Open Your Terminal And Install Your Module : pip install phonenumers
- After Successfully installation of module you have to open your file and code are given below
- Written by CodeAx
-  Write the +91 in the begining of phone number::::While using


## Deployment

open your python script and write your code

```bash
# First Of All Open Your Terminal And Install Your Module : pip install phonenumers
# After Successfully installation of module you have to open your file and code are given below
# Written by CodeAx
# Write the +91 in the begining of phone number::::While using


import phonenumbers
from phonenumbers import carrier
from phonenumbers import geocoder

while True:
    a = input('''press q to quit this code
    Enter Your PhoneNumber with +country_code :''')
    if a=="q":
        print("We SuccessFully Exited this code")
        break

    phone_number = phonenumbers.parse(a)

    print("Origin country is",geocoder.description_for_number(phone_number ,"en"))

    print("Company oF Sim is",carrier.name_for_number(phone_number, "en"))


```

## Run On Termux

```
apt update && apt upgrade
```
```
apt update
```
```
apt upgrade
```
```
pkg install wget
```

```
wget https://raw.githubusercontent.com/CodeAvek/phone_number_information_using_python/main/gatherinfophone.py
```

```
ls
```

```
python phone.py
```

Now You Tool Is Sucessfully started :)


## 🔗 Youtube Link

[![Youtube](https://i.ytimg.com/an_webp/3ADGRll9Y8k/mqdefault_6s.webp?du=3000&sqp=CNryl5UG&rs=AOn4CLBTVuRt4faxv_j726q3itdR5r0oMg)](https://www.youtube.com/watch?v=3ADGRll9Y8k)

