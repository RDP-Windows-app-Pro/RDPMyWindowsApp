
TO SETUP RDP]

sudo su


bash rdp.sh


TO INSTALL TAILSCALE : 


curl -fsSL https://tailscale.com/install.sh | sh

sudo tailscaled --state=/var/lib/tailscale/tailscaled.state &

sudo tailscale up