[core] and [extra] packages that failed to build see branches for fixes
| Package               | Status | Notes                                                                                       |
|-----------------------|--------|---------------------------------------------------------------------------------------------|
|bigloo                 |✓       |bigloo 4.4c_4-1                                                                              |
|dump_syms              |✓       |dump_syms 1.0.1-1                                                                            |
|efitools               |✓       |efitools 1.9.2-4                                                                             |
|falkon                 |✓       |falkon 3.2.0-1                                                                               |
|kopete                 |Fixable |Add -DWITH_libjingle:BOOL=OFF or custom patch                                                |
|krb5                   |✓       |krb5 1.20-1                                                                                  |
|libarchive             |✓       |libarchive 3.6.1-1                                                                           |
|libetebase             |✓       |libetebase 0.5.2-1                                                                           |
|libevent               |Fixable |patch based on https://github.com/libevent/libevent/pull/1288                                |
|lighttpd               |✓       |lighttpd 1.4.65-1                                                                            |
|lynx                   |✓       |lynx 2.8.9-5                                                                                 |
|mariadb                |✓       |mariadb 10.8.3-1                                                                             |
|openvpn                |✓       |openvpn 2.5.7-1                                                                              |
|openssl-1.0            |X       |Fixed build failure. Drop package?                                                           |
|perl-crypt-openssl-rsa |✓       |perl-crypt-openssl-rsa 0.33-1                                                                |
|perl-net-ssleay        |✓       |perl-net-ssleay 1.92-1                                                                       |
|pgbouncer              |✓       |pgbouncer 1.17.0-1                                                                           |
|php7                   |Fixable |https://github.com/php/php-src/commit/a0972deb0f441fc7991001cb51efc994b70a3b51               |
|postgresql             |✓       |postgresql 13.5-1                                                                            |
|python2                |-       |No longer packaged                                                                           |
|ruby                   |Fixable |Use 3.0 version of openssl gem ( now in community )                                          |
|sbsigntools            |Fixable |https://groups.io/g/sbsigntools/message/54 CFLAGS+=' -Wno-error=deprecated-declarations'     |
|socat                  |✓       |socat 1.7.4.3-1                                                                              |
|spice                  |Fixable |https://gitlab.freedesktop.org/spice/spice/-/commit/3d32295f9e99054ae1a40d220ccef53a176c8aed |
|systemd                |Fixable |Requires depends to be rebuilt                                                               |
|transmission           |✓       |transmission-cli 3.00-3                                                                      |
|vde2                   |✓       |vde2 2.3.2-19                                                                                |
|xmlsec                 |✓       |xmlsec 1.2.35-1                                                                              |

