# Firewall Unblocker (for CSF & WHMCS)

This extension provides the ability to self-service Unblock IPs from within WHMCS.

## 🎯 (MODULE) System Requirements 🎯

- Server Integrated OK
- WHMCS v8.x latest
- CSF 14.x latest
- PHP# latest

## 🐛 (MODULE) Permission Requirements 🐛

- `software-ConfigServer-csf` (WHM > Reseller ACL > needs this enabled)
- `whmuser:0:USE,ALLOW,DENY,GREP,UNBLOCK` (within /etc/csf/csf.resellers)

## ✅ (INSTALL) How to Install & Prepare ✅

- Download the latest version of the module
- Upload the module into WHMCS_WEBROOT/modules/addons/
- Visit WHMCS Admin > Settings > Addon Modules > enable it
- From there, it will be visible in the Admin & Client GUIs

## ⚙️ (FAQ) What can this module do? ⚙️

- Allow your customers to unblock their IP from your server's CSF firewall.
- Checks for IP Block on all cP/DA servers associated with an active client service.
- Uses a Smarty template file so you can easily change look/feel of the addon module.
- Only shows the link to the module in your menu if the client has an active cPanel.
- Displays the CSF log entry so the client can see the reason for the block.
- Logs successful unblocks in the WHMCS client log for potential review.
- Set max number of unblocks a client can do in a configured time period.
- Admin GUI: Quickly search for and remove blocks across all cPanel servers.
- Optional: Auto-check for & remove a block when client logs in to WHMCS.

## 🏢 (TNC) Links out to TNC & Co. 🏢

[The Network Crew Pty Ltd](https://thenetworkcrew.com.au)
