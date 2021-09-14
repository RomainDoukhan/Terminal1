Last login: Tue Sep 14 19:29:20 on ttys000

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
[romaindoukhan@macbook-air-de-romain] ~ $ ls
 Applications            Library   'Soulseek Chat Logs'
'Creative Cloud Files'   Movies    'Soulseek Downloads'
 Desktop                 Music     'iCloud Drive (archive)'
 Documents               Pictures
 Downloads               Public
[romaindoukhan@macbook-air-de-romain] ~ $ ls .
 Applications            Library   'Soulseek Chat Logs'
'Creative Cloud Files'   Movies    'Soulseek Downloads'
 Desktop                 Music     'iCloud Drive (archive)'
 Documents               Pictures
 Downloads               Public
[romaindoukhan@macbook-air-de-romain] ~ $ ls -a
 .                     .bashrc                 Library
 ..                    .cups                   Movies
 .CFUserTextEncoding   .local                  Music
 .DS_Store             .vscode                 Pictures
 .SoulseekQt           Applications            Public
 .Trash               'Creative Cloud Files'  'Soulseek Chat Logs'
 .bash_history         Desktop                'Soulseek Downloads'
 .bash_profile         Documents              'iCloud Drive (archive)'
 .bash_sessions        Downloads
[romaindoukhan@macbook-air-de-romain] ~ $ ls Pictures
'Bibliothèque Photo Booth'  'Open de Meru 2012-2013-2014'   Portraits
"Fonds d'écran"              Photothèque.photoslibrary
[romaindoukhan@macbook-air-de-romain] ~ $ ls ./Pictures
'Bibliothèque Photo Booth'  'Open de Meru 2012-2013-2014'   Portraits
"Fonds d'écran"              Photothèque.photoslibrary
[romaindoukhan@macbook-air-de-romain] ~ $ ls /users/romaindoukhan
 Applications            Library   'Soulseek Chat Logs'
'Creative Cloud Files'   Movies    'Soulseek Downloads'
 Desktop                 Music     'iCloud Drive (archive)'
 Documents               Pictures
 Downloads               Public
[romaindoukhan@macbook-air-de-romain] ~ $ ls /users
Guest  Shared  romain  romaindoukhan
[romaindoukhan@macbook-air-de-romain] ~ $ ls ..
Guest  Shared  romain  romaindoukhan
[romaindoukhan@macbook-air-de-romain] ~ $ ls /bin
'['      cp     dd     expr       launchctl   mkdir   pwd     sleep   test
 bash    csh    df     hostname   link        mv      rm      stty    unlink
 cat     dash   echo   kill       ln          pax     rmdir   sync    wait4path
 chmod   date   ed     ksh        ls          ps      sh      tcsh    zsh
