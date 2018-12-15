# The risk of someone having access to your gekko:
There are various risks associated with the appropriation of your Gekko by someone else:
- they can see your bots
- they can start/stop bots
- they can run many backtests that will basically DOS your server

These risks only apply to people running a gekko server (eg. start the UI). This doesn't apply to CLI usage.
If someone has physical access to your computer DoSsing it via the Gekko API is the last thing they would do. They don't have to look up API keys stored by Gekkos as they can directly access your exchange accounts and email.

## How you can prevent people from this risk?
Since the risks apply only to those who launch a gekko server, here is some useful information to secure your server: https://gekko.wizb.it/docs/installation/configuring_gekko_on_a_server.html
However, protect yourself as well and do not disclose any information about your exchange accounts.
