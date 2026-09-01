 1. Download the executable binary
curl -L -o ~/idam "https://github.com/idamemmanuel202-Ogb/idam/releases/download/v1.0.0/idam"

 2. Grant execution permissions
chmod +x ~/idam

 3. Export the required license secrets
export GEN2_LICENSE_SECRET="ChangeThisToYourOwnVeryLongSecretPhrase32CharsMin"
export GEN2_ACCESS_KEY="MYKEY12345"

 4. Launch the application
~/idam
