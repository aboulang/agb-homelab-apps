# AGB Homelab Apps

A personal [Umbrel Community App Store](https://github.com/getumbrel/umbrel-apps) for homelab applications.

## Add this store to Umbrel

In the Umbrel App Store, open the community app store settings and add:

```text
https://github.com/aboulang/agb-homelab-apps
```

## Apps

### NetAlertX

Network discovery, presence monitoring, and alerts for devices on the local network.

NetAlertX uses host networking and the minimum Linux capabilities required for ARP, Nmap, mDNS, NetBIOS, and related discovery methods. Its persistent configuration and database are stored by Umbrel under the app data directory.

After installation, open:

```text
http://<umbrel-ip>:20211
```

## Notes

- This store contains personal homelab packages and may include opinionated defaults.
- NetAlertX currently follows the upstream stable `latest` image tag because upstream's installation documentation uses that distribution channel.
- The NetAlertX web UI listens on TCP 20211. Its GraphQL service listens on TCP 20212.
