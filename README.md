# wpa_file
# Put the following in the WPA_supplicant file
# which lives in: /etc/wpa_supplicant/wpa_supplicant.conf
network={
        ssid="St. Patrick Guest"
        key_mgmt=NONE
}
network={
        ssid="St. Patrick Secure"
        psk=xxxx_replace_with_real_key_xxxxx
}
