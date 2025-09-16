# singbox-geo
SingBox GeoFiles Hosted &amp; Updated By GitHub

```
{
  "rules": [
    {
      "protocol": "dns",
      "action": "hijack-dns"
    },
    {
      "rule_set": [
        "geosite-private",
        "geosite-ir",
        "geoip-ir",
        "geoip-private"
      ],
      "action": "route",
      "outbound": "direct"
    },
    {
      "rule_set": [
        "geosite-ads"
      ],
      "action": "reject"
    }
  ],
  "rule_set": [
    {
      "tag": "geosite-ads",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/meta-rules-dat-sing/category-ads-all.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geosite-private",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/meta-rules-dat-sing/private-geosite.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geosite-ir",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/meta-rules-dat-sing/category-ir.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geoip-private",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/meta-rules-dat-sing/private-geoip.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geoip-ir",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/meta-rules-dat-sing/ir.srs",
      "download_detour": "direct"
    }
  ],
```
Or,
```
{
  "rules": [
    {
      "protocol": "dns",
      "action": "hijack-dns"
    },
    {
      "rule_set": [
        "geosite-private",
        "geosite-ir",
        "geoip-ir",
        "geoip-private"
      ],
      "action": "route",
      "outbound": "direct"
    },
    {
      "rule_set": [
        "geosite-ads"
      ],
      "action": "reject"
    }
  ],
  "rule_set": [
    {
      "tag": "geosite-ads",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/armv8/wp-caa.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geosite-private",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/armv8/wp-pgs.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geosite-ir",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/armv8/wp-ci.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geoip-private",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/armv8/wp-pgp.srs",
      "download_detour": "direct"
    },
    {
      "tag": "geoip-ir",
      "type": "remote",
      "format": "binary",
      "url": "https://github.com/ErfanNamira/armv8/raw/refs/heads/main/armv8/wp-ir.srs",
      "download_detour": "direct"
    }
  ],
```
