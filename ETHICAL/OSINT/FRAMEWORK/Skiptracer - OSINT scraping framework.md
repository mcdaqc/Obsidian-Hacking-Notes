Skiptracer - OSINT scraping framework

Initial attack vectors for recon usually involve utilizing pay-for-data/API (Recon-NG), or paying to utilize transforms (Maltego) to get data mining results. Skiptracer utilizes some basic python webscraping (BeautifulSoup) of PII paywall sites to compile passive information on a target on a ramen noodle budget.

Installation

$ git clone [https://github.com/xillwillx/skiptracer.git](https://github.com/xillwillx/skiptracer.git?fbclid=IwAR0PFnCgPpD8nvPdehqbTuJuHqJpybd11zokN7W4yO1oYZxqYd98CfZ_620) skiptracer

$ cd skiptracer

Install requirements

$ pip install -r requirements.txt

Run

$ python skiptracer.py -l (phone|email|sn|name|plate)

The modules will allow queries for the following:

- Phone

- Email

- Screen names

- Real names

- Addresses

- IP

- Hostname

- Breach Credentials

Disclaimer:- This project was created for educational purposes and should not be used in environments without legal authorization.

[https://gitlab.com/illwill/skiptracer](https://gitlab.com/illwill/skiptracer?fbclid=IwAR0ntJHVZiqxqOe_XvfLyLONr9Z5BMK24wJCR2YBzg3lpdfrP6lPhM15l6Q)