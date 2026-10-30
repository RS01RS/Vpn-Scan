# Third-party notices — VPN Scan

## Proxy cores
| Component | License | Source |
|---|---|---|
| Xray-core (via AndroidLibXrayLite) | MPL-2.0 | https://github.com/XTLS/Xray-core · https://github.com/2dust/AndroidLibXrayLite (v26.10.21) |
| Xray-core 25.10.15 (separate program) | MPL-2.0 | https://github.com/XTLS/Xray-core/releases/tag/v25.10.15 |
| sing-box 1.14.4 (separate program) | GPL-3.0-or-later | https://github.com/SagerNet/sing-box/releases/tag/v1.14.4 — complete corresponding source is available at this link, unmodified |

## DNS-tunnel engines & thefeed (built from upstream source at pinned commits)
| Component | License | Source |
|---|---|---|
| MasterDnsVPN | MIT · © Amin Mahmoudi | https://github.com/masterking32/MasterDnsVPN (5f83ee9a) |
| StormDNS | MIT · © NullRoute1970 | https://github.com/NullRoute1970/StormDNS (a9a8e92a) |
| CottenDNS | MIT · © tajirax / WhiteDNS | https://github.com/WhiteDNS/CottenDNS (7db7b736) |
| Soar | Apache-2.0 · © Lantern / getlantern | https://github.com/getlantern/soar (v0.2.3) |
| thefeed | MIT · © sartoopjj | https://github.com/sartoopjj/thefeed (12512431) |
| jsQR | Apache-2.0 · © Cosmo Wolfe | https://github.com/cozmo/jsQR |

The engines run as separate programs inside the app. Their full license texts are in the linked repositories (MIT: https://opensource.org/license/mit · Apache-2.0: https://www.apache.org/licenses/LICENSE-2.0). Modifications: small wrappers (soarsocks: SOCKS5 front-end for Soar; rsfeed: command-line reader for thefeed) — no changes to the upstream engines.
