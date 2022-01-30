# DEFENDER

![Cover Image](https://github.com/edward62740/defender/blob/main/defender.png)

This is a 2.4GHz Wi-Fi scanner for measuring channel usage and detect deauthentication attacks. The collected data is sent to a database to be analyzed and provide notifications.

## Design Objectives

* Provide notifications on deauthentication attacks (including which channel(s) they are on).
* Allow for measurement of 2.4GHz Wi-Fi channel packets per second to estimate channel noise. Since Wi-Fi is the biggest "polluter" of 2.4GHz in residential environments, this data can be used to steer other linked systems clear of noisy channel frequencies.
