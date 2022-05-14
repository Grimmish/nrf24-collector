# nrf24-collector
A toolkit for collecting measurements from remote sensors via low-cost 2.4 GHz nRF24L01 radios. Kit consists of two roles:
- Sender: A MicroPython-based client running on a microcontroller that collects and transmits samples
- Collector: A Python-based daemon that receives the samples and shovels them into a local Prometheus instance
