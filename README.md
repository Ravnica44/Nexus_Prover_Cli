##CLI v0.5.3
(not working)

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

##UPDATE

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
git checkout vTAG 
```
https://github.com/nexus-xyz/network-api/tags

```shell
cd ~/network-api/public
```

```shell
./install.sh
```


#Optional: clean your space after the event

```shell
sudo pkill -u nexus
```

```shell
sudo userdel -r nexus
```

```shell
screen -XS Nexus quit
```

