# Cosmic Bridge Wallet
Wallet plugin for Chrome.


### Concept

Allows users the ability to participate in a Cosmic Bridge payment network and send batched bitcoin payments (through the Cosmic Bridge application) directly from Chrome.

### Dev Notes

#### Setting up the extension locally
<ol>
<li>
    Run the following command from the `/cosmos-bridge-extension` directory:
</li>
<pre>
    yarn build
</pre>
<li>
    Navigate to the extensions page of your chrome browser.
</li>
<img src='./img/extension.gif' width="400px"/>
<br/>
<li>
    Once there enable "Developer mode".<br/>
</li>
<img src='./img/developer_mode.png' width="400px"/>
</br>
<li>
    Drag the output of the build folder from step one into the chrome extensions browser page.
</li>
<img src='./img/bridge_extension.png' width="400px"/>
<br/>
</ol>

The extension should now be added to chrome in Developer mode.


