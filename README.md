# time-formula

Salt Stack Formula to set up and configure time relatated software and system settings

## NOTICE BEFORE YOU USE

* This formula aims to follow the conventions and recommendations described at [http://docs.saltstack.com/topics/conventions/formulas.html](http://docs.saltstack.com/topics/conventions/formulas.html)

## TODO

None

## Instructions

1. Add this repository as a [GitFS](http://docs.saltstack.com/topics/tutorials/gitfs.html) backend in your Salt master config.

2. Configure your Pillar top file (`/srv/pillar/top.sls`), see pillar.example

3. Include this Formula within another Formula or simply define your needed states within the Salt top file (`/srv/salt/top.sls`).

## Available states

### time.ntpd

Install and configure ntpd

## Additional resources

None

## Formula Dependencies

None

## Contributions

Contributions are always welcome. All development guidelines you have to know are

* write clean code (proper YAML+Jinja syntax, no trailing whitespaces, no empty lines with whitespaces, LF only)
* set sane default settings
* test your code
* update README.md doc

## Salt Compatibility

* >= 2014.1.0

## OS Compatibility

*DOES* work on:

* GNU/ Linux Debian Wheezy
