# openvpn_client
`Ansible` role for deploying `openvpn-client` on `Ubuntu Xenial`.

Written using Ansible ver. *2.7*


#### Variables
- `openvpn_client_ca`

   Certificate  authority  (CA) in .pem format.

- `openvpn_client_cert`

   Local peer's signed certificate in .pem format.

- `openvpn_client_conf_name`

   Name of the openvpn config file with extension.  
   Name is inherits `openvpn_client_service_name` value.

- `openvpn_client_conf_path`

   Location of openvpn client config file.

- `openvpn_client_pkg_ver`

   Openvpn package version to install.

- `openvpn_client_remote.host`

   Remote host name or IP address.

- `openvpn_client_remote.port`

   TCP/UDP port number or port name for remote.

- `openvpn_client_remote.proto`

   Indicates  the protocol to use when connecting with the remote, and may  
   be "tcp" or "udp".

- `openvpn_client_service_name`

   Name of systemd service to create.

- `openvpn_client_tls_auth_key`

   `tls-auth` key in in OpenVPN static key format.
