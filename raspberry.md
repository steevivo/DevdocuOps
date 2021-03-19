# Raspberry

connect wifi

```text
touch /Volumes/boot/ssh
```

```text
touch /Volumes/boot/wpa_supplicant.conf

country=US
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1

network={
    ssid="NETWORK-NAME"
    psk="NETWORK-PASSWORD"
}
```

