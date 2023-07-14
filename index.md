## Welcome to macskas's github pages

This is just a index page for some repository

## projects
### [NSCA-fast](https://github.com/macskas/nsca_fast)
_high traffic nsca server with worker and threadpool support for slow encryption methods. drop-in replacement for nsca._

### [Secure SSH-agent UI](https://github.com/macskas/SSHAgentSecureProxy)
_Secure SSH agent UI for linux/macos. Just a nodejs electron app. Asks permission for key signing, masks your key names on listing. Shortcuts to approve request. Temporary/permanent bypass, blocking. Can block request when you are idle. Notification rate limiting, etc. A more flexible replacement for yubikey/smartcards_

### [libnss-hosts2](https://github.com/macskas/libnss-hosts2)
_Alternate, secondary hosts file lookup. Can be helpful in docker where /etc/hosts cannot be renamed(safely modified). Secondary hosts file's path can be configured. After install it should be added to /etc/nsswitch.conf_

### [nagios-plugins](https://github.com/macskas/nagios-plugins)
- ZFS `WARNING storage-02(ONLINE 11.1T/87T),storage-03(RESILVER 18.53%,223M/s,82h51m),storage-81(ONLINE 1.00T/87T)`
- Bacula status `pass_Bacula CRITICAL: Success: 75, Failed: 3 (Job1AutoMysqlBackupDaily, Job2AutoMysqlBackupDaily, Job3BackupDaily)`
- Open file handles `pass_ProcFD CRITICAL: (W:sshd;3148;11/1024), (C:syslog-ng;7486;2004/65536), (W:udevd;1529;11/1024), (W:lldpd;7063;14/1024), (W:rpcbind;6170;12/1024), (C:rpc.mountd;16466;21/1024)`

### [tcpdump-u32-helper](https://macskas.github.io/tcpdump-u32-helper/)
_You can generate iptables u32 match from tcpdump's output. Just a helper script in html+javascript_

### [nagios2json](https://github.com/macskas/nagios2json)
_Convert nagios status.dat to JSON, JSONP, TEXT format. Supports running as CGI or even CLI_

### [Microsoft RRAS ACL export](https://github.com/macskas/nps-rras-aclexport)
_If you want to migrate from windows RRAS to anything, first you have to export the firewall ACLs in grepable format so you can import it into iptables/etc_

### [Google Sheets to IPSET import](https://github.com/macskas/googlesheets-ipset-import)
_Import ip addresses from googlesheet into an ipset. You can grant roles to googlesheet columns, rows so its a basic ACL manager for lazy people._

### [GeoIP RIPE ipset](https://github.com/macskas/geoip-ripe-ipset)
_Its 2020. GeoIP csv is not available. So use RIPE database + ipset instead of geoip ipset module._

### [ssh-agent sign messages CLI](https://github.com/macskas/ssh-agent-sign-cli)
_With this tool you can use your existing ssh-agent to authenticate in your internal API-s, etc. So you dont have to write usernames/password._
example:
```# perl ssh-sign.pl -m test # encrypt the string "test"
542eac4bb60e9502a167803a02c2aa61:2156acafa7a23395cd69549e8806bbda9c0d687073742a0c09fced7749e3cf6012ceed9733b39afc3fc57ece03806ccc921121c9d8a27140d3aab0b93ae1bf48d9949a8705be5fe05b6fb8e8044dd05ea97b099e717e0d1390ba687b22726f21c68cd5268c005c2aa5f542d453c4cc1ed11c0506a7d7a51214ee8ae874e58f5562364371cafd2371706bc3f1d36c525e67b0a074bceaaa0924e99bcad5030065c181c58c36d5ac2ab88d25c77646020254eeb14fdfbc9562e959969c9ff1a36992d70bfb312aee15c34e3019cddfa47afc65e8dfeaad4b408388361f4afad9c084909653d1f2fad487b04dc214e44bde6f4192328e846f5a3600e97352c4969c
bf2b4508482c99becadb1c789399640c:0e8d68b9eff4c266cd562014dbe67d1a6591219212c8149da1e405b9c018e8a475bc92114ff520cd3af785036b7335026e7e50c04313deb13147ab6c042294feb2b6cab767a44cd98eae82e3402126dde1e26f1718339063910f649c7e62fedb586e77c4e71a0eb38cb5043e3bb21ac3b55e8e3a9917e40aab0b98c4e7ac7b27080d717750ef1d3532703e20432d31a36056862ecb9a90d19eadb17c5605c770a0e1cafaf7415500817e24e376bab43f0dcc1bde58387dc258673e3aed1cc9fc8ada2b33e87770234e5e9a709ecb5ab1ee111f4623e68d613a0f77241c1fea67442fd29ac8a42ae3c464a84057a2b7145396de215c6ada29b8b213e23def6ead
```

### [autobarebackup](https://github.com/macskas/autobarebackup)
_just a simple incremental backup script for linux using tar pigz, etc - useful for bacula_

### [autoinnodbbackup](https://github.com/macskas/autoinnodbbackup)
_automysqlbackup innobackupex alternative. for easy bacula backup_

### [docker-php-runner](https://github.com/macskas/DockerRunnerBasic)
_Just a basic docker exec replacement for multi php and multiuser environment(like shared dev servers)._

### [NGINX openresty dynamic SSL](https://github.com/macskas/nginx-openresty-dynamic-ssl)
_nginx openresty dynamic ssl lua script + cache_

### [PPTP classless route helper](https://github.com/macskas/pptp-route-helper)
_Linux PPTP ip-up.d helper for automatic DHCP classless routes_

### [percona audit module syslog aggregator](https://github.com/macskas/percona-audit-aggregator-perl)
_percona audit connect log syslog aggregator_

