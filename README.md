# pihole-tailscale-cloudflared
A PiHole for Tailscale overlay networks + Cloudflare DNS

# Features
- Upstream DNS provided by Cloudflare (DNS over HTTPS)
- Accessable only within Tailscale network
- Logs stored on TMPFS

# Notes
- It is recommended to enable `Device Approval` on your Tailscale network. This will prevent a leaked key from being used to add unauthorized devices to your network.
