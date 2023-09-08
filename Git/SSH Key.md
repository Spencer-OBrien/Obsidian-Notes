```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```
add you GitHub email address

```bash
eval "$(ssh-agent -s)"
```
start the SSH agent

```bash
cat ~/.ssh/id_ed25519.pub
```
to get the public key 