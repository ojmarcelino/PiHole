# PiHole DNS Blocklists and RegEx entries
All collected entries with the help of the community for multiple purposes and tests.

## Getting Started
Just add the raw list(s) or regex entries in PiHole Settings, update gravity [pihole -g](https://docs.pi-hole.net/core/pihole-command/#gravity) and voilà!
Piece of advice, use any file at your own discretion #DropsMic.

### Prerequisites
[PiHole Installation](https://docs.pi-hole.net/main/basic-install/)

## sublert lists
Automatically generated list using [Sublert](https://github.com/yassineaboukir/sublert). This list contains all subdomains with TLS certificates and **cannot be used directly in pihole.** Sublert is a security and reconnaissance tool that was written in Python to leverage certificate transparency for the sole purpose of monitoring new subdomains deployed by specific organizations and issued TLS/SSL certificate.

## License
This project is licensed under the GNU Lesser General Public License v3.0 - see the [LICENSE](https://github.com/jdmarcelino/PiHole/blob/master/LICENSE) file for details.

And may the Force be with you.
