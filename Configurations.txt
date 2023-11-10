SYSCTL CONFIGS
*/etc/sysctl.conf*
- net.ipv4.tcp_syncookies: Prevents DoS attacks
- net.ipv4.conf.all.rp_filter: Least to most strict
- net.ipv4.ip_forward: Packets traveling from one network to another
- net.ipv4.icmp_echo_ignore_all: when pinged, computers location in network revealed through response
- net.ipv4.tcp_rfc1337=1
- net.ipv4.conf.all.accept_redirects
- net.ipv4.conf.default.accept_redirects
- net.ipv4.conf.all.secure_redirects
- net.ipv4.conf.default.secure_redirects
- net.ipv6.conf.all.accept_redirects
- net.ipv6.conf.default.accept_redirects
