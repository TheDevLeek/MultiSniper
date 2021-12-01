Autosell hasn't been fully tested, but if you get any errors then stick it in errors form in testing group pinned msgs.

This version only snipes TG tokens and not newly discovered tokens, however it will do in the future.

At the moment, it only sniped BNB paired tokens - it may cause errors if it tries to snipe a alt paired token eg. BUSD.

Please look at the README.png file for more information on how to setup the config file.

An option has been added to use telegram proxies. 

Proxy types supported: 'socks5', 'socks4', 'http'

Example (different to config file, just to explain what each option does):

proxy = {
    'proxy_type': 'socks5', # (mandatory) protocol to use (see above)
    'addr': '1.1.1.1',      # (mandatory) proxy IP address
    'port': 5555,           # (mandatory) proxy port number
    'username': 'foo',      # (optional) username if the proxy requires auth
    'password': 'bar',      # (optional) password if the proxy requires auth
    'rdns': True            # (optional) whether to use remote or local resolve, default remote
}



IMPORTANT:

Please make sure you have installed:

- telethon (pip3 install telethon in cmd line)
- web3 (pip3 install web3 in cmd line)
