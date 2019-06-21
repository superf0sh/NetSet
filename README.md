# NetSet
Operational Security utility and automator.

NetSet is designed to automate a number of operations that will help the user with securing their
network traffic. It also provides an easy way to gather proxies and run utilities through Tor.

All the utilities installed and used by NetSet will be automatically configured as well. Of course
the tool itself isn't the be all of Operational Security. Rather it is a convenient way of getting yourself
set up with the basics.

NetSet facilitates, among other things; 

A terminal multiplexer on demand, that has it's sessions routed through Tor.
Secured DNS traffic through automatic installation and configuration of DNSCrypt-proxy.
Tor Wall functionality that forces all traffic through the Tor Network.
Easy access to online OPSEC resources, the web resources in question can be opened in-script

And more.

## Usage

After cloning the repo navigate to the `NetSet` directory and run the following:
```
chmod +x *.sh
sudo ./netset-main.sh --install
```
This will install and configure everything you'll need for NetSet to function properly.

### Options

Please see an option overview below.
```
CLI Arguments                            
    '-t' or '--terminal' Starts         
    terminal multiplexer with all       
    connections routed through Tor        
										 
 	'-s' or '--status' prints a status   
 	overview of NetSet related network   
  utilities and their current state.

 	'-i' or '--install' runs a script
 	designed to install all of NetSet's
 	dependencies and configures them

Menu Options

 'Usage'          - Print options overview
 'Status'         - Print Status overview
 'Spoof MAC'      - Spoof MAC Address
 'Random Proxies' - Scrape random proxies
 'GeoSort Proxies'- Scrape GeoSorted proxies
 'ProtonVPN'      - Start ProtonVPN
 'Tor Terminal'   - Start terminal multi-
                    plexer, with all sessions
                    routed through Tor
 'Tor Wall'       - Configures iptables to
                    force all connections
                    through Tor.
 'OPSEC Resources'- Display NetSet's included
                    list of web resources.
  					        Select an entry to open
                    it in your default browser
```

### Note
Tested on Ubuntu 19.04

I plan on expanding this tool in the future with even more OPSEC related resources and/or operations.

Should you happen to come across a bug or have any questions regarding this tool.
Please feel free to [Open a Ticket](https://github.com/NullArray/NetSet/issues)

Thank you.


