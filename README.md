# PrivateRouter OpenWRT WireGuard setup with TorGuard VPN
<p>PrivateRouter offers an easy WireGuard VPN setup tool compatible with TorGuard's VPN config generator. This is the fastest and easiest way to get TorGuard's WireGuard service up and running on your router. This tutorial will show step by step how to generate a wireguard config and add the settings onto your router.</p>
<p>1.) First, visit the TorGuard members area and access the <a href="https://torguard.net/tgconf.php?action=vpn-openvpnconfig" target="_blank" rel="noopener">VPN config generator tool</a>. Under VPN tunnel type select WireGuard, choose your VPN server location then type your TorGuard VPN username in the username box. Click the Generate config button.</p>
<p><img src="https://privaterouter.com/members/index.php/images/kb/66_wg1.png" alt="" width="1152" height="757" /></p>
<p>2.) Scroll down and copy paste the following values into your PrivateRouter in step 3.</p>
<p>Private Key</p>
<p>ListenPort</p>
<p>Address</p>
<p>Public Key</p>
<p>Endpoint:Port</p>
<p><img src="https://privaterouter.com/members/index.php/images/kb/67_wg2.png" alt="" width="1150" height="755" /></p>
<p>3.) Click the VPN tab then click "tgwireguard". If you don't have the tgwireguard app you can download from <a href="https://github.com/PrivateRouter-LLC/openwrt/raw/main/luci-app-tgwireguard_1.0.0-1_all.ipk" target="_blank" rel="noopener">Github at this link</a> and install by clicking System, Software, and Upload Package. (This package is compatible with any mainline version of OpenWRT.) </p>
<p>Paste each value from step to into the matching text box as seen below, then click Save and Apply.</p>
<p>Your router is now configured to connect to that TorGuard WireGuard VPN server at all times even after bootup. No Firewall settings are required. </p>
<p>Click the "Start WireGuard" and "Stop WireGuard" at anytime to modify your connection. </p>
<p><img src="https://privaterouter.com/members/index.php/images/kb/68_wg3.png" alt="" width="1160" height="755" /></p>
