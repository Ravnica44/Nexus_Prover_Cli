# CLI v0.5.5

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

https://github.com/protocolbuffers/protobuf/releases

```shell
wget https://github.com/protocolbuffers/protobuf/releases/download/v29.3/protoc-29.3-linux-x86_64.zip
```

```shell
unzip protoc-29.3-linux-x86_64.zip -d $HOME/.local && rm protoc-29.3-linux-x86_64.zip
```

```shell
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
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

# UPDATE

```shell
screen -r Nexus
```

stop the script with `Ctrl + C`

```shell
cd ~/network-api
```

```shell
git pull
```

```shell
git checkout [new tag]
```
https://github.com/nexus-xyz/network-api/tags

```shell
cd ~/network-api/public
```

```shell
./install.sh
```


# Optional: clean your space after the event
`on root and out of the screen`

```shell
sudo pkill -u nexus
```

```shell
sudo userdel -r nexus
```

```shell
screen -XS Nexus quit
```

