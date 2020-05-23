# Hack The Box Autologin

HTBAL is a quality of life improvement, its purpose is to automatically log into HackTheBox and download and start openvpn connection

## Dependencies
	Linux
	Python 3
	Selenium
	HTB email, password and sudo password entered in on lines 26-29 or in command line

```bash
pip3 install selenium
```

## Usage

```python
	python HackTheBox.py
	or
	python HackTheBox.py <email> <password> <sudopassword>
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
