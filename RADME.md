# Encrypt file
Install requirements
~~~bash
pip3 intall -r requirements.txt
~~~

Generate keys
~~~bash
python3 key-gen.py
~~~

Path to folder for encrypt/decrypt
~~~bash
vim config.py
	PATH="FULL-PATH-TO-FLODER"
~~~

Encrypt all files in folder
~~~bash
python3 encrypt.py
~~~

Decrypt files
~~~bash
python3 decrypt.py
~~~

#### Using example
![exemple](https://i.imgur.com/z6aKyfk.gif)