#### [MokiyCodes](https://mokiycodes.github.io/MokiyCodes) / [PGP](https://mokiycodes.github.io/MokiyCodes/PGP/) / [Thunderbird](https://mokiycodes.github.io/MokiyCodes/PGP/Thunderbird)
The below describes how to use `PGP` with Thunderbird, to send and recieve encrypted emails.
## Setting Up Thunderbird
The below `3` sections describe how to initially setup Thunderbird's OpenPGP.<br/>
You only need to do this once per Thunderbird Installation.
### Opening the Thunderbird OpenPGP Key Manager
1. Open Thunderbird
2. Press `F10`
3. Go to `Tools`
4. Select `OpenPGP Key Manager`

### Generating a new PGP Key 
(If you have an existing PGP key, see [Importing an existing Key](#importing-an-existing-key) instead)<br/>
1. In the [OpenPGP Key Manager](#opening-the-thunderbird-openpgp-key-manager), select Generate
2. Select `New Key Pair`
3. Set the Expiration date, or select `Key does not expire`
4. Set the Key size to 4096
5. Click `Generate key`

### Importing an existing Key
(If you do not have an existing PGP key, see [Generating a new Key](#generating-a-new-key) instead)
1. In the [OpenPGP Key Manager](#opening-the-thunderbird-openpgp-key-manager), select `File`
2. Select `Import Secret Key(s) From File`
3. Click `Select File to Import...` and select __your__ existing PGP Key
4. Make sure `Treat this key as a Personal Key` is enabled
5. Click `Continue`
6. If you have a Passphrase on the key, input it into the prompt
### Adding someone else's Public Key to Thunderbird
The below points describe how to import someone else's public key into your thunderbird installation.<br/>
You need to do this once per thunderbird installation, per person, to be able to send encrypted emails to that person.<br/>
Requirements:
- An existing Private PGP Key (see [Setting Up Thunderbird](#setting-up-thunderbird))
- The person who you're trying to send emails to's public PGP Key (as an example, [my GPG key](https://raw.githubusercontent.com/MokiyCodes/MokiyCodes/main/Key)

(i will finish this soon)
