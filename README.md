errbit.py
=========

Open source error catcher [Errbit](https://github.com/errbit/errbit) thin client. 
Alternatively, you can use [Airbrakepy](https://github.com/pulseenergy/airbrakepy) if you like `logging` approach.

Usage:
------

    client = ErrbitClient(
        ERRBIT_URL,
        ERRBIT_KEY,
        component="django",
        node=socket.gethostname(),
        environment="production"
       )
    client.log(exception)

Contribute
----------

This project needs love. Please, contribute.