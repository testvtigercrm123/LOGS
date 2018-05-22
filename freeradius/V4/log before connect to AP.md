```bash
 # radiusd -XxXxXx
Tue May 22 11:46:01 2018 : Debug : Server was built with: 
Tue May 22 11:46:01 2018 : Debug :   accounting               : yes
Tue May 22 11:46:01 2018 : Debug :   authentication           : yes
Tue May 22 11:46:01 2018 : Debug :   ascend-binary-attributes : yes
Tue May 22 11:46:01 2018 : Debug :   coa                      : yes
Tue May 22 11:46:01 2018 : Debug :   control-socket           : yes
Tue May 22 11:46:01 2018 : Debug :   detail                   : yes
Tue May 22 11:46:01 2018 : Debug :   dhcp                     : yes
Tue May 22 11:46:01 2018 : Debug :   dynamic-clients          : yes
Tue May 22 11:46:01 2018 : Debug :   osfc2                    : no
Tue May 22 11:46:01 2018 : Debug :   proxy                    : yes
Tue May 22 11:46:01 2018 : Debug :   regex-pcre               : no
Tue May 22 11:46:01 2018 : Debug :   regex-posix              : yes
Tue May 22 11:46:01 2018 : Debug :   regex-posix-extended     : yes
Tue May 22 11:46:01 2018 : Debug :   stats                    : yes
Tue May 22 11:46:01 2018 : Debug :   tcp                      : yes
Tue May 22 11:46:01 2018 : Debug :   threads                  : no
Tue May 22 11:46:01 2018 : Debug :   tls                      : yes
Tue May 22 11:46:01 2018 : Debug :   tls-key-agility          : yes
Tue May 22 11:46:01 2018 : Debug :   unlang                   : yes
Tue May 22 11:46:01 2018 : Debug :   vmps                     : yes
Tue May 22 11:46:01 2018 : Debug :   socket-timestamps        : yes
Tue May 22 11:46:01 2018 : Debug :   developer                : yes
Tue May 22 11:46:01 2018 : Debug :   address-sanitizer        : no
Tue May 22 11:46:01 2018 : Debug :   runtime-debugger         : no
Tue May 22 11:46:01 2018 : Debug : Server core libs:
Tue May 22 11:46:01 2018 : Debug :   freeradius-server        : 4.0.0
Tue May 22 11:46:01 2018 : Debug :   talloc                   : 2.0.*
Tue May 22 11:46:01 2018 : Debug :   ssl                      : 1.1.0h release
Tue May 22 11:46:01 2018 : Debug : OpenSSL engines:
Tue May 22 11:46:01 2018 : Debug :   rdrand                   : Intel RDRAND engine
Tue May 22 11:46:01 2018 : Debug :   dynamic                  : Dynamic engine loading support
Tue May 22 11:46:01 2018 : Debug : Endianness:
Tue May 22 11:46:01 2018 : Debug :   little
Tue May 22 11:46:01 2018 : Debug : Compilation flags:
Tue May 22 11:46:01 2018 : Debug :   cppflags :  -isystem /usr/include/kqueue/ 
Tue May 22 11:46:01 2018 : Debug :   cflags   : -I. -Isrc -include src/freeradius-devel/autoconf.h -include src/freeradius-devel/build.h -include src/freeradius-devel/features.h -include src/freeradius-devel/radpaths.h -fno-strict-aliasing -Wno-date-time -g3 -std=c11 -Wall -D_GNU_SOURCE -D_REENTRANT -D_POSIX_PTHREAD_SEMANTICS -pthread -DOPENSSL_NO_KRB5 -Wshadow -Wpointer-arith -Wcast-qual -Wcast-align -Wwrite-strings -Wstrict-prototypes -Wmissing-prototypes -Wmissing-declarations -Wnested-externs -W -Wredundant-decls -Wundef -Wformat-y2k -Wno-missing-field-initializers -Wno-format-extra-args -Wno-format-zero-length -Wno-cast-align -Wformat-nonliteral -Wformat-security -Wformat=2 -DWITH_VERIFY_PTR=1 -DWITH_OPENSSL_MD4 -DWITH_OPENSSL_MD5 -DIS_MODULE=1
Tue May 22 11:46:01 2018 : Debug :   ldflags  :  
Tue May 22 11:46:01 2018 : Debug :   libs     : -lcrypto -lssl -ltalloc -lkqueue -lcap -lrt -lnsl -lresolv -ldl -lpthread -lreadline
Tue May 22 11:46:01 2018 : Debug :   
Tue May 22 11:46:01 2018 : Info  : FreeRADIUS Version 4.0.0
Tue May 22 11:46:01 2018 : Info  : Copyright 1999-2018 The FreeRADIUS server project and contributors
Tue May 22 11:46:01 2018 : Info  : There is NO warranty; not even for MERCHANTABILITY or FITNESS FOR A
Tue May 22 11:46:01 2018 : Info  : PARTICULAR PURPOSE
Tue May 22 11:46:01 2018 : Info  : You may redistribute copies of FreeRADIUS under the terms of the
Tue May 22 11:46:01 2018 : Info  : GNU General Public License
Tue May 22 11:46:01 2018 : Info  : For more information about these matters, see the file named COPYRIGHT
Tue May 22 11:46:01 2018 : Info  : Starting - reading configuration files ...
Tue May 22 11:46:01 2018 : Debug : Including dictionary file "/usr/local/stow/freeradius-4/share/freeradius/dictionary"
Tue May 22 11:46:01 2018 : Debug : Including dictionary file "/usr/local/stow/freeradius-4/etc/raddb/dictionary"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: server {}
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/radiusd.conf"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/clients.conf"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Including files in directory "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unpack"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unix"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/client"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/digest"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/stats"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/soh"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/utf8"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/chap"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expr"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pap"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expiration"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/dhcpv4"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Including files in directory "/usr/local/stow/freeradius-4/etc/raddb/policy.d/"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/operator-name"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/control"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/debug"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/eap"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/dhcp"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/filter"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/vendor"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/abfab-tr"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/canonicalization"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/accounting"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/time"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/policy.d/cui"
Tue May 22 11:46:01 2018 : Debug : OPTIMIZING (${policy.cui_require_operator_name} == yes) --> FALSE
Tue May 22 11:46:01 2018 : Debug : OPTIMIZING (no == yes) --> FALSE
Tue May 22 11:46:01 2018 : Debug : OPTIMIZING (${policy.cui_require_operator_name} == yes) --> FALSE
Tue May 22 11:46:01 2018 : Debug : OPTIMIZING (no == yes) --> FALSE
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Including files in directory "/usr/local/stow/freeradius-4/etc/raddb/sites-enabled/"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel"
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Pushed parse rule to server section: server {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Pushed parse rule to listen section: listen {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Loading proto_radius
Tue May 22 11:46:01 2018 : Debug : Loading library using linker search path(s)
Tue May 22 11:46:01 2018 : Debug : Defaults         : /lib:/usr/lib
Tue May 22 11:46:01 2018 : Debug : proto_radius loaded, checking if it's valid
Tue May 22 11:46:01 2018 : Debug : proto_radius validated.  Handle address 0x2921910, symbol address 0x7fcd5d3cd780
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_dict found at 0x7fcd5d3cd700
Tue May 22 11:46:01 2018 : Debug : Loading dictionary proto_radius
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_dict_attr found at 0x7fcd5d3cd740
Tue May 22 11:46:01 2018 : Info  : src/main/cf_file.c[1511]: Loaded module "proto_radius"
Tue May 22 11:46:01 2018 : Debug : Including configuration file "/usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default"
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Pushed parse rule to server section: server {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Pushed parse rule to listen section: listen {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Loading proto_radius
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Pushed parse rule to listen section: listen {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_file.c[1511]: Loading proto_radius
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: security {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: name 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: prefix 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: localstatedir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: run_dir 
Tue May 22 11:46:01 2018 : Debug : Parsing security rules to bootstrap UID / GID / chroot / etc.
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: main {
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for security section.  Output (nil)
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: user 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: group 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: chroot 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: allow_core_dumps {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: allow_vulnerable_openssl 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: server_id {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]:   security {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]:     allow_core_dumps = no
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]:     allow_vulnerable_openssl = "no"
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[452]: The item 'max_attributes' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]:   }
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[57]: The item 'sbindir' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[67]: The item 'confdir' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[74]: The item 'db_dir' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[109]: The item 'libdir' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[120]: The item 'pidfile' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[174]: The item 'max_request_time' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[193]: The item 'max_requests' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[211]: The item 'hostname_lookups' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: }
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: prefix 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: localstatedir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: sbindir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: logdir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: run_dir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: libdir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: radacctdir 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: panic_action 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: hostname_lookups {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: max_request_time {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: continuation_timeout {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: max_requests {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: pidfile 
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: debug_level {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: log {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: resources {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: thread {}
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Pushed parse rule to main section: server {}
Tue May 22 11:46:01 2018 : Debug : Parsing main configuration.
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: main {
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for server[0] section.  Output 0x7fcd60b2a230
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[11]: Pushed parse rule to server section: namespace 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[11]: Pushed parse rule to server section: listen {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[11]:   server inner-tunnel {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[11]:     namespace = "radius"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[11]: Evaluating rules for listen[0] section.  Output 0x2844650
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Loading radius listener into 0x2844ce0
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Pushed parse rule to listen section: type {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Pushed parse rule to listen section: transport {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Pushed parse rule to listen section: tunnel_password_zeros {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Pushed parse rule to listen section: limit {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]:     listen {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]:       type = Access-Request
Tue May 22 11:46:01 2018 : Debug : Loading library using linker search path(s)
Tue May 22 11:46:01 2018 : Debug : Defaults         : /lib:/usr/lib
Tue May 22 11:46:01 2018 : Debug : proto_radius_auth loaded, checking if it's valid
Tue May 22 11:46:01 2018 : Debug : proto_radius_auth validated.  Handle address 0x2846800, symbol address 0x7fcd5cfae1a0
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_auth_dict not found
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_auth_dict_attr not found
Tue May 22 11:46:01 2018 : Info  : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Loaded module "proto_radius_auth"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]:       transport = tcp
Tue May 22 11:46:01 2018 : Debug : Loading library using linker search path(s)
Tue May 22 11:46:01 2018 : Debug : Defaults         : /lib:/usr/lib
Tue May 22 11:46:01 2018 : Debug : proto_radius_tcp loaded, checking if it's valid
Tue May 22 11:46:01 2018 : Debug : proto_radius_tcp validated.  Handle address 0x28473d0, symbol address 0x7fcd5cda8140
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_tcp_dict not found
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_tcp_dict_attr not found
Tue May 22 11:46:01 2018 : Info  : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Loaded module "proto_radius_tcp"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: ipaddr 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: ipv4addr {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: ipv6addr {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: interface 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: port_name 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: port {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: recv_buff {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: dynamic_clients {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: networks {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: max_packet_size {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Pushed parse rule to tcp section: max_attributes {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]:       tcp {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]:         ipaddr = 127.0.0.1
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]:         port = 18120
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Allocating fake section "networks"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]: Evaluating rules for networks section.  Output 0x2847b50
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to networks section: allow 
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to networks section: deny 
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         networks {
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]:         max_packet_size = 4096
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]:         max_attributes = 255
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[39]:       }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Allocating fake section "limit"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]: Evaluating rules for limit section.  Output 0x2844f00
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: cleanup_delay {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: nak_lifetime {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_clients {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_pending_packets {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_packet_size {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: num_messages {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:       limit {
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         cleanup_delay = 5.000000
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         idle_timeout = 30.000000
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         nak_lifetime = 30.000000
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         max_connections = 1024
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         max_clients = 256
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         max_pending_packets = 256
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[35]:     }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[11]:   }
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for server[1] section.  Output 0x7fcd60b2a230
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]: Pushed parse rule to server section: namespace 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]: Pushed parse rule to server section: listen {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]:   server default {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]:     namespace = "radius"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]: Evaluating rules for listen[0] section.  Output 0x2827e30
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Loading radius listener into 0x28284d0
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Pushed parse rule to listen section: type {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Pushed parse rule to listen section: transport {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Pushed parse rule to listen section: tunnel_password_zeros {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Pushed parse rule to listen section: limit {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]:     listen {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]:       type = Access-Request
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]:       type = Status-Server
Tue May 22 11:46:01 2018 : Debug : Loading library using linker search path(s)
Tue May 22 11:46:01 2018 : Debug : Defaults         : /lib:/usr/lib
Tue May 22 11:46:01 2018 : Debug : proto_radius_status loaded, checking if it's valid
Tue May 22 11:46:01 2018 : Debug : proto_radius_status validated.  Handle address 0x282a910, symbol address 0x7fcd5cba10c0
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_status_dict not found
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_status_dict_attr not found
Tue May 22 11:46:01 2018 : Info  : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Loaded module "proto_radius_status"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]:       transport = udp
Tue May 22 11:46:01 2018 : Debug : Loading library using linker search path(s)
Tue May 22 11:46:01 2018 : Debug : Defaults         : /lib:/usr/lib
Tue May 22 11:46:01 2018 : Debug : proto_radius_udp loaded, checking if it's valid
Tue May 22 11:46:01 2018 : Debug : proto_radius_udp validated.  Handle address 0x282b3e0, symbol address 0x7fcd5c99d160
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_udp_dict not found
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_udp_dict_attr not found
Tue May 22 11:46:01 2018 : Info  : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Loaded module "proto_radius_udp"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: ipaddr 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: ipv4addr {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: ipv6addr {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: interface 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: port_name 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: port {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: recv_buff {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: dynamic_clients {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: networks {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: max_packet_size {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Pushed parse rule to udp section: max_attributes {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]:       udp {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]:         ipaddr = *
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]:         port = 1812
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]: Evaluating rules for networks section.  Output 0x282bb60
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]: Pushed parse rule to networks section: allow 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]: Pushed parse rule to networks section: deny 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]:         networks {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]:           allow = 127/8
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]:           allow = 192.0.2/24
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]:           allow = 192.168.1.0/24
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[185]:         }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]:         max_packet_size = 4096
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]:         max_attributes = 255
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[159]:       }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]: Evaluating rules for limit section.  Output 0x28286f0
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: cleanup_delay {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: nak_lifetime {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: max_clients {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: max_pending_packets {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: max_packet_size {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]: Pushed parse rule to limit section: num_messages {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:       limit {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:         cleanup_delay = 5.000000
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:         idle_timeout = 60.000000
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:         nak_lifetime = 30.000000
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:         max_connections = 256
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:         max_clients = 256
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:         max_pending_packets = 256
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[78]:       }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[57]:     }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]: Evaluating rules for listen[1] section.  Output 0x2827e30
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Loading radius listener into 0x28304b0
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Pushed parse rule to listen section: type {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Pushed parse rule to listen section: transport {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Pushed parse rule to listen section: tunnel_password_zeros {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Pushed parse rule to listen section: limit {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]:     listen {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]:       type = Accounting-Request
Tue May 22 11:46:01 2018 : Debug : Loading library using linker search path(s)
Tue May 22 11:46:01 2018 : Debug : Defaults         : /lib:/usr/lib
Tue May 22 11:46:01 2018 : Debug : proto_radius_acct loaded, checking if it's valid
Tue May 22 11:46:01 2018 : Debug : proto_radius_acct validated.  Handle address 0x2831f60, symbol address 0x7fcd5c7970e0
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_acct_dict not found
Tue May 22 11:46:01 2018 : Debug : Symbol proto_radius_acct_dict_attr not found
Tue May 22 11:46:01 2018 : Info  : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Loaded module "proto_radius_acct"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]:       transport = udp
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: ipaddr 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: ipv4addr {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: ipv6addr {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: interface 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: port_name 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: port {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: recv_buff {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: dynamic_clients {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: networks {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: max_packet_size {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Pushed parse rule to udp section: max_attributes {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]:       udp {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]:         ipaddr = *
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]:         port = 1813
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Allocating fake section "networks"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]: Evaluating rules for networks section.  Output 0x293f910
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to networks section: allow 
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to networks section: deny 
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         networks {
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]:         max_packet_size = 4096
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]:         max_attributes = 255
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[269]:       }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Allocating fake section "limit"
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]: Evaluating rules for limit section.  Output 0x28306d0
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: cleanup_delay {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: nak_lifetime {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_clients {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_pending_packets {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_packet_size {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to limit section: num_messages {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:       limit {
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         cleanup_delay = 5.000000
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         idle_timeout = 30.000000
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         nak_lifetime = 30.000000
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         max_connections = 1024
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         max_clients = 256
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:         max_pending_packets = 256
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[263]:     }
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[44]:   }
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for security section.  Output 0x7fcd60b2a230
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: user 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: group 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: chroot 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: allow_core_dumps {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: allow_vulnerable_openssl 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]: Pushed parse rule to security section: server_id {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]:   security {
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[452]: The item 'max_attributes' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[370]:   }
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   sbindir = "/usr/local/stow/freeradius-4/sbin"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   libdir = "/usr/local/stow/freeradius-4/lib"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   hostname_lookups = no
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   max_request_time = 30
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   continuation_timeout = 15
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   max_requests = 16384
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   pidfile = "/usr/local/stow/freeradius-4/var/run/radiusd/radiusd.pid"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]:   debug_level = 0
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for log section.  Output 0x628ce8
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: stripped_names {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: auth {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: auth_badpass {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: auth_goodpass {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: msg_badpass 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: msg_goodpass 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: colourise {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: timestamp {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: use_utc {}
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]: Pushed parse rule to log section: msg_denied 
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:   log {
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     stripped_names = no
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     auth = yes
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     auth_badpass = yes
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     auth_goodpass = yes
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     colourise = yes
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     timestamp = yes
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:     msg_denied = "You are already logged in - access denied"
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[229]: The item 'destination' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[260]: The item 'file' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[268]: The item 'syslog_facility' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Debug : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[217]:   }
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Allocating fake section "resources"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for resources section.  Output 0x628ce8
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to resources section: talloc_pool_size {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to resources section: talloc_memory_limit {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to resources section: talloc_memory_report {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:   resources {
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:   }
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Allocating fake section "thread"
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: Evaluating rules for thread section.  Output 0x628ce8
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to thread section: num_networks {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]: Pushed parse rule to thread section: num_workers {}
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:   thread {
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:     num_networks = 1
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:     num_workers = 4
Tue May 22 11:46:01 2018 : Debug : src/main/cf_parse.c[893]:   }
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[67]: The item 'confdir' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Warn  : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[74]: The item 'db_dir' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : Debug : src/main/mainconfig.c[782]: }
Tue May 22 11:46:01 2018 : Switching to configured log settings
Tue May 22 11:46:01 2018 : radiusd: #### Loading Clients ####
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: ipv4addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: ipv6addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: src_ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: require_message_authenticator {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: secret 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: shortname 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: nas_type 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: response_window {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: track_connections {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: proto 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Pushed parse rule to client section: limit {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:   client localhost {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:     ipaddr = 127.0.0.1
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:     require_message_authenticator = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:     secret = "testing123"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:     nas_type = "other"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:     proto = "*"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]: Evaluating rules for limit section.  Output 0x294a440
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]: Pushed parse rule to limit section: lifetime {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]:     limit {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]:       max_connections = 16
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]:       lifetime = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]:       idle_timeout = 30
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[173]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[30]:   }
Tue May 22 11:46:01 2018 : Adding client 127.0.0.1/32 (127.0.0.1) to prefix tree 32
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: ipv4addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: ipv6addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: src_ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: require_message_authenticator {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: secret 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: shortname 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: nas_type 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: response_window {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: track_connections {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: proto 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Pushed parse rule to client section: limit {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]:   client office_cont-wifi {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]:     ipaddr = 192.168.1.2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]:     require_message_authenticator = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]:     secret = "tusWuw*E4um3vec"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Allocating fake section "limit"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]: Evaluating rules for limit section.  Output 0x294d610
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: lifetime {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:     limit {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       max_connections = 16
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       lifetime = 0
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       idle_timeout = 30
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[206]: The item 'require_message_authentificator' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[203]:   }
Tue May 22 11:46:01 2018 : Adding client 192.168.1.2/32 (192.168.1.2) to prefix tree 32
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: ipv4addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: ipv6addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: src_ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: require_message_authenticator {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: secret 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: shortname 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: nas_type 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: response_window {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: track_connections {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: proto 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Pushed parse rule to client section: limit {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]:   client office_dev-wifi {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]:     ipaddr = 192.168.1.3
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]:     require_message_authenticator = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]:     secret = "tusWuw*E4um3ve3"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Allocating fake section "limit"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]: Evaluating rules for limit section.  Output 0x2951890
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: lifetime {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:     limit {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       max_connections = 16
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       lifetime = 0
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       idle_timeout = 30
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[212]: The item 'require_message_authentificator' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[209]:   }
Tue May 22 11:46:01 2018 : Adding client 192.168.1.3/32 (192.168.1.3) to prefix tree 32
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: ipv4addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: ipv6addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: src_ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: require_message_authenticator {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: secret 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: shortname 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: nas_type 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: response_window {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: track_connections {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: proto 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Pushed parse rule to client section: limit {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]:   client localhost_ipv6 {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]:     ipv6addr = ::1
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]:     require_message_authenticator = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]:     secret = "testing123"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Allocating fake section "limit"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]: Evaluating rules for limit section.  Output 0x2955a30
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: max_connections {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: lifetime {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to limit section: idle_timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:     limit {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       max_connections = 16
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       lifetime = 0
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       idle_timeout = 30
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/clients.conf[216]:   }
Tue May 22 11:46:01 2018 : Adding client ::1/128 (::1) to prefix tree 128
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-0
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-1
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-2
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-3
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-4
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-5
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-6
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-7
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-8
Tue May 22 11:46:01 2018 : xlat_register: Foreach-Variable-9
Tue May 22 11:46:01 2018 : xlat_register: integer
Tue May 22 11:46:01 2018 : xlat_register: strlen
Tue May 22 11:46:01 2018 : xlat_register: length
Tue May 22 11:46:01 2018 : xlat_register: hex
Tue May 22 11:46:01 2018 : xlat_register: tag
Tue May 22 11:46:01 2018 : xlat_register: string
Tue May 22 11:46:01 2018 : xlat_register: xlat
Tue May 22 11:46:01 2018 : xlat_register: map
Tue May 22 11:46:01 2018 : xlat_register: module
Tue May 22 11:46:01 2018 : xlat_register: debug_attr
Tue May 22 11:46:01 2018 : xlat_register: debug
Tue May 22 11:46:01 2018 : _xlat_async_register: concat
Tue May 22 11:46:01 2018 : _xlat_async_register: bin
Tue May 22 11:46:01 2018 : xlat_register: config
Tue May 22 11:46:01 2018 : Debugger not attached
Tue May 22 11:46:01 2018 : xlat_register: trigger
Tue May 22 11:46:01 2018 : systemd watchdog is disabled
Tue May 22 11:46:01 2018 : xlat_register: interpreter
Tue May 22 11:46:01 2018 : #### Bootstrapping listeners ####
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[183]: Creating Auth-Type = pap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[192]: Creating Auth-Type = chap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[198]: Creating Auth-Type = mschap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[204]: Creating Auth-Type = pam
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[225]: Creating Auth-Type = eap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[551]: Creating Auth-Type = digest
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[572]: Creating Auth-Type = ldap
Tue May 22 11:46:01 2018 : #### Bootstrapping modules ####
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[655]:  modules {
Tue May 22 11:46:01 2018 : Loading rlm_unpack with path: /usr/local/stow/freeradius-4/lib/rlm_unpack.so
Tue May 22 11:46:01 2018 : rlm_unpack loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_unpack validated.  Handle address 0x2960310, symbol address 0x7fcd5c5930e0
Tue May 22 11:46:01 2018 : Symbol rlm_unpack_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_unpack_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unpack[41]: Loaded module "rlm_unpack"
Tue May 22 11:46:01 2018 : xlat_register: unpack
Tue May 22 11:46:01 2018 : Loading rlm_eap with path: /usr/local/stow/freeradius-4/lib/rlm_eap.so
Tue May 22 11:46:01 2018 : rlm_eap loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap validated.  Handle address 0x29615b0, symbol address 0x7fcd5c38f360
Tue May 22 11:46:01 2018 : Symbol rlm_eap_dict found at 0x7fcd5c38f300
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap
Tue May 22 11:46:01 2018 : Symbol rlm_eap_dict_attr found at 0x7fcd5c38f420
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]: Loaded module "rlm_eap"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]: Pushed parse rule to eap section: default_eap_type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]: Pushed parse rule to eap section: type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]: Pushed parse rule to eap section: ignore_unknown_eap_types {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]: Pushed parse rule to eap section: cisco_accounting_username_bug {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:     eap inner-eap {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       default_eap_type = mschapv2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       type = md5
Tue May 22 11:46:01 2018 : Loading rlm_eap_md5 with path: /usr/local/stow/freeradius-4/lib/rlm_eap_md5.so
Tue May 22 11:46:01 2018 : rlm_eap_md5 loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_md5 validated.  Handle address 0x2963f50, symbol address 0x7fcd5bf73160
Tue May 22 11:46:01 2018 : Symbol rlm_eap_md5_dict found at 0x7fcd5bf730e0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_md5
Tue May 22 11:46:01 2018 : Symbol rlm_eap_md5_dict_attr found at 0x7fcd5bf73120
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[42]: Loaded module "rlm_eap_md5"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       type = gtc
Tue May 22 11:46:01 2018 : Loading rlm_eap_gtc with path: /usr/local/stow/freeradius-4/lib/rlm_eap_gtc.so
Tue May 22 11:46:01 2018 : rlm_eap_gtc loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_gtc validated.  Handle address 0x2964d90, symbol address 0x7fcd5bd6e2c0
Tue May 22 11:46:01 2018 : Symbol rlm_eap_gtc_dict found at 0x7fcd5bd6e200
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_gtc
Tue May 22 11:46:01 2018 : Symbol rlm_eap_gtc_dict_attr found at 0x7fcd5bd6e260
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]: Loaded module "rlm_eap_gtc"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]: Pushed parse rule to gtc section: challenge 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]: Pushed parse rule to gtc section: auth_type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]:       gtc {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]:         challenge = "Password: "
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]:         auth_type = PAP
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[45]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       type = mschapv2
Tue May 22 11:46:01 2018 : Loading rlm_eap_mschapv2 with path: /usr/local/stow/freeradius-4/lib/rlm_eap_mschapv2.so
Tue May 22 11:46:01 2018 : rlm_eap_mschapv2 loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_mschapv2 validated.  Handle address 0x29664b0, symbol address 0x7fcd5bb6a5e0
Tue May 22 11:46:01 2018 : Symbol rlm_eap_mschapv2_dict found at 0x7fcd5bb6a380
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_mschapv2
Tue May 22 11:46:01 2018 : Symbol rlm_eap_mschapv2_dict_attr found at 0x7fcd5bb6a3e0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]: Loaded module "rlm_eap_mschapv2"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]: Pushed parse rule to mschapv2 section: with_ntdomain_hack {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]: Pushed parse rule to mschapv2 section: auth_type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]: Pushed parse rule to mschapv2 section: send_error {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]: Pushed parse rule to mschapv2 section: identity 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]:       mschapv2 {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]:         with_ntdomain_hack = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]:         auth_type = mschap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]:         send_error = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[53]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       type = tls
Tue May 22 11:46:01 2018 : Loading rlm_eap_tls with path: /usr/local/stow/freeradius-4/lib/rlm_eap_tls.so
Tue May 22 11:46:01 2018 : rlm_eap_tls loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_tls validated.  Handle address 0x29688e0, symbol address 0x7fcd5b963360
Tue May 22 11:46:01 2018 : Symbol rlm_eap_tls_dict found at 0x7fcd5b9632c0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_tls
Tue May 22 11:46:01 2018 : Symbol rlm_eap_tls_dict_attr found at 0x7fcd5b963300
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]: Loaded module "rlm_eap_tls"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]: Pushed parse rule to tls section: tls 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]: Pushed parse rule to tls section: require_client_cert {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]: Pushed parse rule to tls section: include_length {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]: Pushed parse rule to tls section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]:       tls {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]:         tls = "tls-peer"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]:         require_client_cert = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]:         include_length = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[164]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       ignore_unknown_eap_types = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:       cisco_accounting_username_bug = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]:     }
Tue May 22 11:46:01 2018 : Loading rlm_exec with path: /usr/local/stow/freeradius-4/lib/rlm_exec.so
Tue May 22 11:46:01 2018 : rlm_exec loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_exec validated.  Handle address 0x296b1a0, symbol address 0x7fcd5b75f0c0
Tue May 22 11:46:01 2018 : Symbol rlm_exec_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_exec_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Loaded module "rlm_exec"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Pushed parse rule to exec section: wait {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Pushed parse rule to exec section: program 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Pushed parse rule to exec section: input_pairs 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Pushed parse rule to exec section: output_pairs 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Pushed parse rule to exec section: shell_escape {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]: Pushed parse rule to exec section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]:     exec ntlm_auth {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]:       wait = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]:       program = "/path/to/ntlm_auth --request-nt-key --domain=MYDOMAIN --username=%{mschap:User-Name} --password=%{User-Password}"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]:       shell_escape = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/ntlm_auth[15]:     }
Tue May 22 11:46:01 2018 : xlat_register: ntlm_auth
Tue May 22 11:46:01 2018 : Loading rlm_unix with path: /usr/local/stow/freeradius-4/lib/rlm_unix.so
Tue May 22 11:46:01 2018 : rlm_unix loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_unix validated.  Handle address 0x296d7f0, symbol address 0x7fcd5b55b380
Tue May 22 11:46:01 2018 : Symbol rlm_unix_dict found at 0x7fcd5b55b180
Tue May 22 11:46:01 2018 : Loading dictionary rlm_unix
Tue May 22 11:46:01 2018 : Symbol rlm_unix_dict_attr found at 0x7fcd5b55b1e0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unix[15]: Loaded module "rlm_unix"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unix[15]: Pushed parse rule to unix section: radwtmp 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unix[15]:     unix {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unix[15]:       radwtmp = "/usr/local/stow/freeradius-4/var/log/radius/radwtmp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/unix[15]:     }
Tue May 22 11:46:01 2018 : Creating attribute Unix-Group
Tue May 22 11:46:01 2018 : Loading rlm_cache with path: /usr/local/stow/freeradius-4/lib/rlm_cache.so
Tue May 22 11:46:01 2018 : rlm_cache loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_cache validated.  Handle address 0x296eeb0, symbol address 0x7fcd5b3562e0
Tue May 22 11:46:01 2018 : Symbol rlm_cache_dict found at 0x7fcd5b3561c0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_cache
Tue May 22 11:46:01 2018 : Symbol rlm_cache_dict_attr found at 0x7fcd5b356200
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Loaded module "rlm_cache"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Pushed parse rule to cache section: driver 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Pushed parse rule to cache section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Pushed parse rule to cache section: ttl {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Pushed parse rule to cache section: max_entries {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Pushed parse rule to cache section: epoch {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Pushed parse rule to cache section: add_stats {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:     cache cache_eap {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:       driver = "rlm_cache_rbtree"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:       ttl = 15
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:       max_entries = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:       epoch = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:       add_stats = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]:     }
Tue May 22 11:46:01 2018 : xlat_register: cache_eap
Tue May 22 11:46:01 2018 : Loading rlm_client with path: /usr/local/stow/freeradius-4/lib/rlm_client.so
Tue May 22 11:46:01 2018 : rlm_client loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_client validated.  Handle address 0x2971e70, symbol address 0x7fcd5b14e160
Tue May 22 11:46:01 2018 : Symbol rlm_client_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_client_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/client[42]: Loaded module "rlm_client"
Tue May 22 11:46:01 2018 : xlat_register: client
Tue May 22 11:46:01 2018 : map_proc_register: client
Tue May 22 11:46:01 2018 : Loading rlm_attr_filter with path: /usr/local/stow/freeradius-4/lib/rlm_attr_filter.so
Tue May 22 11:46:01 2018 : rlm_attr_filter loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_attr_filter validated.  Handle address 0x2973450, symbol address 0x7fcd5af49220
Tue May 22 11:46:01 2018 : Symbol rlm_attr_filter_dict found at 0x7fcd5af490e0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_attr_filter
Tue May 22 11:46:01 2018 : Symbol rlm_attr_filter_dict_attr found at 0x7fcd5af49140
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]: Loaded module "rlm_attr_filter"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]: Pushed parse rule to attr_filter section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]: Pushed parse rule to attr_filter section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]: Pushed parse rule to attr_filter section: relaxed {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]:     attr_filter attr_filter.pre-proxy {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]:       filename = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/pre-proxy"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]:       relaxed = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]: Pushed parse rule to attr_filter section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]: Pushed parse rule to attr_filter section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]: Pushed parse rule to attr_filter section: relaxed {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]:     attr_filter attr_filter.post-proxy {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]:       filename = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/post-proxy"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]:       relaxed = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]: Pushed parse rule to attr_filter section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]: Pushed parse rule to attr_filter section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]: Pushed parse rule to attr_filter section: relaxed {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]:     attr_filter attr_filter.access_reject {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]:       filename = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/access_reject"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]:       relaxed = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]: Pushed parse rule to attr_filter section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]: Pushed parse rule to attr_filter section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]: Pushed parse rule to attr_filter section: relaxed {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]:     attr_filter attr_filter.access_challenge {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]:       filename = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/access_challenge"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]:       relaxed = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]: Pushed parse rule to attr_filter section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]: Pushed parse rule to attr_filter section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]: Pushed parse rule to attr_filter section: relaxed {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]:     attr_filter attr_filter.accounting_response {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]:       filename = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/accounting_response"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]:       relaxed = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]: Pushed parse rule to eap section: default_eap_type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]: Pushed parse rule to eap section: type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]: Pushed parse rule to eap section: ignore_unknown_eap_types {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]: Pushed parse rule to eap section: cisco_accounting_username_bug {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:     eap {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       default_eap_type = md5
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = md5
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = gtc
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[119]: Pushed parse rule to gtc section: challenge 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[119]: Pushed parse rule to gtc section: auth_type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[119]:       gtc {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[119]:         challenge = "Password: "
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[119]:         auth_type = PAP
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[119]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = tls
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]: Pushed parse rule to tls section: tls 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]: Pushed parse rule to tls section: require_client_cert {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]: Pushed parse rule to tls section: include_length {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]: Pushed parse rule to tls section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]:       tls {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]:         tls = "tls-common"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]:         require_client_cert = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]:         include_length = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[806]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = ttls
Tue May 22 11:46:01 2018 : Loading rlm_eap_ttls with path: /usr/local/stow/freeradius-4/lib/rlm_eap_ttls.so
Tue May 22 11:46:01 2018 : rlm_eap_ttls loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_ttls validated.  Handle address 0x297f3e0, symbol address 0x7fcd5ad44540
Tue May 22 11:46:01 2018 : Symbol rlm_eap_ttls_dict found at 0x7fcd5ad444e0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_ttls
Tue May 22 11:46:01 2018 : Symbol rlm_eap_ttls_dict_attr found at 0x7fcd5ad445e0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]: Loaded module "rlm_eap_ttls"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]: Pushed parse rule to ttls section: tls 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]: Pushed parse rule to ttls section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]: Pushed parse rule to ttls section: include_length {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]: Pushed parse rule to ttls section: require_client_cert {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]:       ttls {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]:         tls = "tls-common"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]:         virtual_server = "inner-tunnel"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]:         include_length = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]:         require_client_cert = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[863]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = mschapv2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]: Pushed parse rule to mschapv2 section: with_ntdomain_hack {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]: Pushed parse rule to mschapv2 section: auth_type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]: Pushed parse rule to mschapv2 section: send_error {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]: Pushed parse rule to mschapv2 section: identity 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]:       mschapv2 {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]:         with_ntdomain_hack = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]:         auth_type = mschap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]:         send_error = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1056]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = peap
Tue May 22 11:46:01 2018 : Loading rlm_eap_peap with path: /usr/local/stow/freeradius-4/lib/rlm_eap_peap.so
Tue May 22 11:46:01 2018 : rlm_eap_peap loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_peap validated.  Handle address 0x29831e0, symbol address 0x7fcd5ab3a660
Tue May 22 11:46:01 2018 : Symbol rlm_eap_peap_dict found at 0x7fcd5ab3a600
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_peap
Tue May 22 11:46:01 2018 : Symbol rlm_eap_peap_dict_attr found at 0x7fcd5ab3a700
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Loaded module "rlm_eap_peap"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: tls 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: inner_eap_module {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: proxy_tunneled_request_as_eap {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: soh {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: require_client_cert {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]: Pushed parse rule to peap section: soh_virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:       peap {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:         tls = "tls-common"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:         inner_eap_module = eap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:         proxy_tunneled_request_as_eap = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:         virtual_server = "inner-tunnel"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:         soh = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:         require_client_cert = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[987]: The item 'default_eap_type' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[968]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       type = sim
Tue May 22 11:46:01 2018 : Loading rlm_eap_sim with path: /usr/local/stow/freeradius-4/lib/rlm_eap_sim.so
Tue May 22 11:46:01 2018 : rlm_eap_sim loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_eap_sim validated.  Handle address 0x2986130, symbol address 0x7fcd5a930600
Tue May 22 11:46:01 2018 : xlat_register: sim_id_method
Tue May 22 11:46:01 2018 : xlat_register: sim_id_type
Tue May 22 11:46:01 2018 : xlat_register: 3gpp_pseudonym_key_index
Tue May 22 11:46:01 2018 : xlat_register: 3gpp_pseudonym_decrypt
Tue May 22 11:46:01 2018 : xlat_register: 3gpp_pseudonym_encrypt
Tue May 22 11:46:01 2018 : Symbol rlm_eap_sim_dict found at 0x7fcd5a930300
Tue May 22 11:46:01 2018 : Loading dictionary rlm_eap_sim
Tue May 22 11:46:01 2018 : Symbol rlm_eap_sim_dict_attr found at 0x7fcd5a930360
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1169]: Loaded module "rlm_eap_sim"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1169]: Pushed parse rule to sim section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1169]: Pushed parse rule to sim section: protected_success {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1169]:       sim {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1169]:         protected_success = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[1169]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       ignore_unknown_eap_types = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:       cisco_accounting_username_bug = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]:     }
Tue May 22 11:46:01 2018 : Loading rlm_radutmp with path: /usr/local/stow/freeradius-4/lib/rlm_radutmp.so
Tue May 22 11:46:01 2018 : rlm_radutmp loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_radutmp validated.  Handle address 0x29890f0, symbol address 0x7fcd5a507100
Tue May 22 11:46:01 2018 : Symbol rlm_radutmp_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_radutmp_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Loaded module "rlm_radutmp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Pushed parse rule to radutmp section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Pushed parse rule to radutmp section: username 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Pushed parse rule to radutmp section: case_sensitive {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Pushed parse rule to radutmp section: check_with_nas {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Pushed parse rule to radutmp section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]: Pushed parse rule to radutmp section: caller_id {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:     radutmp sradutmp {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/sradutmp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:       username = "%{User-Name}"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:       case_sensitive = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:       check_with_nas = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:       permissions = 420
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:       caller_id = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sradutmp[12]:     }
Tue May 22 11:46:01 2018 : Loading rlm_logintime with path: /usr/local/stow/freeradius-4/lib/rlm_logintime.so
Tue May 22 11:46:01 2018 : rlm_logintime loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_logintime validated.  Handle address 0x298bc60, symbol address 0x7fcd5a302200
Tue May 22 11:46:01 2018 : Symbol rlm_logintime_dict found at 0x7fcd5a302100
Tue May 22 11:46:01 2018 : Loading dictionary rlm_logintime
Tue May 22 11:46:01 2018 : Symbol rlm_logintime_dict_attr found at 0x7fcd5a302160
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime[16]: Loaded module "rlm_logintime"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime[16]: Pushed parse rule to logintime section: minimum_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime[16]:     logintime {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime[16]:       minimum_timeout = 60
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime[16]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]: Pushed parse rule to radutmp section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]: Pushed parse rule to radutmp section: username 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]: Pushed parse rule to radutmp section: case_sensitive {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]: Pushed parse rule to radutmp section: check_with_nas {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]: Pushed parse rule to radutmp section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]: Pushed parse rule to radutmp section: caller_id {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:     radutmp {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/radutmp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:       username = "%{User-Name}"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:       case_sensitive = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:       check_with_nas = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:       permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:       caller_id = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radutmp[11]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]: Pushed parse rule to exec section: wait {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]: Pushed parse rule to exec section: program 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]: Pushed parse rule to exec section: input_pairs 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]: Pushed parse rule to exec section: output_pairs 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]: Pushed parse rule to exec section: shell_escape {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]: Pushed parse rule to exec section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]:     exec {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]:       wait = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]:       input_pairs = "request"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]:       shell_escape = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]:       timeout = 10
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/exec[24]:     }
Tue May 22 11:46:01 2018 : xlat_register: exec
Tue May 22 11:46:01 2018 : Loading rlm_linelog with path: /usr/local/stow/freeradius-4/lib/rlm_linelog.so
Tue May 22 11:46:01 2018 : rlm_linelog loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_linelog validated.  Handle address 0x29907a0, symbol address 0x7fcd5a0fc240
Tue May 22 11:46:01 2018 : Symbol rlm_linelog_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_linelog_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Loaded module "rlm_linelog"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: destination 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: delimiter 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: format 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: reference 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: file {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: syslog {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: unix {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: tcp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Pushed parse rule to linelog section: udp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]:     linelog {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]:       destination = "file"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]:       delimiter = " "
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Evaluating rules for file section.  Output 0x2990dd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]: Pushed parse rule to file section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]: Pushed parse rule to file section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]: Pushed parse rule to file section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]: Pushed parse rule to file section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]:       file {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]:         filename = "/usr/local/stow/freeradius-4/var/log/radius/linelog"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]:         permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]:         escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[73]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Evaluating rules for syslog section.  Output 0x2990dd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[192]: Pushed parse rule to syslog section: facility 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[192]: Pushed parse rule to syslog section: severity 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[192]:       syslog {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[192]:         severity = "info"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[192]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Allocating fake section "unix"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Evaluating rules for unix section.  Output 0x2990dd0
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to unix section: filename 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       unix {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Evaluating rules for tcp section.  Output 0x2990e78
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]: Pushed parse rule to tcp section: server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]: Pushed parse rule to tcp section: port {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]: Pushed parse rule to tcp section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]:       tcp {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]:         port = 514
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]:         timeout = 2.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[166]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Evaluating rules for udp section.  Output 0x2990ec8
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]: Pushed parse rule to udp section: server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]: Pushed parse rule to udp section: port {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]: Pushed parse rule to udp section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]:       udp {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]:         port = 514
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]:         timeout = 2.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[189]: The item 'pool' is defined, but is unused by the configuration
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[179]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: destination 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: delimiter 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: format 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: reference 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: file {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: syslog {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: unix {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: tcp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Pushed parse rule to linelog section: udp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]:     linelog log_accounting {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]:       destination = "file"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]:       delimiter = " "
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Evaluating rules for file section.  Output 0x2996590
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]: Pushed parse rule to file section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]: Pushed parse rule to file section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]: Pushed parse rule to file section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]: Pushed parse rule to file section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]:       file {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]:         filename = "/usr/local/stow/freeradius-4/var/log/radius/linelog-accounting"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]:         permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]:         escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[247]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Allocating fake section "syslog"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Evaluating rules for syslog section.  Output 0x2996590
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to syslog section: facility 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to syslog section: severity 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       syslog {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         severity = "info"
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Allocating fake section "unix"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Evaluating rules for unix section.  Output 0x2996590
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to unix section: filename 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       unix {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Allocating fake section "tcp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Evaluating rules for tcp section.  Output 0x2996638
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tcp section: server 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tcp section: port {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tcp section: timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       tcp {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         timeout = 1000.000000
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Allocating fake section "udp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Evaluating rules for udp section.  Output 0x2996688
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to udp section: server 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to udp section: port {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to udp section: timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       udp {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         timeout = 1000.000000
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]:     }
Tue May 22 11:46:01 2018 : Loading rlm_digest with path: /usr/local/stow/freeradius-4/lib/rlm_digest.so
Tue May 22 11:46:01 2018 : rlm_digest loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_digest validated.  Handle address 0x299d670, symbol address 0x7fcd59ef4340
Tue May 22 11:46:01 2018 : Symbol rlm_digest_dict found at 0x7fcd59ef40e0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_digest
Tue May 22 11:46:01 2018 : Symbol rlm_digest_dict_attr found at 0x7fcd59ef4140
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/digest[12]: Loaded module "rlm_digest"
Tue May 22 11:46:01 2018 : Loading rlm_stats with path: /usr/local/stow/freeradius-4/lib/rlm_stats.so
Tue May 22 11:46:01 2018 : rlm_stats loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_stats validated.  Handle address 0x299e880, symbol address 0x7fcd59cee120
Tue May 22 11:46:01 2018 : Symbol rlm_stats_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_stats_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/stats[15]: Loaded module "rlm_stats"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/stats[15]:     stats {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/stats[15]:     }
Tue May 22 11:46:01 2018 : Loading rlm_soh with path: /usr/local/stow/freeradius-4/lib/rlm_soh.so
Tue May 22 11:46:01 2018 : rlm_soh loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_soh validated.  Handle address 0x299fda0, symbol address 0x7fcd59ae9240
Tue May 22 11:46:01 2018 : Symbol rlm_soh_dict found at 0x7fcd59ae90c0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_soh
Tue May 22 11:46:01 2018 : Symbol rlm_soh_dict_attr found at 0x7fcd59ae9120
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/soh[2]: Loaded module "rlm_soh"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/soh[2]: Pushed parse rule to soh section: dhcp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/soh[2]:     soh {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/soh[2]:       dhcp = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/soh[2]:     }
Tue May 22 11:46:01 2018 : xlat_register: soh
Tue May 22 11:46:01 2018 : Loading rlm_files with path: /usr/local/stow/freeradius-4/lib/rlm_files.so
Tue May 22 11:46:01 2018 : rlm_files loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_files validated.  Handle address 0x29a1400, symbol address 0x7fcd598e5180
Tue May 22 11:46:01 2018 : Symbol rlm_files_dict found at 0x7fcd598e5100
Tue May 22 11:46:01 2018 : Loading dictionary rlm_files
Tue May 22 11:46:01 2018 : Symbol rlm_files_dict_attr found at 0x7fcd598e5140
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Loaded module "rlm_files"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: usersfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: acctusersfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: preproxy_usersfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: postproxy_usersfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: auth_usersfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: postauth_usersfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Pushed parse rule to files section: key 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]:     files {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]:       filename = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/files/authorize"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]:       acctusersfile = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/files/accounting"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]:       preproxy_usersfile = "/usr/local/stow/freeradius-4/etc/raddb/mods-config/files/pre-proxy"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]:     }
Tue May 22 11:46:01 2018 : Loading rlm_utf8 with path: /usr/local/stow/freeradius-4/lib/rlm_utf8.so
Tue May 22 11:46:01 2018 : rlm_utf8 loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_utf8 validated.  Handle address 0x29a40a0, symbol address 0x7fcd596e0060
Tue May 22 11:46:01 2018 : Symbol rlm_utf8_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_utf8_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/utf8[12]: Loaded module "rlm_utf8"
Tue May 22 11:46:01 2018 : Loading rlm_radius with path: /usr/local/stow/freeradius-4/lib/rlm_radius.so
Tue May 22 11:46:01 2018 : rlm_radius loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_radius validated.  Handle address 0x29a51a0, symbol address 0x7fcd594ddb20
Tue May 22 11:46:01 2018 : Symbol rlm_radius_dict found at 0x7fcd594dda60
Tue May 22 11:46:01 2018 : Loading dictionary rlm_radius
Tue May 22 11:46:01 2018 : Symbol rlm_radius_dict_attr found at 0x7fcd594ddaa0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Loaded module "rlm_radius"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: transport {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: replicate {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: synchronous {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: no_connection_fail {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: status_checks {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: max_connections {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: max_attributes {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: connection {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:     radius {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:       transport = udp
Tue May 22 11:46:01 2018 : Loading rlm_radius_udp with path: /usr/local/stow/freeradius-4/lib/rlm_radius_udp.so
Tue May 22 11:46:01 2018 : rlm_radius_udp loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_radius_udp validated.  Handle address 0x29a7c80, symbol address 0x7fcd592d3600
Tue May 22 11:46:01 2018 : Symbol rlm_radius_udp_dict found at 0x7fcd592d34c0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_radius_udp
Tue May 22 11:46:01 2018 : Symbol rlm_radius_udp_dict_attr found at 0x7fcd592d3500
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Loaded module "rlm_radius_udp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: ipv4addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: ipv6addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: port {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: secret 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: interface 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: recv_buff {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: send_buff {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: max_packet_size {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: src_ipaddr 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: src_ipv4addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]: Pushed parse rule to udp section: src_ipv6addr {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]:       udp {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]:         ipaddr = 127.0.0.1
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]:         port = 1812
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]:         secret = "testing123"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]:         max_packet_size = 4096
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[139]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:       type = Access-Request
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: Access-Request {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:       type = Accounting-Request
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: Accounting-Request {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Evaluating rules for status_checks section.  Output 0x29a5a20
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[92]: Pushed parse rule to status_checks section: type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[92]:       status_checks {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[92]:         type = Status-Server
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Pushed parse rule to radius section: Status-Server {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[92]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:       max_connections = 32
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:       max_attributes = 255
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Evaluating rules for connection section.  Output 0x29a5a20
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]: Pushed parse rule to connection section: connect_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]: Pushed parse rule to connection section: reconnect_delay {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]: Pushed parse rule to connection section: idle_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]: Pushed parse rule to connection section: zombie_period {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]:       connection {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]:         connect_timeout = 5.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]:         reconnect_delay = 5.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]:         idle_timeout = 5.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]:         zombie_period = 1.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[157]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Evaluating rules for Access-Request section.  Output 0x29a5a20
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]: Pushed parse rule to Access-Request section: initial_retransmission_time {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]: Pushed parse rule to Access-Request section: maximum_retransmission_time {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]: Pushed parse rule to Access-Request section: maximum_retransmission_count {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]: Pushed parse rule to Access-Request section: maximum_retransmission_duration {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]:       Access-Request {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]:         initial_retransmission_time = 2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]:         maximum_retransmission_time = 16
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]:         maximum_retransmission_count = 2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]:         maximum_retransmission_duration = 30
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[198]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Evaluating rules for Accounting-Request section.  Output 0x29a5a20
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]: Pushed parse rule to Accounting-Request section: initial_retransmission_time {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]: Pushed parse rule to Accounting-Request section: maximum_retransmission_time {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]: Pushed parse rule to Accounting-Request section: maximum_retransmission_count {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]: Pushed parse rule to Accounting-Request section: maximum_retransmission_duration {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]:       Accounting-Request {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]:         initial_retransmission_time = 2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]:         maximum_retransmission_time = 16
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]:         maximum_retransmission_count = 5
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]:         maximum_retransmission_duration = 30
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[247]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Evaluating rules for Status-Server section.  Output 0x29a5a20
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]: Pushed parse rule to Status-Server section: initial_retransmission_time {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]: Pushed parse rule to Status-Server section: maximum_retransmission_time {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]: Pushed parse rule to Status-Server section: maximum_retransmission_count {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]: Pushed parse rule to Status-Server section: maximum_retransmission_duration {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]:       Status-Server {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]:         initial_retransmission_time = 2
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]:         maximum_retransmission_time = 16
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]:         maximum_retransmission_count = 5
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]:         maximum_retransmission_duration = 30
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[286]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]:     }
Tue May 22 11:46:01 2018 : Loading rlm_detail with path: /usr/local/stow/freeradius-4/lib/rlm_detail.so
Tue May 22 11:46:01 2018 : rlm_detail loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_detail validated.  Handle address 0x29af200, symbol address 0x7fcd590c3300
Tue May 22 11:46:01 2018 : Symbol rlm_detail_dict found at 0x7fcd590c31a0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_detail
Tue May 22 11:46:01 2018 : Symbol rlm_detail_dict_attr found at 0x7fcd590c3200
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Loaded module "rlm_detail"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: header 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: locking {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Pushed parse rule to detail section: log_packet_header {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:     detail {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/detail-%Y%m%d"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:       header = "%t"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:       permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:       locking = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:       escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:       log_packet_header = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]:     }
Tue May 22 11:46:01 2018 : Loading rlm_chap with path: /usr/local/stow/freeradius-4/lib/rlm_chap.so
Tue May 22 11:46:01 2018 : rlm_chap loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_chap validated.  Handle address 0x29b1e00, symbol address 0x7fcd58ebd200
Tue May 22 11:46:01 2018 : Symbol rlm_chap_dict found at 0x7fcd58ebd0e0
Tue May 22 11:46:01 2018 : Loading dictionary rlm_chap
Tue May 22 11:46:01 2018 : Symbol rlm_chap_dict_attr found at 0x7fcd58ebd140
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/chap[11]: Loaded module "rlm_chap"
Tue May 22 11:46:01 2018 : Loading rlm_expr with path: /usr/local/stow/freeradius-4/lib/rlm_expr.so
Tue May 22 11:46:01 2018 : rlm_expr loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_expr validated.  Handle address 0x29b3370, symbol address 0x7fcd58cb8460
Tue May 22 11:46:01 2018 : Symbol rlm_expr_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_expr_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expr[135]: Loaded module "rlm_expr"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expr[135]: Pushed parse rule to expr section: safe_characters 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expr[135]:     expr {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expr[135]:       safe_characters = "@abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789.-_: /äéöüàâæçèéêëîïôœùûüaÿÄÉÖÜßÀÂÆÇÈÉÊËÎÏÔŒÙÛÜŸ"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expr[135]:     }
Tue May 22 11:46:01 2018 : xlat_register: expr
Tue May 22 11:46:01 2018 : xlat_register: rand
Tue May 22 11:46:01 2018 : xlat_register: randstr
Tue May 22 11:46:01 2018 : xlat_register: urlquote
Tue May 22 11:46:01 2018 : xlat_register: urlunquote
Tue May 22 11:46:01 2018 : xlat_register: escape
Tue May 22 11:46:01 2018 : xlat_register: unescape
Tue May 22 11:46:01 2018 : xlat_register: tolower
Tue May 22 11:46:01 2018 : xlat_register: toupper
Tue May 22 11:46:01 2018 : xlat_register: md5
Tue May 22 11:46:01 2018 : xlat_register: sha1
Tue May 22 11:46:01 2018 : xlat_register: sha256
Tue May 22 11:46:01 2018 : xlat_register: sha512
Tue May 22 11:46:01 2018 : xlat_register: hmacmd5
Tue May 22 11:46:01 2018 : xlat_register: hmacsha1
Tue May 22 11:46:01 2018 : xlat_register: pairs
Tue May 22 11:46:01 2018 : xlat_register: base64
Tue May 22 11:46:01 2018 : xlat_register: base64tohex
Tue May 22 11:46:01 2018 : xlat_register: explode
Tue May 22 11:46:01 2018 : xlat_register: nexttime
Tue May 22 11:46:01 2018 : xlat_register: lpad
Tue May 22 11:46:01 2018 : xlat_register: rpad
Tue May 22 11:46:01 2018 : Loading rlm_passwd with path: /usr/local/stow/freeradius-4/lib/rlm_passwd.so
Tue May 22 11:46:01 2018 : rlm_passwd loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_passwd validated.  Handle address 0x29b7bb0, symbol address 0x7fcd58aac100
Tue May 22 11:46:01 2018 : Symbol rlm_passwd_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_passwd_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Loaded module "rlm_passwd"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: format 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: delimiter 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: ignore_nislike {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: ignore_empty {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: allow_multiple_keys {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Pushed parse rule to passwd section: hash_size {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:     passwd etc_passwd {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       filename = "/etc/passwd"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       format = "*User-Name:Crypt-Password:"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       delimiter = ":"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       ignore_nislike = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       ignore_empty = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       allow_multiple_keys = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:       hash_size = 100
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]:     }
Tue May 22 11:46:01 2018 : Loading rlm_always with path: /usr/local/stow/freeradius-4/lib/rlm_always.so
Tue May 22 11:46:01 2018 : rlm_always loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_always validated.  Handle address 0x29ba680, symbol address 0x7fcd588a6080
Tue May 22 11:46:01 2018 : Symbol rlm_always_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_always_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]: Loaded module "rlm_always"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]:     always reject {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]:       rcode = "reject"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]:     always fail {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]:       rcode = "fail"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]:     always ok {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]:       rcode = "ok"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]:     always handled {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]:       rcode = "handled"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]:     always invalid {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]:       rcode = "invalid"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]:     always userlock {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]:       rcode = "userlock"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]:     always notfound {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]:       rcode = "notfound"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]:     always noop {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]:       rcode = "noop"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]: Pushed parse rule to always section: rcode 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]: Pushed parse rule to always section: simulcount {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]: Pushed parse rule to always section: mpp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]:     always updated {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]:       rcode = "updated"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]:       simulcount = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]:       mpp = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]:     }
Tue May 22 11:46:01 2018 : Loading rlm_pam with path: /usr/local/stow/freeradius-4/lib/rlm_pam.so
Tue May 22 11:46:01 2018 : rlm_pam loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_pam validated.  Handle address 0x29c8840, symbol address 0x7fcd586a30c0
Tue May 22 11:46:01 2018 : Symbol rlm_pam_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_pam_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam[15]: Loaded module "rlm_pam"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam[15]: Pushed parse rule to pam section: pam_auth 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam[15]:     pam {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam[15]:       pam_auth = "radiusd"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam[15]:     }
Tue May 22 11:46:01 2018 : Loading rlm_pap with path: /usr/local/stow/freeradius-4/lib/rlm_pap.so
Tue May 22 11:46:01 2018 : rlm_pap loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_pap validated.  Handle address 0x29ca7e0, symbol address 0x7fcd5806a600
Tue May 22 11:46:01 2018 : Symbol rlm_pap_dict found at 0x7fcd5806a260
Tue May 22 11:46:01 2018 : Loading dictionary rlm_pap
Tue May 22 11:46:01 2018 : Symbol rlm_pap_dict_attr found at 0x7fcd5806a2c0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pap[13]: Loaded module "rlm_pap"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pap[13]: Pushed parse rule to pap section: normalise {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pap[13]:     pap {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pap[13]:       normalise = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pap[13]:     }
Tue May 22 11:46:01 2018 : Loading rlm_expiration with path: /usr/local/stow/freeradius-4/lib/rlm_expiration.so
Tue May 22 11:46:01 2018 : rlm_expiration loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_expiration validated.  Handle address 0x29cc240, symbol address 0x7fcd57e5e140
Tue May 22 11:46:01 2018 : Symbol rlm_expiration_dict found at 0x7fcd57e5e080
Tue May 22 11:46:01 2018 : Loading dictionary rlm_expiration
Tue May 22 11:46:01 2018 : Symbol rlm_expiration_dict_attr found at 0x7fcd57e5e0e0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expiration[12]: Loaded module "rlm_expiration"
Tue May 22 11:46:01 2018 : Loading rlm_dhcpv4 with path: /usr/local/stow/freeradius-4/lib/rlm_dhcpv4.so
Tue May 22 11:46:01 2018 : rlm_dhcpv4 loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_dhcpv4 validated.  Handle address 0x29cd470, symbol address 0x7fcd57c5a140
Tue May 22 11:46:01 2018 : Symbol rlm_dhcpv4_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_dhcpv4_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/dhcpv4[18]: Loaded module "rlm_dhcpv4"
Tue May 22 11:46:01 2018 : xlat_register: dhcp_options
Tue May 22 11:46:01 2018 : xlat_register: dhcp
Tue May 22 11:46:01 2018 : Adding values for DHCP-Parameter-Request-List
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 1 DHCP-Subnet-Mask
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 2 DHCP-Time-Offset
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 3 DHCP-Router-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 4 DHCP-Time-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 5 DHCP-IEN-116-Name-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 6 DHCP-Domain-Name-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 7 DHCP-Log-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 8 DHCP-Quotes-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 9 DHCP-LPR-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 10 DHCP-Impress-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 11 DHCP-RLP-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 12 DHCP-Hostname
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 13 DHCP-Boot-File-Size
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 14 DHCP-Merit-Dump-File
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 15 DHCP-Domain-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 16 DHCP-Swap-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 17 DHCP-Root-Path
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 18 DHCP-Bootp-Extensions-Path
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 19 DHCP-IP-Forward-Enable
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 20 DHCP-Source-Route-Enable
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 21 DHCP-Policy-Filter
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 22 DHCP-Max-Datagram-Reassembly-Size
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 23 DHCP-Default-IP-TTL
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 24 DHCP-Path-MTU-Aging-Timeout
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 25 DHCP-Path-MTU-Plateau-Table
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 26 DHCP-Interface-MTU-Size
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 27 DHCP-All-Subnets-Are-Local
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 28 DHCP-Broadcast-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 29 DHCP-Perform-Mask-Discovery
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 30 DHCP-Provide-Mask-To-Others
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 31 DHCP-Perform-Router-Discovery
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 32 DHCP-Router-Solicitation-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 33 DHCP-Static-Routes
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 34 DHCP-Trailer-Encapsulation
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 35 DHCP-ARP-Cache-Timeout
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 36 DHCP-Ethernet-Encapsulation
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 37 DHCP-Default-TCP-TTL
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 38 DHCP-Keep-Alive-Interval
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 39 DHCP-Keep-Alive-Garbage
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 40 DHCP-NIS-Domain-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 41 DHCP-NIS-Servers
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 42 DHCP-NTP-Servers
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 43 DHCP-Vendor
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 44 DHCP-NETBIOS-Name-Servers
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 45 DHCP-NETBIOS-Dgm-Dist-Servers
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 46 DHCP-NETBIOS-Node-Type
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 47 DHCP-NETBIOS
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 48 DHCP-X-Window-Font-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 49 DHCP-X-Window-Display-Mgr
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 50 DHCP-Requested-IP-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 51 DHCP-IP-Address-Lease-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 52 DHCP-Overload
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 53 DHCP-Message-Type
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 54 DHCP-DHCP-Server-Identifier
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 55 DHCP-Parameter-Request-List
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 56 DHCP-DHCP-Error-Message
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 57 DHCP-DHCP-Maximum-Msg-Size
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 58 DHCP-Renewal-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 59 DHCP-Rebinding-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 60 DHCP-Vendor-Class-Identifier
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 61 DHCP-Client-Identifier
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 62 DHCP-Netware-Domain-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 63 DHCP-Netware-Sub-Options
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 64 DHCP-NIS-Client-Domain-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 65 DHCP-NIS-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 66 DHCP-TFTP-Server-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 67 DHCP-Boot-File-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 68 DHCP-Home-Agent-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 69 DHCP-SMTP-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 70 DHCP-POP3-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 71 DHCP-NNTP-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 72 DHCP-WWW-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 73 DHCP-Finger-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 74 DHCP-IRC-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 75 DHCP-StreetTalk-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 76 DHCP-STDA-Server-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 77 DHCP-User-Class
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 78 DHCP-Directory-Agent
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 79 DHCP-Service-Scope
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 80 DHCP-Rapid-Commit
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 81 DHCP-Client-FQDN
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 82 DHCP-Relay-Agent-Information
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 83 DHCP-iSNS
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 84
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 85 DHCP-NDS-Servers
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 86 DHCP-NDS-Tree-Name
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 87 DHCP-NDS-Context
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 88 DHCP-BCMS-Server-IPv4-FQDN
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 89 DHCP-BCMS-Server-IPv4-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 90 DHCP-Authentication
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 91 DHCP-Client-Last-Txn-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 92 DHCP-associated-ip
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 93 DHCP-Client-System
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 94 DHCP-Client-NDI
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 95 DHCP-LDAP
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 96
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 97 DHCP-UUID/GUID
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 98 DHCP-User-Auth
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 99 DHCP-GeoConf-Civic
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 100 DHCP-Timezone-Posix
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 101 DHCP-Timezone-Database
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 102
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 103
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 104
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 105
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 106
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 107
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 108
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 109
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 110
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 111
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 112 DHCP-Netinfo-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 113 DHCP-Netinfo-Tag
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 114 DHCP-URL
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 115
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 116 DHCP-Auto-Config
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 117 DHCP-Name-Service-Search
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 118 DHCP-Subnet-Selection-Option
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 119 DHCP-Domain-Search
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 120 DHCP-SIP-Servers-DHCP-Option
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 121 DHCP-Classless-Static-Route
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 122 DHCP-CCC
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 123 DHCP-GeoConf-Option
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 124 DHCP-V-I-Vendor-Class
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 125 DHCP-V-I-Vendor-Specific
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 126
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 127
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 128 DHCP-TFTP-Server-IP-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 129 DHCP-Call-Server-IP-address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 130 DHCP-Vendor-Discrimination-Str
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 131 DHCP-Remote-Stats-Svr-IP-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 132 DHCP-IEEE-802dot1Q-VLAN-ID
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 133 DHCP-IEEE-802dot1P-L2-Priority
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 134 DHCP-Diffserv-Code-Point
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 135 DHCP-HTTP-Proxy
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 136 DHCP-PANA-Agent
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 137 DHCP-LoST-Server
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 138 DHCP-CAPWAP-AC-IPv4-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 139 DHCP-MoS-IPv4-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 140 DHCP-MoS-IPv4-FQDN
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 141 DHCP-SIP-UA-Configuration-Service-Domains
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 142 DHCP-ANDSF-IPv4-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 143 DHCP-ANDSF-IPv6-Address
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 144
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 145
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 146
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 147
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 148
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 149
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 150 DHCP-TFTP-Server-IPv4-Address
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 151 DHCP-Query-Status-Code
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 152 DHCP-Query-Server-Base-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 153 DHCP-Query-Start-Time-Of-State
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 154 DHCP-Query-Start-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 155 DHCP-Query-End-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 156 DHCP-State
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 157 DHCP-Data-Source
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 158 DHCP-PCP-IPv4-Server-Address
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 159
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 160
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 161
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 162
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 163
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 164
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 165
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 166
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 167
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 168
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 169
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 170
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 171
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 172
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 173
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 174
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 175
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 176
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 177
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 178
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 179
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 180
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 181
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 182
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 183
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 184
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 185
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 186
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 187
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 188
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 189
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 190
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 191
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 192
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 193
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 194
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 195
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 196
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 197
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 198
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 199
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 200
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 201
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 202
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 203
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 204
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 205
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 206
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 207
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 208 DHCP-PXELINUX-Magic
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 209 DHCP-Packet-Format
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 210 DHCP-Path-Prefix
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 211 DHCP-Reboot-Time
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 212 DHCP-6RD
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 213 DHCP-Access-Network-Domain-Name
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 214
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 215
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 216
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 217
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 218
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 219
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 220 DHCP-Virtual-Subnet-Allocation
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 221 DHCP-Virtual-Subnet-Selection
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 222
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 223
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 224 DHCP-Site-specific-0
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 225 DHCP-Site-specific-1
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 226 DHCP-Site-specific-2
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 227 DHCP-Site-specific-3
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 228 DHCP-Site-specific-4
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 229 DHCP-Site-specific-5
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 230 DHCP-Site-specific-6
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 231 DHCP-Site-specific-7
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 232 DHCP-Site-specific-8
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 233 DHCP-Site-specific-9
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 234 DHCP-Site-specific-10
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 235 DHCP-Site-specific-11
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 236 DHCP-Site-specific-12
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 237 DHCP-Site-specific-13
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 238 DHCP-Site-specific-14
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 239 DHCP-Site-specific-15
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 240 DHCP-Site-specific-16
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 241 DHCP-Site-specific-17
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 242 DHCP-Site-specific-18
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 243 DHCP-Site-specific-19
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 244 DHCP-Site-specific-20
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 245 DHCP-Site-specific-21
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 246 DHCP-Site-specific-22
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 247 DHCP-Site-specific-23
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 248 DHCP-Site-specific-24
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 249 DHCP-Site-specific-25
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 250 DHCP-Site-specific-26
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 251 DHCP-Site-specific-27
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 252 DHCP-Site-specific-28
Tue May 22 11:46:01 2018 : Adding DHCP-Parameter-Request-List value 253 DHCP-Site-specific-30
Tue May 22 11:46:01 2018 : No DHCP RFC space attribute at 254
Tue May 22 11:46:01 2018 : Loading rlm_mschap with path: /usr/local/stow/freeradius-4/lib/rlm_mschap.so
Tue May 22 11:46:01 2018 : rlm_mschap loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_mschap validated.  Handle address 0x2a10c90, symbol address 0x7fcd578482c0
Tue May 22 11:46:01 2018 : Symbol rlm_mschap_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_mschap_dict_attr found at 0x7fcd57848380
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Loaded module "rlm_mschap"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: use_mppe {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: require_encryption {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: require_strong {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: with_ntdomain_hack {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: ntlm_auth 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: ntlm_auth_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: passchange {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: allow_retry {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: retry_msg 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: winbind_username 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Pushed parse rule to mschap section: winbind_domain 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:     mschap {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:       use_mppe = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:       require_encryption = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:       require_strong = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:       with_ntdomain_hack = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Evaluating rules for passchange section.  Output 0x2a11390
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[168]: Pushed parse rule to passchange section: ntlm_auth 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[168]: Pushed parse rule to passchange section: ntlm_auth_username 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[168]: Pushed parse rule to passchange section: ntlm_auth_domain 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[168]: Pushed parse rule to passchange section: local_cpw 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[168]:       passchange {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[168]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:       allow_retry = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]:     }
Tue May 22 11:46:01 2018 : xlat_register: mschap
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]: Pushed parse rule to exec section: wait {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]: Pushed parse rule to exec section: program 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]: Pushed parse rule to exec section: input_pairs 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]: Pushed parse rule to exec section: output_pairs 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]: Pushed parse rule to exec section: shell_escape {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]: Pushed parse rule to exec section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:     exec echo {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:       wait = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:       program = "/bin/echo %{User-Name}"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:       input_pairs = "request"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:       output_pairs = "reply"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:       shell_escape = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/echo[34]:     }
Tue May 22 11:46:01 2018 : xlat_register: echo
Tue May 22 11:46:01 2018 : Loading rlm_sql with path: /usr/local/stow/freeradius-4/lib/rlm_sql.so
Tue May 22 11:46:01 2018 : rlm_sql loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_sql validated.  Handle address 0x2a177b0, symbol address 0x7fcd576393e0
Tue May 22 11:46:01 2018 : Symbol rlm_sql_dict found at 0x7fcd57639300
Tue May 22 11:46:01 2018 : Loading dictionary rlm_sql
Tue May 22 11:46:01 2018 : Symbol rlm_sql_dict_attr found at 0x7fcd57639360
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Loaded module "rlm_sql"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: driver 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: port {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: login 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: password 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: radius_db 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: read_groups {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: read_profiles {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: sql_user_name 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: group_attribute 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: logfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: default_user_profile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: open_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: authorize_check_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: authorize_reply_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: authorize_group_check_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: authorize_group_reply_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: group_membership_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: safe_characters 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: query_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: accounting {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Pushed parse rule to sql section: post-auth {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:     sql {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       driver = "rlm_sql_mysql"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       server = "localhost"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       port = 3306
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       login = "root"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       password = "15-Bylecjd"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       radius_db = "radius_serv"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       read_groups = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       read_profiles = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       sql_user_name = "%{User-Name}"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       logfile = "/usr/local/stow/freeradius-4/var/log/radius/sqllog.sql"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       default_user_profile = ""
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       authorize_check_query = "SELECT id, username, attribute, value, op FROM radcheck WHERE username = '%{SQL-User-Name}' ORDER BY id"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       authorize_reply_query = "SELECT id, username, attribute, value, op FROM radreply WHERE username = '%{SQL-User-Name}' ORDER BY id"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       authorize_group_check_query = "SELECT id, groupname, attribute, Value, op FROM radgroupcheck WHERE groupname = '%{sql-Group}' ORDER BY id"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       authorize_group_reply_query = "SELECT id, groupname, attribute, value, op FROM radgroupreply WHERE groupname = '%{sql-Group}' ORDER BY id"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       group_membership_query = "SELECT groupname FROM radusergroup WHERE username = '%{SQL-User-Name}' ORDER BY priority"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:       safe_characters = "@abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789.-_: /"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Evaluating rules for accounting section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]: Pushed parse rule to accounting section: reference 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]: Pushed parse rule to accounting section: logfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]: Pushed parse rule to accounting section: type {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]:       accounting {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]:         reference = "%{tolower:type.%{Acct-Status-Type}.query}"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]: Evaluating rules for type section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Pushed parse rule to type section: accounting-on {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Pushed parse rule to type section: accounting-off {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Pushed parse rule to type section: start {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Pushed parse rule to type section: interim-update {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Pushed parse rule to type section: stop {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]:         type {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Evaluating rules for accounting-on section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[168]: Pushed parse rule to accounting-on section: query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[168]:           accounting-on {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[168]:           }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Evaluating rules for accounting-off section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[186]: Pushed parse rule to accounting-off section: query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[186]:           accounting-off {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[186]:             query = "UPDATE radacct SET acctstoptime = FROM_UNIXTIME(%{integer:Event-Timestamp}), acctsessiontime	= '%{integer:Event-Timestamp}' - UNIX_TIMESTAMP(acctstarttime), acctterminatecause = '%{%{Acct-Terminate-Cause}:-NAS-Reboot}' WHERE acctstoptime IS NULL AND nasipaddress   = '%{NAS-IP-Address}' AND acctstarttime <= FROM_UNIXTIME(%{integer:Event-Timestamp})"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[186]:           }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Evaluating rules for start section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[190]: Pushed parse rule to start section: query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[190]:           start {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[190]:             query = "INSERT INTO radacct (acctsessionid,		acctuniqueid,		username, realm,			nasipaddress,		nasportid, nasporttype,		acctstarttime,		acctupdatetime, acctstoptime,		acctsessiontime, 	acctauthentic, connectinfo_start,	connectinfo_stop, 	acctinputoctets, acctoutputoctets,	calledstationid, 	callingstationid, acctterminatecause,	servicetype,		framedprotocol, framedipaddress) VALUES ('%{Acct-Session-Id}', '%{Acct-Unique-Session-Id}', '%{SQL-User-Name}', '%{Realm}', '%{NAS-IP-Address}', '%{%{NAS-Port-ID}:-%{NAS-Port}}', '%{NAS-Port-Type}', FROM_UNIXTIME(%{integer:Event-Timestamp}), FROM_UNIXTIME(%{integer:Event-Timestamp}), NULL, '0', '%{Acct-Authentic}', '%{Connect-Info}', '', '0', '0', '%{Called-Station-Id}', '%{Calling-Station-Id}', '', '%{Service-Type}', '%{Framed-Protocol}', '%{Framed-IP-Address}')"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[190]:             query = "UPDATE radacct SET acctstarttime	= FROM_UNIXTIME(%{integer:Event-Timestamp}), acctupdatetime	= FROM_UNIXTIME(%{integer:Event-Timestamp}), connectinfo_start = '%{Connect-Info}' WHERE acctuniqueid = '%{Acct-Unique-Session-Id}'"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[190]:           }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Evaluating rules for interim-update section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[233]: Pushed parse rule to interim-update section: query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[233]:           interim-update {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[233]:             query = "UPDATE radacct SET acctupdatetime  = (@acctupdatetime_old:=acctupdatetime), acctupdatetime  = FROM_UNIXTIME(%{integer:Event-Timestamp}), acctinterval    = %{integer:Event-Timestamp} - UNIX_TIMESTAMP(@acctupdatetime_old), framedipaddress = '%{Framed-IP-Address}', acctsessiontime = %{%{Acct-Session-Time}:-NULL}, acctinputoctets = '%{%{Acct-Input-Gigawords}:-0}' << 32 | '%{%{Acct-Input-Octets}:-0}', acctoutputoctets = '%{%{Acct-Output-Gigawords}:-0}' << 32 | '%{%{Acct-Output-Octets}:-0}' WHERE acctuniqueid = '%{Acct-Unique-Session-Id}'"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[233]:             query = "INSERT INTO radacct (acctsessionid,		acctuniqueid,		username, realm,			nasipaddress,		nasportid, nasporttype,		acctstarttime,		acctupdatetime, acctstoptime,		acctsessiontime, 	acctauthentic, connectinfo_start,	connectinfo_stop, 	acctinputoctets, acctoutputoctets,	calledstationid, 	callingstationid, acctterminatecause,	servicetype,		framedprotocol, framedipaddress) VALUES ('%{Acct-Session-Id}', '%{Acct-Unique-Session-Id}', '%{SQL-User-Name}', '%{Realm}', '%{NAS-IP-Address}', '%{%{NAS-Port-ID}:-%{NAS-Port}}', '%{NAS-Port-Type}', FROM_UNIXTIME(%{integer:Event-Timestamp} - %{%{Acct-Session-Time}:-0}), FROM_UNIXTIME(%{integer:Event-Timestamp}), NULL, %{%{Acct-Session-Time}:-NULL}, '%{Acct-Authentic}', '%{Connect-Info}', '', '%{%{Acct-Input-Gigawords}:-0}' << 32 | '%{%{Acct-Input-Octets}:-0}', '%{%{Acct-Output-Gigawords}:-0}' << 32 | '%{%{Acct-Output-Octets}:-0}', '%{Called-Station-Id}', '%{Calling-Station-Id}', '', '%{Service-Type}', '%{Framed-Protocol}', '%{Framed-IP-Address}')"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[233]:           }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]: Evaluating rules for stop section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[287]: Pushed parse rule to stop section: query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[287]:           stop {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[287]:             query = "UPDATE radacct SET acctstoptime	= FROM_UNIXTIME(%{integer:Event-Timestamp}), acctsessiontime	= %{%{Acct-Session-Time}:-NULL}, acctinputoctets	= '%{%{Acct-Input-Gigawords}:-0}' << 32 | '%{%{Acct-Input-Octets}:-0}', acctoutputoctets = '%{%{Acct-Output-Gigawords}:-0}' << 32 | '%{%{Acct-Output-Octets}:-0}', acctterminatecause = '%{Acct-Terminate-Cause}', connectinfo_stop = '%{Connect-Info}' WHERE acctuniqueid = '%{Acct-Unique-Session-Id}'"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[287]:             query = "INSERT INTO radacct (acctsessionid,		acctuniqueid,		username, realm,			nasipaddress,		nasportid, nasporttype,		acctstarttime,		acctupdatetime, acctstoptime,		acctsessiontime, 	acctauthentic, connectinfo_start,	connectinfo_stop, 	acctinputoctets, acctoutputoctets,	calledstationid, 	callingstationid, acctterminatecause,	servicetype,		framedprotocol, framedipaddress) VALUES ('%{Acct-Session-Id}', '%{Acct-Unique-Session-Id}', '%{SQL-User-Name}', '%{Realm}', '%{NAS-IP-Address}', '%{%{NAS-Port-ID}:-%{NAS-Port}}', '%{NAS-Port-Type}', FROM_UNIXTIME(%{integer:Event-Timestamp} - %{%{Acct-Session-Time}:-0}), FROM_UNIXTIME(%{integer:Event-Timestamp}), FROM_UNIXTIME(%{integer:Event-Timestamp}), %{%{Acct-Session-Time}:-NULL}, '%{Acct-Authentic}', '', '%{Connect-Info}', '%{%{Acct-Input-Gigawords}:-0}' << 32 | '%{%{Acct-Input-Octets}:-0}', '%{%{Acct-Output-Gigawords}:-0}' << 32 | '%{%{Acct-Output-Octets}:-0}', '%{Called-Station-Id}', '%{Calling-Station-Id}', '%{Acct-Terminate-Cause}', '%{Service-Type}', '%{Framed-Protocol}', '%{Framed-IP-Address}')"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[287]:           }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[167]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[150]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Evaluating rules for post-auth section.  Output 0x2a17fd0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]: Pushed parse rule to post-auth section: reference 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]: Pushed parse rule to post-auth section: logfile 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]: Pushed parse rule to post-auth section: query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]:       post-auth {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]:         reference = ".query"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]:         query = "INSERT INTO radpostauth (username, pass, reply, authdate) VALUES ( '%{SQL-User-Name}', '%{%{User-Password}:-%{Chap-Password}}', '%{reply:Packet-Type}', '%S')"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/main/mysql/queries.conf[345]:       }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]:     }
Tue May 22 11:46:01 2018 : Loading rlm_sql_mysql with path: /usr/local/stow/freeradius-4/lib/rlm_sql_mysql.so
Tue May 22 11:46:01 2018 : rlm_sql_mysql loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_sql_mysql validated.  Handle address 0x2a22110, symbol address 0x7fcd5742b3c0
Tue May 22 11:46:01 2018 : rlm_sql_mysql - libmysql version: 5.7.22
Tue May 22 11:46:01 2018 : Symbol rlm_sql_mysql_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_sql_mysql_dict_attr not found
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]: Loaded module "rlm_sql_mysql"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]: Pushed parse rule to mysql section: tls {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]: Pushed parse rule to mysql section: warnings 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]:       mysql {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]: Allocating fake section "tls"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]: Evaluating rules for tls section.  Output 0x2a24c80
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tls section: ca_file 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tls section: ca_path 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tls section: certificate_file 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tls section: private_key_file 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to tls section: cipher 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         tls {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]:         warnings = "auto"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-config/sql/driver/mysql[9]:       }
Tue May 22 11:46:01 2018 : Memory limit for module rlm_sql_mysql is set to 112 bytes
Tue May 22 11:46:01 2018 : Creating attribute SQL-Group
Tue May 22 11:46:01 2018 : xlat_register: sql
Tue May 22 11:46:01 2018 : map_proc_register: sql
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: header 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: locking {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Pushed parse rule to detail section: log_packet_header {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:     detail auth_log {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/auth-detail-%Y%m%d"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:       header = "%t"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:       permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:       locking = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:       escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:       log_packet_header = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: header 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: locking {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Pushed parse rule to detail section: log_packet_header {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:     detail reply_log {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/reply-detail-%Y%m%d"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:       header = "%t"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:       permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:       locking = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:       escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:       log_packet_header = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: header 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: locking {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Pushed parse rule to detail section: log_packet_header {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:     detail pre_proxy_log {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/pre-proxy-detail-%Y%m%d"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:       header = "%t"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:       permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:       locking = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:       escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:       log_packet_header = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: filename 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: header 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: permissions {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: group 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: locking {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: escape_filenames {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Pushed parse rule to detail section: log_packet_header {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:     detail post_proxy_log {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:       filename = "/usr/local/stow/freeradius-4/var/log/radius/radacct/%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}}/post-proxy-detail-%Y%m%d"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:       header = "%t"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:       permissions = 384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:       locking = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:       escape_filenames = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:       log_packet_header = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]:     }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[708]:   instantiate {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[708]:   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/radiusd.conf[655]:  } # modules
Tue May 22 11:46:01 2018 : #### Instantiating listeners ####
Tue May 22 11:46:01 2018 : Compiling policies in server inner-tunnel { ... }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[48]: compiling - recv Access-Request {...}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/policy.d/filter[156]: Please change attribute reference to '&Outer-Realm-Name = ...'
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/policy.d/filter[193]: Please change attribute reference to '&Inner-Realm-Name = ...'
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[134]: Ignoring "ldap" (see raddb/mods-available/README.rst)
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     if (&State) {
Tue May 22 11:46:01 2018 :      if (&User-Name) {
Tue May 22 11:46:01 2018 :       if (!&session-state:Session-State-User-Name) {
Tue May 22 11:46:01 2018 :        update {
Tue May 22 11:46:01 2018 :         &Module-Failure-Message[*] += 'No cached session-state:Session-State-User-Name'
Tue May 22 11:46:01 2018 :        }
Tue May 22 11:46:01 2018 :        reject
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       if (!&User-Name == &session-state:Session-State-User-Name) {
Tue May 22 11:46:01 2018 :        update {
Tue May 22 11:46:01 2018 :         &Module-Failure-Message[*] += 'User-Name does not match cached session-state:Session-State-User-Name'
Tue May 22 11:46:01 2018 :        }
Tue May 22 11:46:01 2018 :        reject
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :     elseif (&User-Name) {
Tue May 22 11:46:01 2018 :      if (&User-Name =~ / /) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'User-Name contains whitespace'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@[^@]*@/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Multiple @ in User-Name'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /\.\./) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'User-Name contains multiple ..s'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@/ && !&User-Name =~ /@[^.]+(\.[^.]+)+$/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Realm does not have at least one dot separator'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /\.$/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Realm ends with a dot'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@\./) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Realm begins with a dot'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &session-state:Session-State-User-Name[*] := &User-Name[*]
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     if (!&outer.request:User-Name || !&User-Name) {
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &Module-Failure-Message[*] += "User-Name is required for tunneled authentication"
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      reject
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :     if (!&outer.request:User-Name == &User-Name) {
Tue May 22 11:46:01 2018 :      if (&outer.request:User-Name =~ /@([^@]+)$/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Outer-Realm-Name[*] = "%{1}"
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       if (!&outer.request:User-Name =~ /^(anon|@)/) {
Tue May 22 11:46:01 2018 :        update {
Tue May 22 11:46:01 2018 :         &Module-Failure-Message[*] += "User-Name is not anonymized"
Tue May 22 11:46:01 2018 :        }
Tue May 22 11:46:01 2018 :        reject
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      elseif (!&outer.request:User-Name =~ /^anon/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += "User-Name is not anonymized"
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@([^@]+)$/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Inner-Realm-Name[*] = "%{1}"
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       if (&Outer-Realm-Name && !&Inner-Realm-Name == &Outer-Realm-Name && !&Inner-Realm-Name =~ "\\.%{Outer-Realm-Name}$") {
Tue May 22 11:46:01 2018 :        update {
Tue May 22 11:46:01 2018 :         &Module-Failure-Message[*] += "Inner realm '%{Inner-Realm-Name}' and outer realm '%{Outer-Realm-Name}' are not from the same domain."
Tue May 22 11:46:01 2018 :        }
Tue May 22 11:46:01 2018 :        reject
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :    chap
Tue May 22 11:46:01 2018 :    mschap
Tue May 22 11:46:01 2018 :    eap
Tue May 22 11:46:01 2018 :    files
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :    expiration
Tue May 22 11:46:01 2018 :    logintime
Tue May 22 11:46:01 2018 :    pap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[253]: compiling - send Access-Accept {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[302]: compiling - send Access-Reject {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :    attr_filter.access_reject
Tue May 22 11:46:01 2018 :    update {
Tue May 22 11:46:01 2018 :     &outer.session-state:Module-Failure-Message[*] := &Module-Failure-Message[*]
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[183]: Compiling policies - authenticate pap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    pap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[192]: Compiling policies - authenticate chap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    chap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[198]: Compiling policies - authenticate mschap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    mschap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[204]: Compiling policies - authenticate pam {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    pam
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/inner-tunnel[225]: Compiling policies - authenticate eap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    eap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : Compiling policies in server default { ... }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[295]: compiling - recv Access-Request {...}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[442]: Ignoring "ldap" (see raddb/mods-available/README.rst)
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     if (&State) {
Tue May 22 11:46:01 2018 :      if (&User-Name) {
Tue May 22 11:46:01 2018 :       if (!&session-state:Session-State-User-Name) {
Tue May 22 11:46:01 2018 :        update {
Tue May 22 11:46:01 2018 :         &Module-Failure-Message[*] += 'No cached session-state:Session-State-User-Name'
Tue May 22 11:46:01 2018 :        }
Tue May 22 11:46:01 2018 :        reject
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       if (!&User-Name == &session-state:Session-State-User-Name) {
Tue May 22 11:46:01 2018 :        update {
Tue May 22 11:46:01 2018 :         &Module-Failure-Message[*] += 'User-Name does not match cached session-state:Session-State-User-Name'
Tue May 22 11:46:01 2018 :        }
Tue May 22 11:46:01 2018 :        reject
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :     elseif (&User-Name) {
Tue May 22 11:46:01 2018 :      if (&User-Name =~ / /) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'User-Name contains whitespace'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@[^@]*@/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Multiple @ in User-Name'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /\.\./) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'User-Name contains multiple ..s'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@/ && !&User-Name =~ /@[^.]+(\.[^.]+)+$/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Realm does not have at least one dot separator'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /\.$/) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Realm ends with a dot'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      if (&User-Name =~ /@\./) {
Tue May 22 11:46:01 2018 :       update {
Tue May 22 11:46:01 2018 :        &Module-Failure-Message[*] += 'Realm begins with a dot'
Tue May 22 11:46:01 2018 :       }
Tue May 22 11:46:01 2018 :       reject
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &session-state:Session-State-User-Name[*] := &User-Name[*]
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :    chap
Tue May 22 11:46:01 2018 :    mschap
Tue May 22 11:46:01 2018 :    digest
Tue May 22 11:46:01 2018 :    eap
Tue May 22 11:46:01 2018 :    files
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :    expiration
Tue May 22 11:46:01 2018 :    logintime
Tue May 22 11:46:01 2018 :    pap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[483]: compiling - recv Status-Server {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    ok
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[632]: compiling - send Access-Challenge {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    attr_filter.access_challenge
Tue May 22 11:46:01 2018 :    handled
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[643]: compiling - send Access-Accept {...}
Tue May 22 11:46:01 2018 : Instantiating xlat "md5" node 0x2a5b760, new instance 0x2a5d720
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    update {
Tue May 22 11:46:01 2018 :     &reply:[*] += &session-state:[*]
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     update {
Tue May 22 11:46:01 2018 :      &reply:Class[*] = "ai:%{md5:%t,%I,%{Packet-Src-Port},%{%{Packet-Src-IP-Address}:-%{Packet-Src-IPv6-Address}},%{NAS-IP-Address},%{Calling-Station-ID},%{User-Name}}"
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     if (&reply:EAP-Message && &reply:Reply-Message) {
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &reply:Reply-Message[*] !* ANY
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :     else {
Tue May 22 11:46:01 2018 :      noop
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[810]: compiling - send Access-Reject {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :    attr_filter.access_reject
Tue May 22 11:46:01 2018 :    eap
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     if (&reply:EAP-Message && &reply:Reply-Message) {
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &reply:Reply-Message[*] !* ANY
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :     else {
Tue May 22 11:46:01 2018 :      noop
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[852]: Skipping recv Accounting-Request { ...}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[898]: compiling - send Accounting-Response {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    detail
Tue May 22 11:46:01 2018 :    unix
Tue May 22 11:46:01 2018 :    radutmp
Tue May 22 11:46:01 2018 :    sradutmp
Tue May 22 11:46:01 2018 :    sql
Tue May 22 11:46:01 2018 :    attr_filter.accounting_response
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[526]: Compiling policies - authenticate pap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    pap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[535]: Compiling policies - authenticate chap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    chap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[542]: Compiling policies - authenticate mschap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    mschap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[551]: Compiling policies - authenticate digest {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    digest
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[558]: Compiling policies - authenticate pam {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    pam
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[572]: Compiling policies - authenticate ldap {...}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[573]: Ignoring "ldap" (see raddb/mods-available/README.rst)
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[580]: Compiling policies - authenticate eap {...}
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    eap
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/sites-enabled/default[852]: compiling - recv Accounting-Request {...}
Tue May 22 11:46:01 2018 : Instantiating xlat "string" node 0x2a620e0, new instance 0x2a62060
Tue May 22 11:46:01 2018 : Instantiating xlat "md5" node 0x2a62fb0, new instance 0x2a62f20
Tue May 22 11:46:01 2018 : Instantiating xlat "md5" node 0x2a63ff0, new instance 0x2a641b0
Tue May 22 11:46:01 2018 :   group {
Tue May 22 11:46:01 2018 :    group {
Tue May 22 11:46:01 2018 :     if ("%{string:Class}" =~ /ai:([0-9a-f]{32})/) {
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &Acct-Unique-Session-Id[*] := "%{md5:%{1},%{Acct-Session-ID}}"
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :     else {
Tue May 22 11:46:01 2018 :      update {
Tue May 22 11:46:01 2018 :       &Acct-Unique-Session-Id[*] := "%{md5:%{User-Name},%{Acct-Multi-Session-ID},%{Acct-Session-ID},%{%{NAS-IPv6-Address}:-%{NAS-IP-Address}},%{NAS-Identifier},%{NAS-Port-ID},%{NAS-Port}}"
Tue May 22 11:46:01 2018 :      }
Tue May 22 11:46:01 2018 :     }
Tue May 22 11:46:01 2018 :    }
Tue May 22 11:46:01 2018 :    files
Tue May 22 11:46:01 2018 :   }
Tue May 22 11:46:01 2018 : #### Instantiating modules ####
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[45]: Instantiating module "attr_filter.access_challenge"
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/access_challenge
Tue May 22 11:46:01 2018 : Memory limit for module attr_filter.access_challenge is set to 994 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[36]: Instantiating module "attr_filter.access_reject"
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/access_reject
Tue May 22 11:46:01 2018 : [/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/access_reject]:11 Check item "FreeRADIUS-Response-Delay" 	found in filter list for realm "DEFAULT". 
Tue May 22 11:46:01 2018 : [/usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/access_reject]:11 Check item "FreeRADIUS-Response-Delay-USec" 	found in filter list for realm "DEFAULT". 
Tue May 22 11:46:01 2018 : Memory limit for module attr_filter.access_reject is set to 1378 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[55]: Instantiating module "attr_filter.accounting_response"
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/accounting_response
Tue May 22 11:46:01 2018 : Memory limit for module attr_filter.accounting_response is set to 610 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[27]: Instantiating module "attr_filter.post-proxy"
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/post-proxy
Tue May 22 11:46:01 2018 : Memory limit for module attr_filter.post-proxy is set to 3426 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/attr_filter[15]: Instantiating module "attr_filter.pre-proxy"
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/attr_filter/pre-proxy
Tue May 22 11:46:01 2018 : Memory limit for module attr_filter.pre-proxy is set to 2018 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[20]: Instantiating module "auth_log"
Tue May 22 11:46:01 2018 : rlm_detail (auth_log) - 'User-Password' suppressed, will not appear in detail output
Tue May 22 11:46:01 2018 : Memory limit for module auth_log is set to 101 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/cache_eap[4]: Instantiating module "cache_eap"
Tue May 22 11:46:01 2018 : Loading rlm_cache_rbtree with path: /usr/local/stow/freeradius-4/lib/rlm_cache_rbtree.so
Tue May 22 11:46:01 2018 : rlm_cache_rbtree loaded, checking if it's valid
Tue May 22 11:46:01 2018 : rlm_cache_rbtree validated.  Handle address 0x2a6d480, symbol address 0x7fcd5615f120
Tue May 22 11:46:01 2018 : Symbol rlm_cache_rbtree_dict not found
Tue May 22 11:46:01 2018 : Symbol rlm_cache_rbtree_dict_attr not found
Tue May 22 11:46:01 2018 : src/modules/rlm_cache/rlm_cache.c[962]: Loaded module "rlm_cache_rbtree"
Tue May 22 11:46:01 2018 : Memory limit for module rlm_cache_rbtree is set to 16523 bytes
Tue May 22 11:46:01 2018 : Memory limit for module cache_eap is set to 16647 bytes
Tue May 22 11:46:01 2018 : Memory limit for module chap is set to 27 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail[8]: Instantiating module "detail"
Tue May 22 11:46:01 2018 : Memory limit for module detail is set to 101 bytes
Tue May 22 11:46:01 2018 : Memory limit for module dhcpv4 is set to 17 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[15]: Instantiating module "eap"
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 30 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: auto_chain {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: chain {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: verify_depth {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: ca_path 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: ca_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: psk_identity 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: psk_hexphrase 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: psk_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: dh_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: random_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: fragment_size {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: disable_single_dh_use {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: check_crl {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: allow_expired_crl {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: check_cert_cn 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: cipher_list 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: cipher_server_preference {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: allow_renegotiation {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: check_cert_issuer 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: require_client_cert {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: ecdh_curve 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: tls_max_version {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: tls_min_version {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: cache {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: verify {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: ocsp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Pushed parse rule to tls-config section: staple {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:       tls-config tls-common {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         auto_chain = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Evaluating rules for chain[0] section.  Output 0x2a77288
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: format {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: certificate_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: private_key_password 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: private_key_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: ca_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: verify_mode {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]: Pushed parse rule to chain section: include_root_ca {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:         chain {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           format = pem
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           certificate_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/server.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           private_key_password = "whatever"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           private_key_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/server.key"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           ca_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/ca.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           verify_mode = hard
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:           include_root_ca = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[189]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Evaluating rules for chain[1] section.  Output 0x2a77288
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: format {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: certificate_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: private_key_password 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: private_key_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: ca_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: verify_mode {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]: Pushed parse rule to chain section: include_root_ca {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:         chain {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           format = pem
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           certificate_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/ecc/server.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           private_key_password = "whatever"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           private_key_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/ecc/server.key"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           ca_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/ecc/ca.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           verify_mode = hard
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:           include_root_ca = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[275]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         verify_depth = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         ca_path = "/usr/local/stow/freeradius-4/etc/raddb/certs"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         ca_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/ca.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         dh_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/dh"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         fragment_size = 1024
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         check_crl = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         cipher_list = "DEFAULT"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         cipher_server_preference = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         allow_renegotiation = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         ecdh_curve = "prime256v1"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:         tls_min_version = 1.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Evaluating rules for cache section.  Output 0x2a77270
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]: Pushed parse rule to cache section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]: Pushed parse rule to cache section: name 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]: Pushed parse rule to cache section: lifetime {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]: Pushed parse rule to cache section: verify {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]: Pushed parse rule to cache section: require_extended_master_secret {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]: Pushed parse rule to cache section: require_perfect_forward_secrecy {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]:         cache {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]:           lifetime = 86400
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]:           verify = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]:           require_extended_master_secret = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]:           require_perfect_forward_secrecy = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[486]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Evaluating rules for verify section.  Output 0x2a77270
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[592]: Pushed parse rule to verify section: tmpdir 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[592]: Pushed parse rule to verify section: client 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[592]:         verify {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[592]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Evaluating rules for ocsp section.  Output 0x2a77350
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: enable {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: override_cert_url {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: url 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: use_nonce {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]: Pushed parse rule to ocsp section: softfail {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:         ocsp {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:           enable = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:           override_cert_url = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:           url = "http://127.0.0.1/ocsp/"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:           use_nonce = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:           timeout = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:           softfail = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[655]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]: Evaluating rules for staple section.  Output 0x2a773a0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: enable {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: virtual_server 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: override_cert_url {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: url 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: use_nonce {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]: Pushed parse rule to staple section: softfail {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:         staple {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:           enable = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:           override_cert_url = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:           url = "http://127.0.0.1/ocsp/"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:           use_nonce = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:           timeout = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:           softfail = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[736]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap[161]:       }
Tue May 22 11:46:01 2018 : tls - Found 1 server certificate chain(s)
Tue May 22 11:46:01 2018 : tls - Number of chains configured (2) does not match chains set (1)
Tue May 22 11:46:01 2018 : tls - Only one chain per key type is allowed, check config for duplicates
Tue May 22 11:46:01 2018 : tls - RSA chain
Tue May 22 11:46:01 2018 : tls - [0] RSA /C=FR/ST=Radius/O=Example Inc./CN=Example Server Certificate/emailAddress=admin@example.org
Tue May 22 11:46:01 2018 : tls - Configured ciphers (by priority)
Tue May 22 11:46:01 2018 : tls - [0] ECDHE-ECDSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [1] ECDHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [2] DHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [3] ECDHE-ECDSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [4] ECDHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [5] DHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [6] ECDHE-ECDSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [7] ECDHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [8] DHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [9] ECDHE-ECDSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [10] ECDHE-RSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [11] DHE-RSA-AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [12] ECDHE-ECDSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [13] ECDHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [14] DHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [15] ECDHE-ECDSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [16] ECDHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [17] DHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [18] ECDHE-ECDSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [19] ECDHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [20] DHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [21] RSA-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [22] DHE-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [23] RSA-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [24] DHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [25] ECDHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [26] AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [27] PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [28] PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [29] RSA-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [30] DHE-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [31] AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [32] PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [33] AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [34] AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [35] ECDHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [36] ECDHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [37] SRP-RSA-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [38] SRP-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [39] RSA-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [40] DHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [41] RSA-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [42] DHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [43] AES256-SHA
Tue May 22 11:46:01 2018 : tls - [44] PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [45] PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [46] ECDHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [47] ECDHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [48] SRP-RSA-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [49] SRP-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [50] RSA-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [51] DHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [52] RSA-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [53] DHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [54] AES128-SHA
Tue May 22 11:46:01 2018 : tls - [55] PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [56] PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - Found 1 server certificate chain(s)
Tue May 22 11:46:01 2018 : tls - Number of chains configured (2) does not match chains set (1)
Tue May 22 11:46:01 2018 : tls - Only one chain per key type is allowed, check config for duplicates
Tue May 22 11:46:01 2018 : tls - RSA chain
Tue May 22 11:46:01 2018 : tls - [0] RSA /C=FR/ST=Radius/O=Example Inc./CN=Example Server Certificate/emailAddress=admin@example.org
Tue May 22 11:46:01 2018 : tls - Configured ciphers (by priority)
Tue May 22 11:46:01 2018 : tls - [0] ECDHE-ECDSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [1] ECDHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [2] DHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [3] ECDHE-ECDSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [4] ECDHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [5] DHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [6] ECDHE-ECDSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [7] ECDHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [8] DHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [9] ECDHE-ECDSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [10] ECDHE-RSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [11] DHE-RSA-AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [12] ECDHE-ECDSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [13] ECDHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [14] DHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [15] ECDHE-ECDSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [16] ECDHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [17] DHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [18] ECDHE-ECDSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [19] ECDHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [20] DHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [21] RSA-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [22] DHE-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [23] RSA-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [24] DHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [25] ECDHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [26] AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [27] PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [28] PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [29] RSA-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [30] DHE-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [31] AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [32] PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [33] AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [34] AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [35] ECDHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [36] ECDHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [37] SRP-RSA-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [38] SRP-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [39] RSA-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [40] DHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [41] RSA-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [42] DHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [43] AES256-SHA
Tue May 22 11:46:01 2018 : tls - [44] PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [45] PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [46] ECDHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [47] ECDHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [48] SRP-RSA-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [49] SRP-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [50] RSA-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [51] DHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [52] RSA-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [53] DHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [54] AES128-SHA
Tue May 22 11:46:01 2018 : tls - [55] PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [56] PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 46 bytes
Tue May 22 11:46:01 2018 : tls - Using cached TLS configuration from previous invocation
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 55 bytes
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 60 bytes
Tue May 22 11:46:01 2018 : tls - Using cached TLS configuration from previous invocation
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 79 bytes
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 30 bytes
Tue May 22 11:46:01 2018 : Memory limit for module eap is set to 3646 bytes
Tue May 22 11:46:01 2018 : Memory limit for module echo is set to 67 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/passwd[49]: Instantiating module "etc_passwd"
Tue May 22 11:46:01 2018 : rlm_passwd - nfields: 3 keyfield 0(User-Name) listable: no
Tue May 22 11:46:01 2018 : Memory limit for module etc_passwd is set to 93 bytes
Tue May 22 11:46:01 2018 : Memory limit for module exec is set to 67 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/expiration[12]: Instantiating module "expiration"
Tue May 22 11:46:01 2018 : Memory limit for module expr is set to 27 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[38]: Instantiating module "fail"
Tue May 22 11:46:01 2018 : Memory limit for module fail is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/files[9]: Instantiating module "files"
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/files/authorize
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/files/accounting
Tue May 22 11:46:01 2018 : Reading file /usr/local/stow/freeradius-4/etc/raddb/mods-config/files/pre-proxy
Tue May 22 11:46:01 2018 : Memory limit for module files is set to 9777 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[44]: Instantiating module "handled"
Tue May 22 11:46:01 2018 : Memory limit for module handled is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[15]: Instantiating module "inner-eap"
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 30 bytes
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 60 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: auto_chain {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: chain {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: verify_depth {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: ca_path 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: ca_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: psk_identity 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: psk_hexphrase 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: psk_query 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: dh_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: random_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: fragment_size {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: disable_single_dh_use {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: check_crl {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: allow_expired_crl {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: check_cert_cn 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: cipher_list 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: cipher_server_preference {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: allow_renegotiation {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: check_cert_issuer 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: require_client_cert {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: ecdh_curve 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: tls_max_version {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: tls_min_version {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: cache {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: verify {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: ocsp {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Pushed parse rule to tls-config section: staple {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:       tls-config tls-peer {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         auto_chain = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Evaluating rules for chain[0] section.  Output 0x2acc358
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: format {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: certificate_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: private_key_password 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: private_key_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: ca_file 
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: verify_mode {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]: Pushed parse rule to chain section: include_root_ca {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:         chain {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           format = pem
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           certificate_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/server.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           private_key_password = "whatever"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           private_key_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/server.key"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           ca_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/ca.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           verify_mode = hard
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:           include_root_ca = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[86]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         verify_depth = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         ca_path = "/usr/local/stow/freeradius-4/etc/raddb/certs"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         ca_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/rsa/ca.pem"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         dh_file = "/usr/local/stow/freeradius-4/etc/raddb/certs/dh"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         fragment_size = 16384
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         check_crl = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         cipher_server_preference = yes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         allow_renegotiation = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         ecdh_curve = "prime256v1"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:         tls_min_version = 1.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Allocating fake section "cache"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Evaluating rules for cache section.  Output 0x2acc340
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to cache section: virtual_server 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to cache section: name 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to cache section: lifetime {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to cache section: verify {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to cache section: require_extended_master_secret {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to cache section: require_perfect_forward_secrecy {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         cache {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           lifetime = 86400
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           verify = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           require_extended_master_secret = yes
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           require_perfect_forward_secrecy = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Allocating fake section "verify"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Evaluating rules for verify section.  Output 0x2acc340
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to verify section: tmpdir 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to verify section: client 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         verify {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Allocating fake section "ocsp"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Evaluating rules for ocsp section.  Output 0x2acc420
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: enable {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: virtual_server 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: override_cert_url {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: url 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: use_nonce {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to ocsp section: softfail {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         ocsp {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           enable = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           override_cert_url = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           use_nonce = yes
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           timeout = 0
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           softfail = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Allocating fake section "staple"
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]: Evaluating rules for staple section.  Output 0x2acc470
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: enable {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: virtual_server 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: override_cert_url {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: url 
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: use_nonce {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: timeout {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]: Pushed parse rule to staple section: softfail {}
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         staple {
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           enable = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           override_cert_url = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           use_nonce = yes
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           timeout = 0
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:           softfail = no
Tue May 22 11:46:01 2018 : src/main/cf_parse.c[893]:         }
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/eap_inner[66]:       }
Tue May 22 11:46:01 2018 : tls - Found 1 server certificate chain(s)
Tue May 22 11:46:01 2018 : tls - RSA chain
Tue May 22 11:46:01 2018 : tls - [0] RSA /C=FR/ST=Radius/O=Example Inc./CN=Example Server Certificate/emailAddress=admin@example.org
Tue May 22 11:46:01 2018 : tls - Configured ciphers (by priority)
Tue May 22 11:46:01 2018 : tls - [0] ECDHE-ECDSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [1] ECDHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [2] DHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [3] ECDHE-ECDSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [4] ECDHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [5] DHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [6] ECDHE-ECDSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [7] ECDHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [8] DHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [9] ECDHE-ECDSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [10] ECDHE-RSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [11] DHE-RSA-AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [12] ECDHE-ECDSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [13] ECDHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [14] DHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [15] ECDHE-ECDSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [16] ECDHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [17] DHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [18] ECDHE-ECDSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [19] ECDHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [20] DHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [21] RSA-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [22] DHE-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [23] RSA-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [24] DHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [25] ECDHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [26] AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [27] PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [28] PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [29] RSA-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [30] DHE-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [31] AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [32] PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [33] AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [34] AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [35] ECDHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [36] ECDHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [37] SRP-RSA-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [38] SRP-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [39] RSA-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [40] DHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [41] RSA-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [42] DHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [43] AES256-SHA
Tue May 22 11:46:01 2018 : tls - [44] PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [45] PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [46] ECDHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [47] ECDHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [48] SRP-RSA-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [49] SRP-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [50] RSA-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [51] DHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [52] RSA-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [53] DHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [54] AES128-SHA
Tue May 22 11:46:01 2018 : tls - [55] PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [56] PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - Found 1 server certificate chain(s)
Tue May 22 11:46:01 2018 : tls - RSA chain
Tue May 22 11:46:01 2018 : tls - [0] RSA /C=FR/ST=Radius/O=Example Inc./CN=Example Server Certificate/emailAddress=admin@example.org
Tue May 22 11:46:01 2018 : tls - Configured ciphers (by priority)
Tue May 22 11:46:01 2018 : tls - [0] ECDHE-ECDSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [1] ECDHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [2] DHE-RSA-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [3] ECDHE-ECDSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [4] ECDHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [5] DHE-RSA-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [6] ECDHE-ECDSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [7] ECDHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [8] DHE-RSA-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [9] ECDHE-ECDSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [10] ECDHE-RSA-AES256-SHA384
Tue May 22 11:46:01 2018 : tls - [11] DHE-RSA-AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [12] ECDHE-ECDSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [13] ECDHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [14] DHE-RSA-AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [15] ECDHE-ECDSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [16] ECDHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [17] DHE-RSA-AES256-SHA
Tue May 22 11:46:01 2018 : tls - [18] ECDHE-ECDSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [19] ECDHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [20] DHE-RSA-AES128-SHA
Tue May 22 11:46:01 2018 : tls - [21] RSA-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [22] DHE-PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [23] RSA-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [24] DHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [25] ECDHE-PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [26] AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [27] PSK-AES256-GCM-SHA384
Tue May 22 11:46:01 2018 : tls - [28] PSK-CHACHA20-POLY1305
Tue May 22 11:46:01 2018 : tls - [29] RSA-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [30] DHE-PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [31] AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [32] PSK-AES128-GCM-SHA256
Tue May 22 11:46:01 2018 : tls - [33] AES256-SHA256
Tue May 22 11:46:01 2018 : tls - [34] AES128-SHA256
Tue May 22 11:46:01 2018 : tls - [35] ECDHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [36] ECDHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [37] SRP-RSA-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [38] SRP-AES-256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [39] RSA-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [40] DHE-PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [41] RSA-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [42] DHE-PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [43] AES256-SHA
Tue May 22 11:46:01 2018 : tls - [44] PSK-AES256-CBC-SHA384
Tue May 22 11:46:01 2018 : tls - [45] PSK-AES256-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [46] ECDHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [47] ECDHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [48] SRP-RSA-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [49] SRP-AES-128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [50] RSA-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [51] DHE-PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [52] RSA-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [53] DHE-PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : tls - [54] AES128-SHA
Tue May 22 11:46:01 2018 : tls - [55] PSK-AES128-CBC-SHA256
Tue May 22 11:46:01 2018 : tls - [56] PSK-AES128-CBC-SHA
Tue May 22 11:46:01 2018 : Memory limit for module (null) is set to 46 bytes
Tue May 22 11:46:01 2018 : Memory limit for module inner-eap is set to 3338 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[47]: Instantiating module "invalid"
Tue May 22 11:46:01 2018 : Memory limit for module invalid is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[12]: Instantiating module "linelog"
Tue May 22 11:46:01 2018 : Memory limit for module linelog is set to 366 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/linelog[239]: Instantiating module "log_accounting"
Tue May 22 11:46:01 2018 : Memory limit for module log_accounting is set to 366 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/logintime[16]: Instantiating module "logintime"
Tue May 22 11:46:01 2018 : Memory limit for module logintime is set to 20 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/mschap[10]: Instantiating module "mschap"
Tue May 22 11:46:01 2018 : mschap: using internal authentication
Tue May 22 11:46:01 2018 : Memory limit for module mschap is set to 125 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[56]: Instantiating module "noop"
Tue May 22 11:46:01 2018 : Memory limit for module noop is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[53]: Instantiating module "notfound"
Tue May 22 11:46:01 2018 : Memory limit for module notfound is set to 53 bytes
Tue May 22 11:46:01 2018 : Instantiating xlat "mschap" node 0x2af4730, new instance 0x2af0f40
Tue May 22 11:46:01 2018 : Memory limit for module ntlm_auth is set to 67 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[41]: Instantiating module "ok"
Tue May 22 11:46:01 2018 : Memory limit for module ok is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/pam[15]: Instantiating module "pam"
Tue May 22 11:46:01 2018 : Memory limit for module pam is set to 18 bytes
Tue May 22 11:46:01 2018 : Memory limit for module pap is set to 34 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[73]: Instantiating module "post_proxy_log"
Tue May 22 11:46:01 2018 : Memory limit for module post_proxy_log is set to 101 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[57]: Instantiating module "pre_proxy_log"
Tue May 22 11:46:01 2018 : Memory limit for module pre_proxy_log is set to 101 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/radius[36]: Instantiating module "radius"
Tue May 22 11:46:01 2018 : Memory limit for module radius is set to 1430 bytes
Tue May 22 11:46:01 2018 : Memory limit for module radutmp is set to 54 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[35]: Instantiating module "reject"
Tue May 22 11:46:01 2018 : Memory limit for module reject is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/detail.log[45]: Instantiating module "reply_log"
Tue May 22 11:46:01 2018 : Memory limit for module reply_log is set to 101 bytes
Tue May 22 11:46:01 2018 : Memory limit for module soh is set to 26 bytes
Tue May 22 11:46:01 2018 : Instantiating xlat "tolower" node 0x2aef150, new instance 0x2aef030
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af4740, new instance 0x2aefba0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2aef120, new instance 0x2af0c40
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af0ac0, new instance 0x2ae43e0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af4740, new instance 0x2ae43e0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2aef120, new instance 0x2af0c40
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af4d50, new instance 0x2aefba0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af3070, new instance 0x2afbd00
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af36d0, new instance 0x2afbe10
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af10c0, new instance 0x2aefaa0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af12f0, new instance 0x2aefba0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2afbc40, new instance 0x2aefc20
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af1e30, new instance 0x2af0b90
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2af3ba0, new instance 0x2b00350
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2afb1f0, new instance 0x2b00460
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2aef170, new instance 0x2afbdc0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2afa270, new instance 0x2b016d0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2afb6c0, new instance 0x2b017e0
Tue May 22 11:46:01 2018 : Instantiating xlat "integer" node 0x2afbf30, new instance 0x2b018f0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[19]: Instantiating module "sql"
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Attempting to connect to database "radius_serv"
Tue May 22 11:46:01 2018 : rlm_sql (sql): Using local pool section
Tue May 22 11:46:01 2018 : rlm_sql (sql): No pool reference found for config item "sql.pool"
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Initialising connection pool
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: start {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: min {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: max {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: max_pending {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: spare {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: uses {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: lifetime {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: cleanup_delay {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: cleanup_interval {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: idle_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: connect_timeout {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: held_trigger_min {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: held_trigger_max {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: retry_delay {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]: Pushed parse rule to pool section: spread {}
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:       pool {
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         start = 5
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         min = 3
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         max = 32
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         max_pending = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         spare = 10
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         uses = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         lifetime = 0
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         cleanup_interval = 30
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         idle_timeout = 60
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         connect_timeout = 3.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         held_trigger_min = 0.000000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         held_trigger_max = 0.500000
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         retry_delay = 30
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:         spread = no
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/sql[137]:       }
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Opening additional connection (0), 1 of 32 pending slots used
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Starting connect to MySQL server
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Connected to database 'radius_serv' on Localhost via UNIX socket, server version 5.7.20-0ubuntu0.16.04.1, protocol version 10
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Opening additional connection (1), 1 of 31 pending slots used
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Starting connect to MySQL server
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Connected to database 'radius_serv' on Localhost via UNIX socket, server version 5.7.20-0ubuntu0.16.04.1, protocol version 10
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Opening additional connection (2), 1 of 30 pending slots used
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Starting connect to MySQL server
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Connected to database 'radius_serv' on Localhost via UNIX socket, server version 5.7.20-0ubuntu0.16.04.1, protocol version 10
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Opening additional connection (3), 1 of 29 pending slots used
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Starting connect to MySQL server
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Connected to database 'radius_serv' on Localhost via UNIX socket, server version 5.7.20-0ubuntu0.16.04.1, protocol version 10
Tue May 22 11:46:01 2018 : rlm_sql (sql) - Opening additional connection (4), 1 of 28 pending slots used
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Starting connect to MySQL server
Tue May 22 11:46:01 2018 : rlm_sql_mysql - Connected to database 'radius_serv' on Localhost via UNIX socket, server version 5.7.20-0ubuntu0.16.04.1, protocol version 10
Tue May 22 11:46:01 2018 : rlm_sql (sql): Adding pool reference 0x2aeef50 to config item "sql.pool"
Tue May 22 11:46:01 2018 : Memory limit for module sql is set to 850 bytes
Tue May 22 11:46:01 2018 : Memory limit for module sradutmp is set to 54 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/stats[15]: Instantiating module "stats"
Tue May 22 11:46:01 2018 : Memory limit for module stats is set to 516 bytes
Tue May 22 11:46:01 2018 : Memory limit for module unix is set to 27 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[59]: Instantiating module "updated"
Tue May 22 11:46:01 2018 : Memory limit for module updated is set to 53 bytes
Tue May 22 11:46:01 2018 : /usr/local/stow/freeradius-4/etc/raddb/mods-enabled/always[50]: Instantiating module "userlock"
Tue May 22 11:46:01 2018 : Memory limit for module userlock is set to 53 bytes
Tue May 22 11:46:01 2018 : Memory limit for all modules is set to 51546 bytes
Tue May 22 11:46:01 2018 : Worker alloced attr_filter thread instance data (0x2b5fd50/(nil))
Tue May 22 11:46:01 2018 : Worker alloced attr_filter thread instance data (0x2b5fe80/(nil))
Tue May 22 11:46:01 2018 : Worker alloced attr_filter thread instance data (0x2b5ffb0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced attr_filter thread instance data (0x2b600e0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced attr_filter thread instance data (0x2b60210/(nil))
Tue May 22 11:46:01 2018 : Worker alloced detail thread instance data (0x2b60340/(nil))
Tue May 22 11:46:01 2018 : Worker alloced cache thread instance data (0x2b60470/(nil))
Tue May 22 11:46:01 2018 : Worker alloced chap thread instance data (0x2b605a0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced dynamic_clients thread instance data (0x2b606d0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced detail thread instance data (0x2b60800/(nil))
Tue May 22 11:46:01 2018 : Worker alloced dhcpv4 thread instance data (0x2b60930/(nil))
Tue May 22 11:46:01 2018 : Worker alloced digest thread instance data (0x2b60a60/(nil))
Tue May 22 11:46:01 2018 : Worker alloced eap thread instance data (0x2b60b00/(nil))
Tue May 22 11:46:01 2018 : Worker alloced exec thread instance data (0x2b60c30/(nil))
Tue May 22 11:46:01 2018 : Worker alloced passwd thread instance data (0x2b60d60/(nil))
Tue May 22 11:46:01 2018 : Worker alloced exec thread instance data (0x2b60e90/(nil))
Tue May 22 11:46:01 2018 : Worker alloced expiration thread instance data (0x2b60fc0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced expr thread instance data (0x2b61060/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b61190/(nil))
Tue May 22 11:46:01 2018 : Worker alloced files thread instance data (0x2b612c0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b613f0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced eap thread instance data (0x2b61520/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b61650/(nil))
Tue May 22 11:46:01 2018 : Worker alloced linelog thread instance data (0x2b61780/(nil))
Tue May 22 11:46:01 2018 : Worker alloced linelog thread instance data (0x2b618b0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced logintime thread instance data (0x2b619e0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced mschap thread instance data (0x2b61b10/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b61c40/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b61d70/(nil))
Tue May 22 11:46:01 2018 : Worker alloced exec thread instance data (0x2b61ea0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b61fd0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced pam thread instance data (0x2b62100/(nil))
Tue May 22 11:46:01 2018 : Worker alloced pap thread instance data (0x2b62230/(nil))
Tue May 22 11:46:01 2018 : Worker alloced detail thread instance data (0x2b62360/(nil))
Tue May 22 11:46:01 2018 : Worker alloced detail thread instance data (0x2b62490/(nil))
Tue May 22 11:46:01 2018 : Worker alloced radius thread instance data (0x2b625c0/0x2b62660)
Tue May 22 11:46:01 2018 : [1] radius - Connection initialising
Tue May 22 11:46:01 2018 : [1] radius - Changed state HALTED -> INIT
Tue May 22 11:46:01 2018 : [1] radius - Connection initialised
Tue May 22 11:46:01 2018 : [1] radius - Changed state INIT -> CONNECTING
Tue May 22 11:46:01 2018 : Worker alloced radutmp thread instance data (0x2b6fb90/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b6fcc0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced detail thread instance data (0x2b6fdf0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced soh thread instance data (0x2b6ff20/(nil))
Tue May 22 11:46:01 2018 : Worker alloced sql thread instance data (0x2b70050/(nil))
Tue May 22 11:46:01 2018 : Worker alloced radutmp thread instance data (0x2b70180/(nil))
Tue May 22 11:46:01 2018 : Worker alloced stats thread instance data (0x2b702b0/0x2b70350)
Tue May 22 11:46:01 2018 : Worker alloced unix thread instance data (0x2b709b0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced unpack thread instance data (0x2b70ae0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b70b80/(nil))
Tue May 22 11:46:01 2018 : Worker alloced always thread instance data (0x2b70cb0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced utf8 thread instance data (0x2b70de0/(nil))
Tue May 22 11:46:01 2018 : Worker alloced xlat thread instance (0x2b70fd0/(nil))
Tue May 22 11:46:01 2018 : Instantiating xlat "string" node 0x2a620e0, instance 0x2a62060, new thread instance 0x2b70fd0
Tue May 22 11:46:01 2018 : Worker alloced xlat thread instance (0x2b710f0/(nil))
Tue May 22 11:46:01 2018 : Instantiating xlat "md5" node 0x2a5b760, instance 0x2a5d720, new thread instance 0x2b710f0
Tue May 22 11:46:01 2018 : Worker alloced xlat thread instance (0x2b71210/(nil))
Tue May 22 11:46:01 2018 : Instantiating xlat "md5" node 0x2a63ff0, instance 0x2a641b0, new thread instance 0x2b71210
Tue May 22 11:46:01 2018 : Worker alloced xlat thread instance (0x2b71330/(nil))
Tue May 22 11:46:01 2018 : Instantiating xlat "md5" node 0x2a62fb0, instance 0x2a62f20, new thread instance 0x2b71330
Tue May 22 11:46:01 2018 : Scheduler created in single-threaded mode
Tue May 22 11:46:01 2018 : #### Opening listener interfaces ####
Tue May 22 11:46:01 2018 : Listening on radius address proto tcp server 127.0.0.1 port 18120 bound to virtual server inner-tunnel
Tue May 22 11:46:01 2018 : Opened listener for radius
Tue May 22 11:46:01 2018 : Listening on radius address proto udp server * port 1812 bound to virtual server default
Tue May 22 11:46:01 2018 : Opened listener for radius
Tue May 22 11:46:01 2018 : Listening on radius address proto udp server * port 1813 bound to virtual server default
Tue May 22 11:46:01 2018 : Opened listener for radius
Tue May 22 11:46:01 2018 : Memory limit for global configuration is set to 678885 bytes
Tue May 22 11:46:01 2018 : Created signal pipe.  Read end FD 18, write end FD 19
Tue May 22 11:46:01 2018 : Waking up in 4.9 seconds.
Tue May 22 11:46:01 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:01 2018 : 	requests 0, decoded 0, replied 0 active 0
Tue May 22 11:46:01 2018 : radius - Connection open - proto udp local 0.0.0.0 port 39382 remote 127.0.0.1 port 1812
Tue May 22 11:46:01 2018 : radius - Setting idle timeout to +5.000000 for connection proto udp local 0.0.0.0 port 39382 remote 127.0.0.1 port 1812
Tue May 22 11:46:01 2018 : Status check packet will be 
Tue May 22 11:46:01 2018 : (radius)    &Event-Timestamp = Jan  1 1970 03:00:00 MSK
Tue May 22 11:46:01 2018 : (radius)    &NAS-Identifier = "status check - are you alive?"
Tue May 22 11:46:01 2018 : radius - Allocated Status-Server ID 0 for status checks on connection proto udp local 0.0.0.0 port 39382 remote 127.0.0.1 port 1812
Tue May 22 11:46:01 2018 : [1] radius - Connection established
Tue May 22 11:46:01 2018 : [1] radius - Changed state CONNECTING -> CONNECTED
Tue May 22 11:46:01 2018 : Using new socket with FD 15
Tue May 22 11:46:01 2018 : Using new socket with FD 16
Tue May 22 11:46:01 2018 : Using new socket with FD 17
Tue May 22 11:46:01 2018 : 	checking timeouts
Tue May 22 11:46:01 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:01 2018 : Waking up in 4.9 seconds.
Tue May 22 11:46:01 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:01 2018 : 	requests 0, decoded 0, replied 0 active 0
Tue May 22 11:46:01 2018 : Worker 0 was sleeping, not re-signaling
Tue May 22 11:46:01 2018 : 	--> channel open
Tue May 22 11:46:01 2018 : 	received channel 0x2b82df0 into array entry 0
Tue May 22 11:46:01 2018 : 	checking timeouts
Tue May 22 11:46:01 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:01 2018 : Waking up in 4.9 seconds.
Tue May 22 11:46:01 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:01 2018 : 	requests 0, decoded 0, replied 0 active 0

rrrTue May 22 11:46:06 2018 : radius - Idle timeout for connection proto udp local 0.0.0.0 port 39382 remote 127.0.0.1 port 1812
Tue May 22 11:46:06 2018 : [1] radius - Closing connection (14)
Tue May 22 11:46:06 2018 : radius - Connection closed - proto udp local 0.0.0.0 port 39382 remote 127.0.0.1 port 1812
Tue May 22 11:46:06 2018 : radius - Freeing status check ID 0 on connection proto udp local 0.0.0.0 port 39382 remote 127.0.0.1 port 1812
Tue May 22 11:46:06 2018 : 	checking timeouts
Tue May 22 11:46:06 2018 : Worker 0 localized and decode lists are empty
Tue May 22 11:46:06 2018 : Ready to process requests
Tue May 22 11:46:06 2018 : 	sleeping running 0, localized 0, to_decode 0
Tue May 22 11:46:06 2018 : 	requests 0, decoded 0, replied 0 active 0
Tue May 22 11:46:06 2018 : Worker 0 was sleeping, not re-signaling

```
