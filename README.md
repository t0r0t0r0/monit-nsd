# monit-nsd
<br>
<br>
## Requirement<br>
OS:<br>
  CentOS6<br>
<br>
Package:<br>
  monit-5.14-1.el6.x86_64<br>
  nagios-plugins-dig-2.0.3-3.el6.x86_64<br>
<br>
#Note
nsdのプロセス監視用<br>
<br>
monit の protocol dnsは<br>
dig . @127.0.0.1<br>
な上、nsdがservfail返してくるので監視には使えない。<br>
<br>
