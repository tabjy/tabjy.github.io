# Unblock Netease Music

The unblock-netease-music service tricks Netease server to think you are located in China mainland by adding a propriate `X-Forwarded-For` header to your requests.

## Get Started

Paste the following into your `hosts`:

```
138.197.141.210 music.163.com
138.197.141.210 ip.ws.126.net
0.0.0.0 	    music.httpdns.c.163.com
125.39.1.27 	m10.music.126.net
138.197.141.210	interface.music.163.com
```

Now, enjoy!