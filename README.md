# netflowapp-client-links

Public subscription files for **netflowapp.lol** client apps (V2Box, Shadowrocket, etc.).  
No server credentials — only client share links.

**Bundle sync:** 2026-03-23 — matches operator `subscription_all_nodes` + XHTTP-H3 JSON + SEND pack.

## Use in your app (subscription URL)

Paste this URL where the app asks for a **subscription link** (Base64):

**https://raw.githubusercontent.com/Daneshpajouh/netflowapp-client-links/main/subscription.base64.txt**

Plain multiline (some apps):

**https://raw.githubusercontent.com/Daneshpajouh/netflowapp-client-links/main/subscription.txt**

## VLESS XHTTP H3 (JSON)

**https://raw.githubusercontent.com/Daneshpajouh/netflowapp-client-links/main/xray_vless_xhttp_h3_min.json**

## Full copy-paste pack

See **SEND_HIM_COMPLETE.txt** in this repo (SlipNet / DNS tunnel section included).

## Tips

- Try **TCP REALITY** profile first; **Mux OFF**.
- UDP profile is **VLESS + XHTTP + H3**, not legacy “VLESS-QUIC”.
- Hysteria2: **SNI = netflowapp.lol**.
