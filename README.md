# rspamd-invaluement-spbl-rules
Rspamd rules that catch Sendgrid senders that are listed on Invaluement.com's Service Provider DNSBLs. For more information about Invaluement.com's SPBL lists see <https://www.invaluement.com/serviceproviderdnsbl/>.

## How to use

Place both regexp.conf and multimap.conf in your /etc/rspamd/local.d directory, or if either file already exists in your setup append the content to the existing file.

## Authors

* **Jeffry Sleddens** - [jeffrysleddens](https://github.com/jeffrysleddens)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details

## References

* Rspamd: <https://rspamd.com>
* Invaluement.com Service Provier DNSBL: <https://www.invaluement.com/serviceproviderdnsbl/>
