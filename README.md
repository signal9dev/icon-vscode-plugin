
# [ICON SCORE Support](https://github.com/signal9dev/icon-vscode-plugin)

<p >
    <a href="https://marketplace.visualstudio.com/items?itemName=signal9.icon-vscode-plugin">
        <img src="https://vsmarketplacebadge.apphb.com/version/signal9.icon-vscode-plugin.svg" alt="Marketplace badge">
    </a>
</p>

## Features
A VSCode extension to develope ICON SCORE.
Helping ICON SCORE developement. SCORE can be developed and easily deployed on the ICON network.

### Initial Deploy
    Can be deployed on ICON mainnet, ICON testnet or your own testnet.

### Update Deploy
    Can be update deployed on ICON mainnet, ICON testnet or your own testnet.

### Send Transaction
    Provide external function call interface after deployment.

**_We plan to offer more features in the future._**

## Requirements
Visual Studio Code version 1.31+

## Install
![install](https://github.com/signal9dev/icon-vscode-plugin/blob/master/images/install.gif?raw=true)

## Preference
### Setting preference
You can set the preferences with VS Code Application menu.
Code>Preferences> Settings> Extension> ICON SCORE>
Click Edit in settings.json
``` text
# settings.json

# wallet(Mandatory)
"icon.wallet": [
{
"name" : "test_wallet",
"path" : "/dir/keystore_file"
},
{
"name" : "test_wallet2",
"path" : "/dir/keystore_file2"
}
],

# custom uri(Optional)
"icon.network custom url": "http://localhost:9000/api/v3",

```

![TBD](https://github.com/signal9dev/icon-vscode-plugin/blob/master/images/preferenceSettingDemo_v1.1.gif?raw=true)

## Demo
### Deploy to ICON network

![TDB](https://github.com/signal9dev/icon-vscode-plugin/blob/master/images/deployDemo_v1.1.gif?raw=true)

### Sending transaction
![TBD](https://github.com/signal9dev/icon-vscode-plugin/blob/master/images/sendTrxDemo_v1.1.gif?raw=true)

<!--

## Extension Settings

Include if your extension adds any VS Code settings through the `contributes.configuration` extension point.

For example:

This extension contributes the following settings:

* `myExtension.enable`: enable/disable this extension
* `myExtension.thing`: set to `blah` to do something
>

## Known Issues

N/A

-----------------------------------------------------------------------------------------------------------
-->

### For more information

* [Signal9](http://signal9.io/)
* [Contract Support System](http://icon.signal9.io/)