[community] packages that failed to build see branches for fixes
| Package           | Status | Notes                                                                                                                                                   |
|-------------------|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
|acme-redirect      |Fixable |FS#73628 LTO                                                                                                                                             |
|aircrack-ng        |✓       |aircrack-ng 1.7-1                                                                                                                                        |
|arrow              |✓       |arrow-6.0.1-7                                                                                                                                            |
|authoscope         |✓       |authoscope 0.8.1-1                                                                                                                                       |
|aws-sdk-cpp        |✓       |aws-sdk-cpp 1.9.334-1                                                                                                                                    |
|boinc              |✓       |boinc 7.20.2-1                                                                                                                                           |
|boinctui           |✓       |boinctui 2.5.2-1                                                                                                                                         |
|cargo-audit        |✓       |cargo-audit 0.17.0-1                                                                                                                                     |
|cargo-edit         |✓       |cargo-edit 0.9.0-1                                                                                                                                       |
|cargo-outdated     |✓       |cargo-outdated 0.10.2-2                                                                                                                                  |
|ceph               |✓       |ceph 15.2.14-6                                                                                                                                           |
|clevis             |✓       |Fixed in trunk                                                                                                                                           |
|coturn             |Fixable |https://github.com/coturn/coturn/issues/886 https://github.com/coturn/coturn/commit/4ce784a8781ab086c150e2b9f5641b1a37fd9b31                             |
|dbmail             |✓       |dbmail 3.2.6-2                                                                                                                                           |
|deepin-file-manager|✓       |deepin-file-manager 5.5.10-3                                                                                                                             |
|dog                |Fixable |https://github.com/ogham/dog/issues/98 custom patch                                                                                                      |
|dovecot            |Fixable |https://src.fedoraproject.org/rpms/dovecot/raw/rawhide/f/dovecot-2.3.14-opensslv3.patch https://dovecot.org/pipermail/dovecot/2022-June/124877.html      |
|dotnet-core        |✓       |dotnet-core 6.0.2.sdk102                                                                                                                                 |
|dotnet-core-3.1    |✓       |No longer packaged                                                                                                                                       |
|dsniff             |Fixable |FS#72121 needs aditional patch                                                                                                                           |
|echoping           |Fixable |FS#73709 LTO                                                                                                                                             |
|epic4              |✓       |epic4 2.10.10-3                                                                                                                                          |
|exim               |✓       |exim 4.96-1                                                                                                                                              |
|fractal            |Fixable |FS#76217 FTBFS                                                                                                                                           |
|fragments          |✓       |fragments 2.0.2-1                                                                                                                                        |
|freeradius         |✓       |freeradius 3.2.0-1                                                                                                                                       |
|git-crypt          |Fixable |https://github.com/AGWA/git-crypt/issues/232 https://github.com/AGWA/git-crypt/pull/249                                                                  |
|gitlab             |Fixable |Update webauthn webauthn Ruby Gem for OpenSSL 3.0 https://gitlab.com/gitlab-org/gitlab/-/issues/341435                                                   |
|gnome-podcasts     |✓       |gnome-podcasts 0.5.1-1                                                                                                                                   |
|gogglesmm          |✓       |gogglesmm 1.2.2-2                                                                                                                                        |
|httping            |Fixable |FS#71981 upstream removed source                                                                                                                         |
|hydra              |✓       |hydra 9.3-1                                                                                                                                              |
|ibm-sw-tpm2        |✓       |Fixed in trunk                                                                                                                                           |
|jose               |?       |Builds for me                                                                                                                                            |
|kodi               |✓       |kodi 19.3-3                                                                                                                                              |
|lua-luaossl        |✓       |lua-luaossl 20220711-1                                                                                                                                   |
|mtd-utils          |✓       |mtd-utils 2.1.4-1                                                                                                                                        |
|mumble             |Fixable |https://github.com/mumble-voip/mumble/commit/f4cea62ed95e4967d8591f25e903f5e8fc2e2a30                                                                    |
|mysql-workbench    |✓       |mysql-workbench 8.0.30-1                                                                                                                                 |
|newsflash          |✓       |newsflash-1.5.1-1                                                                                                                                        |
|nextcloud-client   |?       |Builds for me                                                                                                                                            |
|nodejs             |✓       |nodejs 17.3.1-1                                                                                                                                          |
|nodejs-lts-erbium  |-       |No longer packaged                                                                                                                                       |
|nodejs-lts-fermium |X       |needs -fpermissive to build. Fails check. Use openssl 1.1 Drop package and move reverse depends to nodejs-lts-gallium when possible.                     |
|nrpe               |✓       |nrpe 4.1.0-1                                                                                                                                             |
|ntp                |Fixable |FS#74690 needs patch for glibc 2.34+                                                                                                                     |
|nut                |✓       |nut 2.8.0-1                                                                                                                                              |
|nzbget             |Fixable |https://github.com/nzbget/nzbget/pull/793                                                                                                                |
|opendkim           |✓       |opendkim 2.11.0beta-2                                                                                                                                    |
|openrct2           |✓       |openrct2-0.4.0-1                                                                                                                                         |
|opensc             |✓       |In trunk                                                                                                                                                 |
|opensips           |✓       |opensips 3.2.6-1                                                                                                                                         |
|partclone          |✓       |partclone 0.3.19-1                                                                                                                                       |
|percona-server     |✓       |percona-server 8.0.29_21-2                                                                                                                               |
|powerdns-recursor  |✓       |powerdns-recursor 4.6.0-3                                                                                                                                |
|pypy               |✓       |pypy 7.3.8-1                                                                                                                                             |
|pypy3              |✓       |pypy3 7.3.8-1                                                                                                                                            |
|qpid-proton        |Fixable |https://github.com/apache/qpid-proton/commit/5aaa655cb1023e9fb48e59f64e3d0c1307ea54f2  https://issues.apache.org/jira/projects/PROTON/issues/PROTON-2544 |
|rathole            |✓       |rathole 0.3.10-1                                                                                                                                         |
|rebuilderd         |✓       |rebuilderd-0.19.0-1                                                                                                                                      |
|rink               |✓       |rink 0.6.3-1                                                                                                                                             |
|ruby2.7            |Fixable |Use 3.0.0 version of openssl gem                                                                                                                         |
|rustup             |✓       |rustup 1.25.0-1                                                                                                                                          |
|s2n-tls            |✓       |s2n-tls 1.3.24-1                                                                                                                                         |
|sccache            |✓       |sccache 0.3.0-1                                                                                                                                          |
|sequoia            |✓       |In trunk                                                                                                                                                 |
|sequoia-sq         |✓       |sequoia-sq 0.26.0-1                                                                                                                                      |
|shairport-sync     |✓       |shairport-sync 3.3.9-1                                                                                                                                   |
|softhsm            |Fixable |Fails check fixed upstream by https://github.com/opendnssec/SoftHSMv2/pull/633                                                                           |
|spotifyd           |✓       |In trunk                                                                                                                                                 |
|sqlx-cli           |✓       |sqlx-cli 0.5.10-1                                                                                                                                        |
|squid              |✓       |squid 5.7-1                                                                                                                                              |
|sscg               |✓       |sscg 3.0.2-1                                                                                                                                             |
|sslsplit           |Fixable |https://github.com/droe/sslsplit/commit/e17de8454a65d2b9ba432856971405dfcf1e7522 https://github.com/droe/sslsplit/issues/290                             |
|tarantool          |✓       |tarantool 2.9.0-3                                                                                                                                        |
|tcpflow            |Fixable |FS#74209 format security                                                                                                                                 |
|telegram           |?       |Probably related to the ffmpeg update,  builds for me.                                                                                                   |
|tensorflow         |✓       |tensorflow 2.8.0-1                                                                                                                                       |
|torrential         |✓       |torrential 2.0.1-1                                                                                                                                       |
|tpm2-pkcs11        |-       |diabonas:needs python-tpm2-pytss 1.1.0-rc1 and tpm2-openssl 1.1.0, otherwise tests fail. with upgraded packages everything works fine                    |
|tpm2-tools         |-       |diabonas:works for me                                                                                                                                    |
|tpm2-tss           |-       |diabonas:works for me (also this package is now in [core])                                                                                               |
|tpm2-tss-engine    |-       |diabonas:fixed in trunk; also OpenSSL engines are deprecated, so this package should be replaced by tpm2-openssl once OpenSSL 3.0 is in the repos        |
|umurmur            |Fixable |https://github.com/umurmur/umurmur/issues/176 sed -i 's/CRYPTO_mem_ctrl(CRYPTO_MEM_CHECK_ON);//' src/ssli_openssl.c                                      |
|virtualbox         |Fixable |requires depends to be rebuilt possible issue with gsoap and exported symbols when built using lto                                                       |
|wvstreams          |✓       |wvstreams 4.6.1-19                                                                                                                                       |
|xca                |Fixable |https://github.com/chris2511/xca/commit/f5ac099e948ea354deac75ff9fa09d51453476e1 https://github.com/chris2511/xca/issues/320                             |
|xrootd4            |✓       |No longer packaged                                                                                                                                       |
|xtrabackup         |Fixable |https://github.com/percona/percona-server/commit/6076ab35b961d543969abd0610419f3c2bb3ba50 upstream support expected in 8.0.30                            |


> Written with [StackEdit](https://stackedit.io/).
