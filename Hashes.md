### **If there is not a padlock icon in the address bar or the address is not `https://code.google.com`, then this document could have been tampered with in-transit. Please verify that your browser securely accessed this document before using the hashes below.** ###

If you are downloading TenFourFox on a hostile or insecure network where data could be tampered with, or just want to make sure it downloaded correctly before filing a trouble ticket, you can certify your download with the hashes below.

To check the hash for your file, download it from SourceForge, _but do not decompress it_. Start `Terminal`. At the prompt, type (but **_do not press RETURN yet_**):

```
openssl dgst -ripemd160 
```

Drag the `.zip` file you downloaded into the `Terminal` window. Its path will be added to the command. Now press RETURN in the `Terminal` window. You should see a result like this:

```
RIPEMD160(TenFourFox7450-31.2.0.app.zip)= e6637dff473f68d2b4a4b6b920c70183d8658dea
```

Verify it in the table below (make sure you are looking at the right version and filename). If this matches, you can be very confident that your browser was downloaded correctly and was not tampered with during transit. You can continue with decompressing and installing it at this point.

Only the last two versions are displayed. You should always use the most current version if you are in a security-sensitive situation.

## Stable releases ##

**TenFourFox 31.6.0**

```
RIPEMD160(TenFourFoxG3-31.6.0.app.zip)= a218bc9214db97b01219ee9f0216683297ef4dd3
RIPEMD160(TenFourFox7400-31.6.0.app.zip)= 1be940a32d2fb551d1971dfa0abc8e4979bff886
RIPEMD160(TenFourFox7450-31.6.0.app.zip)= f95401e3938929b67f8964e95844a3d2c3134115
RIPEMD160(TenFourFoxG5-31.6.0.app.zip)= a06d0c31ceddb1831748b5dca11fd65183dda3ce
RIPEMD160(TenFourFox31E-changesets-20150329.zip)= 2196dc39179dc39a3cb1227b5746754a174ce501
```

**TenFourFox 31.5.0**

```
RIPEMD160(TenFourFoxG3-31.5.0.app.zip)= 440a1b1490e5e44dca737df08ebf0f063cae6a68
RIPEMD160(TenFourFox7400-31.5.0.app.zip)= 8c9d82c3898c84401ad6279353adfe2e27c3be82
RIPEMD160(TenFourFox7450-31.5.0.app.zip)= 9e89b95526e448bcfa03daf44f49a7dcd73e9e20
RIPEMD160(TenFourFoxG5-31.5.0.app.zip)= bfaaa2deba87361e64afa488b4e86cc41746607a
RIPEMD160(TenFourFox31E-changesets-20150220.zip)= cefd73847ef67cef098c28dab21cca925ae64b36
```