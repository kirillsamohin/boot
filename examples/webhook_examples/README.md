# Webhook examples using pyTelegramBotAPI

There are 5 examples in this directory using different libraries:

* **Python (CPython):** *webhook_cpython_echo_bot.py*
  * **Pros:**
    * Official python libraries, it works out of the box (doesn't require to
      install anything).
    * Works with Python 2 and Python 3 (need to be converted with 2to3).
  * **Cons:**
    * Ugly code.
    * Many things to handle yourself, this can lead to errors.
    * Not powerful, do the trick but the performance is low.

* **CherryPy (3.8.0):** *webhook_cherrypy_echo_bot.py*
  * **Pros:**
    * It's a web application framework, cleaner code, uses objects for defining
      the web application.
    * Very good performance.
    * The project seems to be active, latest version is recent.
    * Works with Python 2 and Python 3.
  * **Cons:**
    * Some things are not very intuitive, reading the doc is a must.

* **Flask (0.10.1):** *webhook_flask_echo_bot.py*
  * **Pros:**
    * It's a web application framework, cleaner code, uses decorator which can
      be nice.
    * Good performance.
    * It's intuitive if you know how web application works.
  * **Cons:**
    * The project seems not to be very active, latest version dates 2013.
    * They don't recommend to use it with Python 3, but may work.
    * May be a oversized for just handling webhook petitions.
    
* **aiohttp (1.2.0):** *webhook_aiohttp_echo_bot.py*
  * **Pros:**
    * It's a web application framework
    * Python 3 compatible
    * Asynchronous, excellent performance
    * Utilizes new async/await syntax
  * **Cons:**
    * Requires Python 3.4.2+, don't work with Python 2

* **Twisted (20.3.0):** *webhook_twisted_echo_bot.py*
  * **Pros:**
    * Asynchronous event-driven networking engine
    * Very high performance
    * Built-in support for many internet protocols
  * **Cons:**
    * Twisted is low-level, which may be good or bad depending on use case
    * Considerable learning curve - reading docs is a must.
* **FastAPI(0.70.1):** *webhook_fastapi_echo_bot.py*
  * **Pros:**
    * Can be written for both sync and async
    * Good documentation
  * **Cons:**
    * Requires python 3.6+
    

*Latest update of this document: 01-03-2022
