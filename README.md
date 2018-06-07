# macOS Bootstrap

> Build a macOS test environment

## Usage Example

```
vagrant up
vagrant ssh-config > ssh-config
rsync -av -e 'ssh -F ssh-config' . default:~/workspace
ssh -F ssh-config default
```

```
cd workspace
./bootstrap
ansible-playbook main.yml
```