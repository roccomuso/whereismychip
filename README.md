# WhereIsMyChip

Node.js module to find IP Addresses of all the CHIP (getchip.com) on the LAN.

## Install

    npm install whereismychip -g

## Usage

    > whereismychip
    IP: 192.168.88.111 - MAC Address: cc:79:cf:24:d4:f5

## How it works

It scans the current subnet looking for hosts with a MAC Address starting with <code>cc:79:cf</code> (SHENZHEN RF-LINK TECHNOLOGY CO.,LTD.), the Chip Wi-Fi module vendor.

## Author

- Rocco Musolino
- [hackerstribe.com](http://www.hackerstribe.com)

## Inspired by

This project is inspired by the implementation for Raspberry Pi: [roccomuso/WhereIsMyPi](https://github.com/roccomuso/WhereIsMyPi)

## License

MIT © Rocco Musolino
