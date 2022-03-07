# <Your-Project-Title>

## <img src="images/description.jpg" alt="Logo" width="1698">
  
<div align="justify">
 
These devices have almost the same categories as the wearables, so the results are similar:
<br />
<br />
<ul>
  <li><strong>Authentication</strong>: as it happened with wearables, “Exploitation for credential access” is the technique selected in this category.</li>
  <br />
  <li><strong>Insecure pairing method</strong>: the pairing method in smart home IoT devices can also be affected by the “Adversary-in-the-Middle” attack detailed in the wearables section.</li>
  <br />
  <li><strong>Unencrypted Communications</strong>: if the device does not use Bluetooth communications, the only technique adversaries may use is “Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol”.</li>
  <br />
  <li><strong>Static MAC address</strong> if the device uses a static MAC address, the device is exposed, as it happened with wearables, to the technique “System Network Configuration Discovery”.</li>
  <br />
  <li><strong>Transmission of sensitive information to third-party servers</strong>: as these devices are linked to the cloud, they will be affected by techniques like “Data from cloud storage object”.</li>
  <br />
  <li><strong>Sending of information and firmware updates via HTTP</strong>: as was the case with wearables, these devices are exposed to techniques such as “Network Sniffing” that capture the information sent via HTTP.</li>
</ul>

<p align="right">(<a href="https://rayuelaproject.github.io/Tests/">Back Testing</a>)</p>

</div>

## <img src="images/results.jpg" alt="Logo" width="1698">
  
<div align="justify">

Therefore, three techniques should be considered: “Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol”, “System Network Configuration Discovery” and “Data from cloud storage object”. These techniques have worse detection coverage while being commonly used by the selected cyber-criminal groups. 

<p align="right">(<a href="https://rayuelaproject.github.io/Tests/">Back Testing</a>)</p>

</div>