[romaindoukhan@macbook-air-de-romain] ~ $ ls -l /bin
total 4700
-rwxr-xr-x 1 root wheel  121120 jan  1  2020 '['
-r-xr-xr-x 1 root wheel 1296704 jan  1  2020  bash
-rwxr-xr-x 1 root wheel  121984 jan  1  2020  cat
-rwxr-xr-x 1 root wheel  107552 jan  1  2020  chmod
-rwxr-xr-x 1 root wheel  123264 jan  1  2020  cp
-rwxr-xr-x 1 root wheel 1106144 jan  1  2020  csh
-rwxr-xr-x 1 root wheel  277440 jan  1  2020  dash
-rwxr-xr-x 1 root wheel  139312 jan  1  2020  date
-rwxr-xr-x 1 root wheel  122144 jan  1  2020  dd
-rwxr-xr-x 1 root wheel  121840 jan  1  2020  df
-rwxr-xr-x 1 root wheel  120848 jan  1  2020  echo
-rwxr-xr-x 1 root wheel  205648 jan  1  2020  ed
-rwxr-xr-x 1 root wheel  121504 jan  1  2020  expr
-rwxr-xr-x 1 root wheel  120864 jan  1  2020  hostname
-rwxr-xr-x 1 root wheel  121232 jan  1  2020  kill
-r-xr-xr-x 1 root wheel 2585424 jan  1  2020  ksh
-rwxr-xr-x 1 root wheel  329344 jan  1  2020  launchctl
-rwxr-xr-x 1 root wheel  105136 jan  1  2020  link
-rwxr-xr-x 1 root wheel  105136 jan  1  2020  ln
-rwxr-xr-x 1 root wheel  157376 jan  1  2020  ls
-rwxr-xr-x 1 root wheel  104752 jan  1  2020  mkdir
-rwxr-xr-x 1 root wheel  106176 jan  1  2020  mv
-rwxr-xr-x 1 root wheel  291232 jan  1  2020  pax
-rwsr-xr-x 1 root wheel  173728 jan  1  2020  ps
-rwxr-xr-x 1 root wheel  120832 jan  1  2020  pwd
-rwxr-xr-x 1 root wheel  105984 jan  1  2020  rm
-rwxr-xr-x 1 root wheel  104368 jan  1  2020  rmdir
-rwxr-xr-x 1 root wheel  120912 jan  1  2020  sh
-rwxr-xr-x 1 root wheel  120784 jan  1  2020  sleep
-rwxr-xr-x 1 root wheel  138704 jan  1  2020  stty
-rwxr-xr-x 1 root wheel  120464 jan  1  2020  sync
-rwxr-xr-x 1 root wheel 1106144 jan  1  2020  tcsh
-rwxr-xr-x 1 root wheel  121120 jan  1  2020  test
-rwxr-xr-x 1 root wheel  105984 jan  1  2020  unlink
-rwxr-xr-x 1 root wheel  120752 jan  1  2020  wait4path
-rwxr-xr-x 1 root wheel 1347856 jan  1  2020  zsh
[romaindoukhan@macbook-air-de-romain] ~ $ pwd
/Users/romaindoukhan
[romaindoukhan@macbook-air-de-romain] ~ $ cd Pictures
[romaindoukhan@macbook-air-de-romain] ~/Pictures $ pwd
/Users/romaindoukhan/Pictures
[romaindoukhan@macbook-air-de-romain] ~/Pictures $ cd ..
[romaindoukhan@macbook-air-de-romain] ~ $ pwd
/Users/romaindoukhan
[romaindoukhan@macbook-air-de-romain] ~ $ cd /opt
[romaindoukhan@macbook-air-de-romain] /opt $ cd ../users/romaindoukhan
[romaindoukhan@macbook-air-de-romain] /users/romaindoukhan $ cd /usr/bin
[romaindoukhan@macbook-air-de-romain] /usr/bin $ ls
2to3-                     mdfind
2to3-2.7                  mdimport
AssetCacheLocatorUtil     mdls
AssetCacheManagerUtil     mdutil
AssetCacheTetheratorUtil  memory_pressure
BuildStrings              mesg
CpMac                     mg
DeRez                     mib2c
GetFileInfo               mib2c-update
IOAccelMemory             mig
IOMFB_FDR_Loader          mkbom
MergePef                  mkdep
MvMac                     mkfifo
ResMerger                 mklocale
Rez                       mktemp
RezDet                    mmroff
RezWack                   mnthome
SafeEjectGPU              moo-outdated
SetFile                   moo-outdated5.18
SplitForks                moose-outdated
UnRezWack                 moose-outdated5.18
a2p                       moose-outdated5.30
aa                        more
actool                    mp2bug
addftinfo                 msgs
afclip                    nano
afconvert                 native2ascii
afhash                    nbdst
afida                     nc
afinfo                    ncal
afktool                   ncctl
afmtodit                  ncdestroy
afplay                    ncinit
afscexpand                nclist
agentxtrap                ncurses5.4-config
agvtool                   neqn
alias                     net-server
app-sso                   net-server5.18
applesingle               net-server5.30
appletviewer              net-snmp-cert
apply                     net-snmp-config
apropos                   net-snmp-create-v3-user
apt                       nettop
ar                        newaliases
arch                      newgrp
as                        newproc.d
asa                       nfsstat
assetutil                 nice
at                        nl
atos                      nm
atq                       nmedit
atrm                      nohup
atsutil                   notifyutil
automator                 nroff
auval                     nscurl
auvaltool                 nslookup
avbdiagnose               nsupdate
avbutil                   objdump
avconvert                 ocspcheck
avmediainfo               od
avmetareadwrite           odutil
awk                       open
banner                    opendiff
base64                    opensnoop
basename                  openssl
bashbug                   orbd
batch                     osacompile
bc                        osadecompile
bg                        osalang
biff                      osascript
binhex                    otool
binhex.pl                 pack200
binhex5.18.pl             package-stash-conflicts
binhex5.30.pl             package-stash-conflicts5.18
bioutil                   package-stash-conflicts5.30
bison                     pagesize
bitesize.d                pagestuff
bputil                    par.pl
brctl                     par5.30.pl
bsdtar                    parl
bspatch                   parl5.30
bundle                    parldyn
bundler                   parldyn5.30
bunzip2                   passwd
bzcat                     paste
bzcmp                     patch
bzdiff                    pathchk
bzegrep                   pathopens.d
bzfgrep                   pbcopy
bzgrep                    pbpaste
bzip2                     pcap-config
bzip2recover              pcsctest
bzless                    perl
bzmore                    perl5.18
c++                       perl5.30
c++filt                   perlbug
c2ph                      perlbug5.18
c89                       perlbug5.30
c99                       perldoc
caffeinate                perldoc5.18
cal                       perldoc5.30
calendar                  perlivp
cancel                    perlivp5.18
cap_mkdb                  perlivp5.30
captoinfo                 perlthanks
cc                        perlthanks5.18
cd                        perlthanks5.30
certtool                  pfbtops
checknr                   pgrep
chflags                   phar
chfn                      phar.phar
chgrp                     php
chpass                    php-config
chsh                      phpize
cksum                     pic
clang                     pico
clang++                   piconv
clear                     piconv5.18
cmp                       piconv5.30
cmpdylib                  pidpersec.d
codesign                  pip3
codesign_allocate         pkgbuild
col                       pkill
colcrt                    pl
colldef                   pl2pm
colrm                     pl2pm5.18
column                    pl2pm5.30
comm                      plockstat
command                   pluginkit
compress                  plutil
compression_tool          pmset
config_data               pod2html
config_data5.30           pod2html5.18
corelist                  pod2html5.30
corelist5.18              pod2latex
corelist5.30              pod2man
cpan                      pod2man5.18
cpan2dist                 pod2man5.30
cpan5.18                  pod2readme
cpan5.30                  pod2readme5.18
cpanp                     pod2readme5.30
cpanp-run-perl            pod2text
cpio                      pod2text5.18
cpp                       pod2text5.30
cpu_profiler.d            pod2usage
cpuctl                    pod2usage5.18
cpuwalk.d                 pod2usage5.30
crc32                     podchecker
crc325.18                 podchecker5.18
crc325.30                 podchecker5.30
creatbyproc.d             podselect
crlrefresh                podselect5.18
crontab                   podselect5.30
csplit                    policytool
csreq                     post-grohtml
csrutil                   power_report.sh
ctags                     powermetrics
ctf_insert                pp
cu                        pp5.30
cups-config               ppdc
cupstestppd               ppdhtml
curl                      ppdi
curl-config               ppdmerge
cut                       ppdpo
cvaffinity                pr
cvcp                      pre-grohtml
cvmkdir                   priclass.d
cvmkfile                  pridist.d
dappprof                  printenv
dapptrace                 printf
db_archive                procsystime
db_checkpoint             productbuild
db_codegen                productsign
db_deadlock               profiles
db_dump                   prove
db_hotbackup              prove5.18
db_load                   prove5.30
db_printlog               psed
db_recover                psm
db_stat                   pstopdf
db_upgrade                pstruct
db_verify                 ptar
dbicadmin                 ptar5.18
dbicadmin5.18             ptar5.30
dbicadmin5.30             ptardiff
dbilogstrip               ptardiff5.18
dbilogstrip5.18           ptardiff5.30
dbilogstrip5.30           ptargrep
dbiprof                   ptargrep5.18
dbiprof5.18               ptargrep5.30
dbiprof5.30               pwhich
dbiproxy                  pwhich5.18
dbiproxy5.18              pwpolicy
dbiproxy5.30              pydoc
dc                        pydoc2.7
debinhex.pl               python
debinhex5.18.pl           python-config
debinhex5.30.pl           python2
defaults                  python2.7
delv                      python2.7-config
demandoc                  python3
desdp                     pythonw
diagnose-fu               pythonw2.7
diff                      qlmanage
diff3                     quota
diffstat                  rails
dig                       rake
dirname                   ranlib
dispqlen.d                rdoc
ditto                     read
dmc                       readlink
dns-sd                    rebase
drutil                    redo_prebinding
dscacheutil               refer
dscl                      renice
dserr                     reset
dsexport                  resolveLinks
dsimport                  rev
dsmemberutil              ri
dsymutil                  rmic
dtruss                    rmid
du                        rmiregistry
dwarfdump                 rpcgen
easy_install              rs
easy_install-2.7          rsync
egrep                     ruby
enc2xs                    rview
enc2xs5.18                rvim
enc2xs5.30                rwbypid.d
encguess                  rwbytype.d
encode_keychange          rwsnoop
env                       s2p
eqn                       safaridriver
erb                       sample
errinfo                   sampleproc
ex                        sandbox-exec
execsnoop                 say
expand                    sc_usage
expect                    scandeps.pl
extcheck                  scandeps5.18.pl
eyapp                     scandeps5.30.pl
eyapp5.18                 schemagen
eyapp5.30                 scp
false                     screen
fc                        script
fddist                    sdef
fdesetup                  sdiff
fg                        sdp
fgrep                     sdx
file                      security
filebyproc.d              sed
fileproviderctl           seeksize.d
filtercalltree            segedit
find                      seq
find2perl                 serialver
findrule                  servertool
findrule5.18              setregion
findrule5.30              setuids.d
finger                    sfltool
fixproc                   sftp
flex                      shar
flex++                    shasum
fmt                       shasum5.18
fold                      shasum5.30
fontrestore               shlock
footprint                 showmount
format-sql                sigdist.d
format-sql5.18            sips
from                      size
fs_usage                  slogin
funzip                    smbutil
fuser                     smtpd.py
fwkdp                     smtpd2.7.py
fwkpfv                    snfsdefrag
g++                       snmp-bridge-mib
gatherheaderdoc           snmpbulkget
gcc                       snmpbulkwalk
gcore                     snmpconf
gcov                      snmpdelta
gdiffmk                   snmpdf
gem                       snmpget
gen_bridge_metadata       snmpgetnext
gencat                    snmpinform
genstrings                snmpnetstat
getconf                   snmpset
getopt                    snmpstatus
getopts                   snmptable
git                       snmptest
git-receive-pack          snmptranslate
git-shell                 snmptrap
git-upload-archive        snmpusm
git-upload-pack           snmpvacm
gm4                       snmpwalk
gnumake                   sntp
gperf                     soelim
grep                      sort
grn                       sourcekit-lsp
grodvi                    spfd
groff                     spfd5.18
groffer                   spfd5.30
grog                      spfquery
grolbp                    spfquery5.18
grolj4                    spfquery5.30
grops                     splain
grotty                    splain5.18
groups                    splain5.30
gunzip                    split
gzcat                     sqlite3
gzexe                     ssh
gzip                      ssh-add
h2ph                      ssh-agent
h2ph5.18                  ssh-copy-id
h2ph5.30                  ssh-keygen
h2xs                      ssh-keyscan
h2xs5.18                  stapler
h2xs5.30                  stat
hash                      stringdups
hdid                      strings
hdiutil                   strip
hdxml2manxml              stty.pl
head                      stty5.18.pl
headerdoc2html            su
heap                      sudo
hexdump                   sum
hidutil                   sw_vers
hiutil                    swcutil
host                      swift
hostinfo                  swiftc
hotspot.d                 symbols
hpftodit                  symbolscache
hpmdiagnose               syscallbypid.d
htmltree                  syscallbyproc.d
htmltree5.18              syscallbysysc.d
htmltree5.30              sysdiagnose
ibtool                    syslog
iconutil                  systemextensionsctl
iconv                     tab2space
ictool                    tabs
id                        tail
idle                      tailspin
idle2.7                   talk
idlj                      tar
imptrace                  taskinfo
indent                    tbl
indxbib                   tbtdiagnose
info                      tccutil
infocmp                   tclsh
infokey                   tclsh8.5
infotocap                 tee
install                   test-yaml
install-info              test-yaml5.30
install_name_tool         texi2dvi
instmodsh                 texi2pdf
instmodsh5.18             texindex
instmodsh5.30             textutil
instruments               tfmtodit
iofile.d                  tftp
iofileb.d                 thermal
iopattern                 tic
iopending                 tidy
iosnoop                   tidy_changelog
iotop                     tidy_changelog5.30
ip2cc                     tiff2icns
ip2cc5.18                 tiffutil
ip2cc5.30                 time
ipcount                   timer_analyser.d
ipcount5.18               timerfires
ipcount5.30               timesyncanalyse
ipcrm                     tkcon
ipcs                      tkmib
ippeveprinter             tkpp
ippfind                   tkpp5.30
ipptool                   tmdiagnose
iprofiler                 tmutil
iptab                     tnameserv
iptab5.18                 toe
iptab5.30                 top
irb                       tops
jar                       topsyscall
jarsigner                 topsysproc
java                      touch
javac                     tput
javadoc                   tr
javah                     trace
javap                     traptoemail
javapackager              treereg
javaws                    treereg5.18
jcmd                      treereg5.30
jconsole                  trimforce
jcontrol                  troff
jdb                       true
jdeps                     trustcachectl
jhat                      tset
jhsdb                     tsort
jimage                    tty
jinfo                     type
jjs                       ul
jlink                     ulimit
jmap                      umask
jmc                       unalias
jobs                      uname
join                      uncompress
jot                       unexpand
jpackage                  unifdef
jps                       unifdefall
jrunscript                uniq
jsadebugd                 units
jshell                    unpack200
json_pp                   unvis
json_pp5.18               unzip
json_pp5.30               unzipsfx
json_xs                   update_dyld_shared_cache
json_xs5.30               update_dyld_shared_cache_root_mode
jstack                    update_mcdp29xx
jstat                     uptime
jstatd                    usbcfwflasher
jvisualvm                 users
kcc                       uttype
kdestroy                  uucp
kextutil                  uudecode
keytool                   uuencode
kgetcred                  uuidgen
kill.d                    uulog
killall                   uuname
kinit                     uupick
klist                     uustat
kmutil                    uuto
kpasswd                   uux
krb5-config               vi
kswitch                   view
ktrace                    vim
lam                       vimdiff
last                      vimtutor
lastcomm                  vis
lastwords                 vm_stat
latency                   vmmap
layerutil                 vtool
ld                        w
ldapadd                   wait
ldapcompare               wall
ldapdelete                wc
ldapexop                  wdutil
ldapmodify                what
ldapmodrdn                whatis
ldappasswd                whereis
ldapsearch                which
ldapurl                   who
ldapwhoami                whoami
leaks                     whois
leave                     wish
less                      wish8.5
lessecho                  write
lex                       wsgen
libnetcfg                 wsimport
libnetcfg5.18             xar
libnetcfg5.30             xargs
libtool                   xattr
lipo                      xattr-2.7
lkbib                     xcode-select
lldb                      xcodebuild
llvm-g++                  xcrun
llvm-gcc                  xcscontrol
loads.d                   xcsdiagnose
locale                    xed
localedef                 xgettext.pl
locate                    xgettext5.18.pl
lockstat                  xgettext5.30.pl
log                       xip
logger                    xjc
login                     xml2-config
logname                   xml2man
look                      xmlcatalog
lookbib                   xmllint
lorder                    xpath
lp                        xpath5.18
lpoptions                 xpath5.30
lpq                       xslt-config
lpr                       xsltproc
lprm                      xsubpp
lpstat                    xsubpp5.18
lsappinfo                 xsubpp5.30
lsbom                     xxd
lskq                      yaa
lsm                       yacc
lsmp                      yamlpp-events
lsvfs                     yamlpp-events5.30
lwp-download              yamlpp-highlight
lwp-download5.18          yamlpp-highlight5.30
lwp-download5.30          yamlpp-load
lwp-dump                  yamlpp-load-dump
lwp-dump5.18              yamlpp-load-dump5.30
lwp-dump5.30              yamlpp-load5.30
lwp-mirror                yamlpp-parse-emit
lwp-mirror5.18            yamlpp-parse-emit5.30
lwp-mirror5.30            yapp
lwp-request               yapp5.30
lwp-request5.18           yes
lwp-request5.30           zcat
m4                        zcmp
macbinary                 zdiff
macerror                  zegrep
macerror5.18              zfgrep
macerror5.30              zforce
machine                   zgrep
mail                      zip
mailq                     zipcloak
mailx                     zipdetails
make                      zipdetails5.18
makeinfo                  zipdetails5.30
malloc_history            zipgrep
man                       zipinfo
mandoc                    zipnote
mandoc_soelim             zipsplit
manpath                   zless
mcxquery                  zmore
mcxrefresh                znew
mddiagnose                zprint
[romaindoukhan@macbook-air-de-romain] /usr/bin $ cd
[romaindoukhan@macbook-air-de-romain] ~ $ pwd
/Users/romaindoukhan
[romaindoukhan@macbook-air-de-romain] ~ $ cd -
/usr/bin
[romaindoukhan@macbook-air-de-romain] /usr/bin $ pwd
/usr/bin
[romaindoukhan@macbook-air-de-romain] /usr/bin $ cd -/Music
-bash: cd: -/: invalid option
cd: usage: cd [-L|-P] [dir]
[romaindoukhan@macbook-air-de-romain] /usr/bin $ 
