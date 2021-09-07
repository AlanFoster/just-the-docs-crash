---
layout: "default"
title: "Metasploit Loginpalooza"
parent: "Miscellaneous"
grand_parent: "Development"
---

The Loginpalooza contest is over! Congrats and thanks to [@TomSellers](https://www.github.com/TomSellers), [@ChrisTuncer](https://www.github.com/ChrisTuncer), and [@0a2940](https://www.github.com/0a2940)!

The list of [modules to refactor](#modules-to-refactor) is still here. Modules that get refactored should be removed from the list entirely.

If you'd like to learn how to convert your favorite existing module, or write a new module, using the new LoginScanner mixin and the Credentials gem, please take a look at [Creating Metasploit Framework LoginScanners]({% link docs/development/developing-modules/Creating-Metasploit-Framework-LoginScanners.md %}).

# Modules to Refactor

- [ ] [auxiliary/gather/apache_rave_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/apache_rave_creds.rb)
- [ ] [auxiliary/scanner/http/apache_userdir_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/apache_userdir_enum.rb)
- [ ] [auxiliary/voip/asterisk_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/voip/asterisk_login.rb)
- [ ] [post/osx/gather/autologin_password.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/osx/gather/autologin_password.rb)
- [ ] [auxiliary/scanner/http/axis_local_file_include.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/axis_local_file_include.rb)
- [ ] [exploits/windows/http/ca_arcserve_rpc_authbypass.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/exploits/windows/http/ca_arcserve_rpc_authbypass.rb)
- [ ] [auxiliary/scanner/misc/cctv_dvr_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/misc/cctv_dvr_login.rb)
- [ ] [auxiliary/scanner/http/cisco_asa_asdm.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/cisco_asa_asdm.rb)
- [ ] [auxiliary/scanner/http/cisco_ironport_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/cisco_ironport_enum.rb)
- [ ] [auxiliary/scanner/couchdb/couchdb_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/couchdb/couchdb_login.rb)
- [ ] [auxiliary/gather/d20pass.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/d20pass.rb)
- [ ] [auxiliary/scanner/http/dell_idrac.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/dell_idrac.rb)
- [ ] [auxiliary/scanner/http/dlink_dir_300_615_http_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/dlink_dir_300_615_http_login.rb)
- [ ] [auxiliary/scanner/http/dlink_dir_615h_http_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/dlink_dir_615h_http_login.rb)
- [ ] [auxiliary/scanner/http/dlink_dir_session_cgi_http_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/dlink_dir_session_cgi_http_login.rb)
- [ ] [auxiliary/scanner/http/dolibarr_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/dolibarr_login.rb)
- [ ] [auxiliary/gather/doliwamp_traversal_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/doliwamp_traversal_creds.rb)
- [ ] [auxiliary/server/capture/drda.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/server/capture/drda.rb)
- [ ] [auxiliary/scanner/http/drupal_views_user_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/drupal_views_user_enum.rb)
- [ ] [auxiliary/scanner/misc/dvr_config_disclosure.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/misc/dvr_config_disclosure.rb)
- [ ] [auxiliary/gather/eaton_nsm_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/eaton_nsm_creds.rb)
- [ ] [auxiliary/scanner/http/ektron_cms400net.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/ektron_cms400net.rb)
- [ ] [post/osx/gather/enum_osx.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/osx/gather/enum_osx.rb)
- [x] [post/windows/gather/enum_snmp.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/enum_snmp.rb)
- [ ] [post/windows/gather/enum_tomcat.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/enum_tomcat.rb)
- [ ] [post/multi/gather/filezilla_client_cred.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/multi/gather/filezilla_client_cred.rb)
- [ ] [exploits/multi/http/glassfish_deployer.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/exploits/multi/http/glassfish_deployer.rb)
- [x] [auxiliary/scanner/http/glassfish_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/glassfish_login.rb)
- [ ] [auxiliary/gather/hp_snac_domain_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/hp_snac_domain_creds.rb)
- [ ] [auxiliary/scanner/http/infovista_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/infovista_enum.rb)
- [ ] [auxiliary/scanner/ipmi/ipmi_dumphashes.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/ipmi/ipmi_dumphashes.rb)
- [ ] [auxiliary/scanner/oracle/isqlplus_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/oracle/isqlplus_login.rb)
- [ ] [auxiliary/scanner/oracle/isqlplus_sidbrute.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/oracle/isqlplus_sidbrute.rb)
- [ ] [exploits/linux/http/kloxo_sqli.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/exploits/linux/http/kloxo_sqli.rb)
- [ ] [auxiliary/scanner/scada/koyo_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/scada/koyo_login.rb)
- [ ] [auxiliary/scanner/telnet/lantronix_telnet_password.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/telnet/lantronix_telnet_password.rb)
- [ ] [auxiliary/scanner/lotus/lotus_domino_hashes.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/lotus/lotus_domino_hashes.rb)
- [ ] [auxiliary/scanner/lotus/lotus_domino_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/lotus/lotus_domino_login.rb)
- [ ] [auxiliary/scanner/mongodb/mongodb_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/mongodb/mongodb_login.rb)
- [ ] [post/linux/gather/mount_cifs_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/linux/gather/mount_cifs_creds.rb)
- [ ] [auxiliary/scanner/msf/msf_rpc_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/msf/msf_rpc_login.rb)
- [ ] [auxiliary/scanner/msf/msf_web_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/msf/msf_web_login.rb)
- [ ] [auxiliary/scanner/nessus/nessus_ntp_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/nessus/nessus_ntp_login.rb)
- [ ] [auxiliary/scanner/nessus/nessus_xmlrpc_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/nessus/nessus_xmlrpc_login.rb)
- [ ] [auxiliary/scanner/nexpose/nexpose_api_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/nexpose/nexpose_api_login.rb)
- [ ] [auxiliary/scanner/http/novell_mdm_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/novell_mdm_creds.rb)
- [ ] [auxiliary/scanner/misc/oki_scanner.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/misc/oki_scanner.rb)
- [ ] [auxiliary/scanner/http/openmind_messageos_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/openmind_messageos_login.rb)
- [ ] [auxiliary/scanner/openvas/openvas_gsad_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/openvas/openvas_gsad_login.rb)
- [ ] [auxiliary/scanner/openvas/openvas_omp_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/openvas/openvas_omp_login.rb)
- [ ] [auxiliary/scanner/openvas/openvas_otp_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/openvas/openvas_otp_login.rb)
- [ ] [auxiliary/scanner/http/oracle_ilom_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/oracle_ilom_login.rb)
- [ ] [post/windows/gather/credentials/outlook.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/outlook.rb)
- [ ] [auxiliary/scanner/http/owa_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/owa_login.rb)
- [ ] [auxiliary/scanner/pcanywhere/pcanywhere_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/pcanywhere/pcanywhere_login.rb)
- [ ] [post/multi/gather/pgpass_creds.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/multi/gather/pgpass_creds.rb)
- [ ] [auxiliary/scanner/postgres/postgres_version.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/postgres/postgres_version.rb)
- [ ] [post/linux/gather/pptpd_chap_secrets.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/linux/gather/pptpd_chap_secrets.rb)
- [ ] [auxiliary/scanner/http/radware_appdirector_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/radware_appdirector_enum.rb)
- [ ] [auxiliary/scanner/misc/raysharp_dvr_passwords.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/misc/raysharp_dvr_passwords.rb)
- [ ] [post/windows/gather/credentials/razer_synapse.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/razer_synapse.rb)
- [ ] [post/windows/gather/credentials/razorsql.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/razorsql.rb)
- [ ] [auxiliary/scanner/rservices/rexec_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/rservices/rexec_login.rb)
- [ ] [auxiliary/scanner/http/rfcode_reader_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/rfcode_reader_enum.rb)
- [ ] [auxiliary/scanner/rservices/rlogin_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/rservices/rlogin_login.rb)
- [ ] [auxiliary/scanner/misc/rosewill_rxs3211_passwords.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/misc/rosewill_rxs3211_passwords.rb)
- [ ] [auxiliary/scanner/rservices/rsh_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/rservices/rsh_login.rb)
- [ ] [auxiliary/scanner/http/sap_businessobjects_user_brute.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/sap_businessobjects_user_brute.rb)
- [ ] [auxiliary/scanner/http/sap_businessobjects_user_brute_web.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/sap_businessobjects_user_brute_web.rb)
- [ ] [auxiliary/scanner/http/sap_businessobjects_user_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/sap_businessobjects_user_enum.rb)
- [ ] [auxiliary/scanner/sap/sap_ctc_verb_tampering_user_mgmt.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/sap/sap_ctc_verb_tampering_user_mgmt.rb)
- [ ] [auxiliary/scanner/sap/sap_mgmt_con_brute_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/sap/sap_mgmt_con_brute_login.rb)
- [ ] [auxiliary/scanner/sap/sap_soap_bapi_user_create1.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/sap/sap_soap_bapi_user_create1.rb)
- [ ] [auxiliary/scanner/sap/sap_soap_rfc_brute_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/sap/sap_soap_rfc_brute_login.rb)
- [ ] [auxiliary/scanner/sap/sap_web_gui_brute_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/sap/sap_web_gui_brute_login.rb)
- [ ] [auxiliary/scanner/http/sentry_cdu_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/sentry_cdu_enum.rb)
- [ ] [auxiliary/scanner/http/sevone_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/sevone_enum.rb)
- [ ] [auxiliary/scanner/oracle/sid_brute.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/oracle/sid_brute.rb)
- [ ] [auxiliary/admin/oracle/sid_brute.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/admin/oracle/sid_brute.rb)
- [ ] [auxiliary/server/capture/sip.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/server/capture/sip.rb)
- [ ] [post/windows/gather/credentials/smartermail.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/smartermail.rb)
- [ ] [post/windows/gather/credentials/spark_im.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/spark_im.rb)
- [ ] [auxiliary/scanner/http/splunk_web_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/splunk_web_login.rb)
- [ ] [auxiliary/scanner/http/squiz_matrix_user_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/squiz_matrix_user_enum.rb)
- [ ] [auxiliary/scanner/ssh/ssh_identify_pubkeys.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/ssh/ssh_identify_pubkeys.rb)
- [ ] [auxiliary/scanner/telnet/telnet_ruggedcom.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/telnet/telnet_ruggedcom.rb)
- [ ] [auxiliary/scanner/http/titan_ftp_admin_pwd.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/titan_ftp_admin_pwd.rb)
- [ ] [auxiliary/scanner/http/tomcat_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/tomcat_enum.rb)
- [ ] [post/windows/gather/credentials/tortoisesvn.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/tortoisesvn.rb)
- [ ] [post/windows/gather/credentials/total_commander.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/credentials/total_commander.rb)
- [ ] [auxiliary/scanner/http/typo3_bruteforce.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/typo3_bruteforce.rb)
- [ ] [auxiliary/gather/vbulletin_vote_sqli.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/vbulletin_vote_sqli.rb)
- [ ] [exploits/unix/webapp/vbulletin_vote_sqli_exec.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/exploits/unix/webapp/vbulletin_vote_sqli_exec.rb)
- [ ] [auxiliary/scanner/http/vcms_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/vcms_login.rb)
- [ ] [auxiliary/scanner/vmware/vmware_http_login.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/vmware/vmware_http_login.rb)
- [ ] [auxiliary/scanner/dcerpc/windows_deployment_services.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/dcerpc/windows_deployment_services.rb)
- [ ] [auxiliary/scanner/http/wordpress_login_enum.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/scanner/http/wordpress_login_enum.rb)
- [ ] [auxiliary/gather/wp_w3_total_cache_hash_extract.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/auxiliary/gather/wp_w3_total_cache_hash_extract.rb)


### Special attention needed

- [ ]
  [post/windows/gather/enum_domain.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/enum_domain.rb) - Partials, should create realms but not full cores
- [ ]
  [post/windows/gather/enum_domain_group_users.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/enum_domain_group_users.rb) - Should create realms and publics but won't be able to get privates
- [ ]
  [post/windows/gather/enum_domains.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/enum_domains.rb) - Creates realms
- [ ]
  [post/windows/gather/enum_logged_on_users.rb](https://github.com/rapid7/metasploit-framework/tree/master/modules/post/windows/gather/enum_logged_on_users.rb) - Creates publics but not privates