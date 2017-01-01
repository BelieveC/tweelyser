#Tweelyzer

A `Flask` web-app to display analytics based on a particular users' Twitter profile.
User can analyse any profile for public data, as permitted by Twitter REST API (which restricts access to protected accounts).

The number of API requests are limited within a time-frame. It is therefore requested to generate your own API key from [Twitter developer site](https://developer.twitter.com).

For contributing, a basic initial setup is required to contribute to this `Flask` project.

    git clone https://github.com/himanshub16/tweelyser.git
    cd tweelyser
    virtualenv -p /usr/bin/python venv
    source venv/bin/activate
    pip install -r requirements.txt 

Run the `app.py` file any time you want to test the app.