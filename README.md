```shell
add user nexus
```

```shell
sudo usermod -aG sudo nexus
```

```shell
screen -S Nexus
```

```shell
su - nexus
```

```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```shell
echo 'export PATH="$HOME/.cargo/bin:$PATH"' >> ~/.bashrc
```

```shell
source ~/.bashrc
```

```shell
git clone https://github.com/nexus-xyz/network-api
```

```shell
cd ~/network-api/public
```

```shell
./install.sh
```
