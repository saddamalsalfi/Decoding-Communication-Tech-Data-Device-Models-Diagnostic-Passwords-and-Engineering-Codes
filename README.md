
# 📡 Decoding Communication Tech Data: Device Models, Diagnostic Passwords & Engineering Codes

This repository is a comprehensive reference for mobile communication diagnostics. It includes:

- 📱 Device model codes with production/support timeframes  
- 🔐 Diagnostic passwords (Diag PWDs) by network operator  
- 🧪 Android engineering codes (USSD/MMI codes)  
- 🏭 Brand-specific service codes (Samsung, Huawei, Xiaomi, etc.)

---

## 1. 📱 Device Model Codes & Timeframes

| Model        | Start Date | End Date   |
|--------------|------------|------------|
| SM-S978L     | 20150508   | 20150711   |
| SM-S920L     | 20150315   | 20150615   |
| SCH-R970X    | 20121126   | 20131202   |
| SM-G900R4    | 20130513   | 20130909   |
| SM-G900R     | 20130328   | 20130817   |
| SM-N910R4    | 20140516   | 20140901   |
| S120VL       | 20130327   | 20130823   |
| SCH-I535     | 20120601   | 20130815   |
| SPH-L720     | 20130501   | 20140801   |
| SM-G930P     | 20160301   | 20170801   |

---

## 2. 🔐 Diagnostic Passwords by Network Operator

| Operator      | Diag PWDs (Raw)                                      | Full PWD (Concatenated)                  |
|---------------|------------------------------------------------------|------------------------------------------|
| China Telecom | 5903365113726913                                     | 5903365113726913                         |
| TRACEFON      | 20090319,20090615                                     | 2009031920090615                         |
| TRACEFON      | 20141124,20150202                                     | 2014112420150202                         |
| TRACEFON      | 20150315,20150615                                     | 2015031520150615                         |
| US Cellular   | 20100316,19780721                                     | 2010031619780721                         |
| Verizon       | 20090319,20090615                                     | 2009031920090615                         |
| Sprint        | 01F2030F5F678FF9                                      | 01F2030F5F678FF9                         |
| Sprint        | 20121121,20131219                                     | 2012112120131219                         |
| Metro PCS     | 2FF811282FF9F323                                      | 2FF811282FF9F323                         |
| Cricket S3    | 20100316,19780721                                     | 2010031619780721                         |
| Gusto         | 20111011,16083112                                     | 2011101116083112                         |
| Boost Mobile  | 20111201,20130101                                     | 2011120120130101                         |
| TracFone      | 20130501,20140801                                     | 2013050120140801                         |

---

## 3. 🧪 Universal Android Engineering Codes (USSD/MMI)

These codes are entered in the dialer and work across many Android devices:

| Code               | Function                                 |
|--------------------|------------------------------------------|
| *#06#              | Show IMEI number                         |
| *#*#4636#*#*       | Phone info, battery, usage stats         |
| *#*#232338#*#*     | Wi-Fi MAC address                        |
| *#*#1472365#*#*    | GPS test                                 |
| *#*#2664#*#*       | Touchscreen test                         |
| *#*#0842#*#*       | Vibration and backlight test             |
| *#*#0289#*#*       | Audio test                               |
| *#*#197328640#*#*  | Service mode (Samsung)                   |
| *#*#7780#*#*       | Factory reset                            |
| *#*#1111#*#*       | Software version (FTA)                   |
| *#*#2222#*#*       | Hardware version (FTA)                   |
| *#*#1234#*#*       | PDA software version                     |
| *#*#526#*#*        | WLAN test                                |
| *#*#0283#*#*       | Loopback packet test                     |
| *#*#7353#*#*       | Quick diagnostics menu                   |

---

## 4. 🏭 Brand-Specific Codes (2025)

### Samsung
- *#0*# – General hardware test menu  
- *#0011# – Service mode (network info)  
- *#9090# – Diagnostic config  
- *#0808# – USB settings  
- *#7284# – UART/USB config  

### Huawei
- *#*#2846579#*#* – Project menu  
- *#*#2846#*#* – Hardware test  
- *#*#14789632#*#* – Battery and temperature  

### Xiaomi
- *#*#6484#*#* – Hardware test menu  
- *#*#4636#*#* – Device info  
- *#*#86583#*#* – Disable VoLTE carrier check  

### OnePlus
- *#808# – Engineering test mode  
- *#801# – Engineering switch  
- *#1234# – Software version  

---

## 🧠 Why This Data Matters

This repository is useful for:

- 🔧 **Technicians**: Diagnosing and repairing devices using engineering tools  
- 🌐 **Service Providers**: Managing device configurations across networks  
- 👨‍💻 **Developers**: Understanding device internals and firmware behavior  

Every sequence of numbers and characters in this dataset has a specific technical meaning, contributing to the smooth operation and maintenance of mobile communication systems.

---
