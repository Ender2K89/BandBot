# BandBot
This is a robot I made for a customer.
<br/>
I myself named it "Band Bot", as I think it could be used for bands planning out what days band members will play.


## Usage 📝
Using the `config.py` file, you can set a time, and the day the message will be sent at.
When the message is sent, it contains a list of all days, and the message has corresponding reactions for all days.
The reactions are numbers from 1 to 6, 1 being Monday and 6 being Saturday.
Reacting will add your username to the corresponding day, and unreacting will remove you.

You can join as many days as you want, and all the data is stored in a database which you can setup in `config.py` as well.
