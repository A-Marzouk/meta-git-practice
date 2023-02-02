# Connect to your github account using SSH:

## Steps:
- Generate SSH key locally using this command:
    - `ssh-keygen -t ed25519 -C "your@email.com"`
- After passing the steps, public and private keys will be saved in your .ssh folder.
- Now, you need to get copy of your public key:
    - `ls ~/.ssh/`
    - `pbcopy < ~/.ssh/<YOUR KEY>.pub`
- then add this key to your github SSH allowed keys.
- Access the repo through the ssh url.
