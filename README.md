# insteon-python-lib
An initial concept for a Python library for interfacing with the Insteon Hub2 Restful API http://docs.insteon.apiary.io/

# Status
__Abandoned__

## Not Robust
The Hub and the API primarily focus on device control.  Neither the Hub nor the API have any mechanism for managing links between insteon Devices.  If you have a handful of Insteon devices manually managing links between the devices becomes tedious and with a lot of devices it becomes impossible.

## API Keys are Difficult to Obtain
Initially, this library was meant to provide a standardized bridge to the Insteon platform.  This would enable home automation platforms such as Home Assistant https://github.com/balloob/home-assistant to add insteon support.  But I have since heard that Insteon has become quite stingy with handing out API keys with people waiting weeks to months with no response.

Until these problems are fixed, I will not be spending anytime on development of this library.  Maybe in the future it can be revived if things change.
