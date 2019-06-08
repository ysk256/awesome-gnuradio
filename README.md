# awesome-gnuradio

## Overview

Software / Hardware for GNU Radio.

## Hardware

- RTL2832U Tuner (e.g. [RTL-SDR.COM](https://www.rtl-sdr.com/buy-rtl-sdr-dvb-t-dongles/),  [DVB-T](https://www.dx.com/p/rtl2832u-r820t-mini-dvb-t-dab-fm-usb-digital-tv-dongle-black-2021120#.XPtidDNUtHY)) (64-1700MHz, 2MSPS, 1ch Rx, $10~30)
- [HackRF One - Great Scott Gadgets](https://greatscottgadgets.com/hackrf/one/) (1-6000MHz, 20MSPS, 8bit-I/Q, 1ch Rx/Tx, $300~400)


- [blade RF - nuand](https://www.nuand.com/product/bladerf-x115/) (300-3800MHz, 40MSPS, 12bit-I/Q, 1ch  Rx 1ch Tx, $420-650)
- [bladeRF 2.0 micro - nuand](https://www.nuand.com/bladerf-2-0-micro/) (47-6000MHz, BW 56MHz, 61.44MSPS, 2ch Rx 2ch Tx, $480-720)
- [USRP B200 - Ettus](https://www.ettus.com/all-products/ub200-kit/) (70-6000MHz, BW 56MHz, 61.44MSPS, $900-1100)
- other Comparison Table https://www.crowdsupply.com/lime-micro/limesdr-mini/
- [Lime SDR mini](https://limemicro.com/products/boards/limesdr-mini/) (10-3500MHz, BW 30.72MHz, 30.72MSPS, 12bit-I/Q, 1ch Rx 1ch Tx, )

## GnuRadio Software

- Framework
  - [Gnu Radio](https://wiki.gnuradio.org/index.php/WindowsInstall)

- SDR / Library OOT
  - [gr-dvbt](https://github.com/BogdanDIA/gr-dvbt) - DVB-T implementation using gnuradio
  - [gr-osmosdr](https://osmocom.org/projects/gr-osmosdr/wiki) - By using the OsmoSDR block you can take advantage of a common software api in your application(s) independent of the underlying radio hardware.
  - [gr-foo](https://github.com/bastibl/gr-foo) - Some GNU Radio blocks that I use.
  - [gr-fosphor](https://github.com/osmocom/gr-fosphor) - GNURadio block for spectrum visualization using GPU 
  - [gr-paint](https://github.com/drmpeg/gr-paint) - An OFDM Spectrum Painter for GNU Radio
  - [gr-cc11xx](https://github.com/andrepuschmann/gr-cc11xx) - GNU Radio OOT module for communicating with TI CC11xx based devices
  - [gr-recipes](https://github.com/gnuradio/gr-recipes) - Main GNU Radio recipe repository for use with PyBOMBS 
  - [gr-etcetera](https://github.com/gnuradio/gr-etcetera) - Additional PyBOMBS recipes that aren't in gr-recipes 

- Wi-Fi
  - [gr-ieee802-11](https://github.com/bastibl/gr-ieee802-11) - IEEE 802.11 a/g/p Transceiver

- Bluetooth / BLE
  - [gr-nordic](https://github.com/BastilleResearch/gr-nordic) - GNU Radio module and Wireshark dissector for the Nordic Semiconductor nRF24L Enhanced Shockburst protocol. 

- LPWA
  - [gr-ieee802-15-4](https://github.com/bastibl/gr-ieee802-15-4) - zigbee
  - [gr-lora](https://github.com/BastilleResearch/gr-lora) - This is an open-source implementation of the LoRa CSS PHY, based on the blind signal analysis conducted by @matt-knight.

- drone
  - [gr-uaslink](https://github.com/deptofdefense/gr-uaslink) - This is a GNU Radio OOT module designed to provide a basic link between MAVLink control of UAS systems and GNU Radio.

- Cell
  - [gr-gsm](https://github.com/ptrkrysik/gr-gsm) - Gnuradio blocks and tools for receiving GSM transmissions
  - [gr-lte](https://github.com/kit-cel/gr-lte) - GNU Radio LTE receiver

- Car
  - [gr-keyfob](https://github.com/bastibl/gr-keyfob) - Transceiver for Hella wireless car key fobs. 
  - [gr-tpms](https://github.com/jboone/gr-tpms) - Tire Pressure Monitor tools for GNU Radio

- aircraft / Marine
  - [gr-adsb](https://github.com/mhostetter/gr-adsb) - GNU Radio OOT Module for demodulating and decoding ADS-B packets
  - [gr-air-modes](https://github.com/bistromath/gr-air-modes) - Gnuradio Mode-S/ADS-B radio
  - [gr-ais](https://github.com/bistromath/gr-ais) - Automatic Information System decoder for shipborne position reporting for the Gnuradio project

- Satellite
  - [gr-satellites](https://github.com/daniestevez/gr-satellites) - GNU Radio decoders for several Amateur satellites 
  - [gr-iridium](https://github.com/muccc/gr-iridium) - Iridium burst detector and demodulator.

- Radar
  - [gr-radar](https://github.com/kit-cel/gr-radar) - GNU Radio Radar Toolbox

- all in one
  - [gr-inspector](https://github.com/gnuradio/gr-inspector) - Signal Analysis Toolbox for GNU Radio
  - [gr-iqbal](https://github.com/osmocom/gr-iqbal) - GNU Radio Blind IQ imbalance estimator and correction
  - [gr-baz](https://github.com/balint256/gr-baz) - Collection of new blocks for GNU Radio)
  - [gr-rds](https://github.com/balint256/gr-rds) - This directory (and the resulting tarball) contains a build tree of the RDS (Radio Data System) block for GNU Radio.
  
- References
  - [Hardware](https://wiki.gnuradio.org/index.php/Hardware)

## Other SDR Software

- Framework
  - [SoapySDR](https://github.com/pothosware/SoapySDR)

- Monitoring / RF Analysis
  - [GQRX](https://github.com/csete/gqrx) - Software defined radio receiver powered by GNU Radio and Qt
  - [SDR#](https://airspy.com/download/)
  - [HDSDR](http://www.hdsdr.de/)
  - [urh](https://github.com/jopohl/urh) - Analysis PHY layer
  - [Baudline](http://www.baudline.com/download.html) - Baudline is a time-frequency browser designed for scientific visualization of the spectral domain
  - [inspectrum](https://github.com/miek/inspectrum) - Offline radio signal analyser
  - [dspectrum](https://github.com/tresacton/dspectrumgui) - The goal of this app is to make it trivial to demodulate most basic RF transmission, and provide a digital worksheet for your reverse engineering efforts. 
  - [quisk](http://james.ahlstrom.name/quisk/) - QUISK is a Software Defined Radio (SDR) transceiver that can control various radio hardware.
  - [Linrad](http://www.sm5bsz.com/linuxdsp/linrad.htm) - Linrad is an exciting SDR program by Leif Asbrink, SM5BSZ
  - [RTLSDR-Scanner](https://github.com/EarToEarOak/RTLSDR-Scanner)
  - [RF Monitor](https://github.com/EarToEarOak/RF-Monitor) - RF signal monitor
  - [afsk](https://github.com/casebeer/afsk) - Bell 202 Audio Frequency Shift Keying encoder and APRS packet audio tools
  - [multimon-ng](https://github.com/EliasOenal/multimon-ng) - multimon-ng is the successor of multimon. It decodes the following digital transmission modes
  - [rtl_433](https://github.com/merbanan/rtl_433) - Program to decode traffic from Devices that are broadcasting on 433.9 MHz like temperature sensors

- Library
  - [pyrtlsdr](https://github.com/roger-/pyrtlsdr) - A Python wrapper for librtlsdr (a driver for Realtek RTL2832U based SDR's)
  - [SimpleSoapy](https://github.com/xmikos/simplesoapy) - Simple pythonic wrapper for SoapySDR library
  - [PySSTV](https://github.com/dnet/pySSTV) - Python classes for generating Slow-scan Television transmissions
  - [redsea](https://github.com/windytan/redsea) - redsea is a lightweight command-line FM-RDS decoder for Linux/macOS. It supports a large subset of RDS features.

- LPWA
  - [python-xbee](https://github.com/niolabs/python-xbee) - Python tools for working with XBee radios

- GNSS
  - [gps-sdr-sim](https://github.com/osqzss/gps-sdr-sim) - Software-Defined GPS Signal Simulator
  - [GNSS-SDRLIB](https://github.com/taroz/GNSS-SDRLIB) - An Open Source GNSS Software Defined Radio Library

- Cell
  - [Kalibrate-RTL](https://github.com/steve-m/kalibrate-rtl) - Kalibrate, or kal, can scan for GSM base stations in a given frequency band and can use those GSM base stations to calculate the local oscillator frequenc offset.
  - [LTE-Cell-Scanner](https://github.com/JiaoXianjun/LTE-Cell-Scanner) - OpenCL, SDR, TDD/FDD LTE cell scanner, full stack from A/D samples to SIB ASN1 messages decoded in PDSCH, (optimized for RTL-SDR HACKRF and BladeRF board) 
  - [openLTE](http://openlte.sourceforge.net/) - OpenLTE is an open source implementation of the 3GPP LTE specifications.
  - [srsLTE](https://github.com/srsLTE/srsLTE) - Open source SDR LTE software suite from Software Radio Systems (SRS) 
  - [srsGUI](https://github.com/srsLTE/srsGUI) - A graphics library for software radio. 

- aircraft / Marine
  - [acarsdec](https://github.com/TLeconte/acarsdec) - ACARS SDR decoder
  - [ADS-B dump1090](https://www.satsignal.eu/raspberry-pi/dump1090.html) - ADS-B

- SDR w/ Machine Learning
  - [deep-sdr](https://github.com/cjam/deep-sdr) - Use of Deep Learning for classification of Software Defined Radio spectrum.
  - [cnn-rtlsdr](https://github.com/randaller/cnn-rtlsdr) - Deep learning signal classification using rtl-sdr dongle 

- References
  - [RFSec-ToolKit](https://github.com/cn0xroot/RFSec-ToolKit) - RFSec-ToolKit is a collection of Radio Frequency Communication Protocol Hacktools.
  - [awesome-rtl-sdr](https://github.com/Schm1tz1/awesome-rtl-sdr) - Software (meta-)package for RTL-SDR with some additional scripts and installers
  - [awesome-vehicle-security](https://github.com/jaredthecoder/awesome-vehicle-security) - A curated list of resources for learning about vehicle security and car hacking. 
  - [Vehicle-Security](https://github.com/wtsxDev/Vehicle-Security) - List of resources for learning about vehicle security and car hacking 
