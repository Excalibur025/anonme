# AnonMe
A script to connect to Windscribe VPN and change MAC for safe browsing. This script is written in Bash and requires the repos Windscribe-CLI, macchanger and cowsay. An active windscribe account will be required and set-up can be located at the Windscribe webcite regarding Linux installs. Macchanger and Cowsay are available in the standard gobal repos for most major linux systems.

  $ sudo apt-get install macchanger
      - When prompted, the package will ask to randomize MAC upon every new network connection. Choose 'No'.
      
  $ sudo apt-get install cowsay
      - Standard install
      
Before running the script, you'll need to change the default hardware device for your network card. This can be found using the $ ifconfig cmd. Add your hardware device under the 8th line of code for Macchanger.

Additionally, you may need to make the script excutable with $ sudo chmod u+x anonme.
Within the script, the default location set will be the Miami Windscribe server. This can be changed depending on personal prefrence at line 9. For all available locations, use $ sudo windscribe locations.
