**ALL MAC ADDRESS FIND COMMAND**
- **arp -a**
---
**PARTICULAR PC MAC ADDRESS FIND COMMAND**
- **getmac**
---
**IP ADDRESS FIND COMMAND**
- **ipconfig**
- **ipconfig/all**
---
**SYSTEM INFORMATION FIND COMMAND**
- **systeminfo**
---
**DNS Cache Flush**
- **ipconfig /flushdns**
---
**DNS Cache Check**
- **ipconfig/displaydns**
---
**Domain IP Website IP address and Mac address find**
- **nslookup google.com**
---

**GROUP POLICY UPDATE COMMAND IN WINDOWD SERVER **
- **gpupdate /force**
---
**DNS TYPES Recoreds**
- **nslookup -type=a google.com**
- **nslookup -type=aaaa google.com**
- **nslookup -type=ns google.com**
-  **nslookup -type=mx google.com**
-  **nslookup -type=cname google.com**
- **nslookup -type=soa google.com**
-  **nslookup -type=ptr google.com**
- **nslookup -type=rv google.com**

---
### 1. IPCONFIG
यह कमांड आपके कंप्यूटर के IP कॉन्फ़िगरेशन की जानकारी प्रदर्शित करता है।

**उदाहरण:**
```
ipconfig
```
यह कमांड आपके कंप्यूटर के IP पते, सबनेट मास्क और डिफ़ॉल्ट गेटवे को दिखाएगा।

### 2. NSLOOKUP
यह कमांड DNS सर्वर से डोमेन नाम की जानकारी प्राप्त करने में मदद करता है।

**उदाहरण:**
```
nslookup google.com
```
यह कमांड Google के लिए DNS विवरण प्रदान करेगा।

### 3. PING
यह कमांड किसी अन्य होस्ट के साथ कनेक्टिविटी की जांच करने के लिए उपयोग किया जाता है। यह चार पैकेट भेजता है और उनके उत्तर की प्रतीक्षा करता है।

**उदाहरण:**
```
ping www.example.com
```
यह कमांड यह जांचेगा कि `www.example.com` तक पहुँच संभव है या नहीं।

### 4. TRACERT
यह कमांड डेटा पैकेट के गंतव्य तक पहुँचने के लिए रास्ते को ट्रेस करता है।

**उदाहरण:**
```
tracert www.example.com
```
यह कमांड दिखाएगा कि डेटा पैकेट किस-किस हॉप के माध्यम से गंतव्य तक पहुँचता है।

### 5. NETSTAT
यह कमांड आपके कंप्यूटर पर सभी सक्रिय नेटवर्क कनेक्शनों की जानकारी प्रदान करता है।

**उदाहरण:**
```
netstat
```
यह कमांड सभी TCP/IP कनेक्शनों की सूची दिखाएगा।

### 6. ARP
यह कमांड IP पते को MAC पते में मैप करने की जानकारी दिखाता है।

**उदाहरण:**
```
arp -a
```
यह कमांड आपके नेटवर्क पर सभी IP और उनके संबंधित MAC पते दिखाएगा।

### 7. NBTSTAT
यह कमांड TCP/IP प्रोटोकॉल के लिए NetBIOS नामों की जानकारी दिखाता है।

**उदाहरण:**
```
nbtstat -n
```
यह कमांड आपके कंप्यूटर पर NetBIOS नामों की सूची दिखाएगा।

### 8. SYSTEMINFO
यह कमांड आपके सिस्टम की हार्डवेयर और सॉफ़्टवेयर जानकारी प्रदर्शित करता है।

**उदाहरण:**
```
systeminfo
```
यह कमांड आपके सिस्टम की विस्तृत जानकारी जैसे OS संस्करण, प्रोसेसर विवरण आदि दिखाएगा।

### 9. PATHPING
यह कमांड `PING` और `TRACERT` का संयोजन है, जो नेटवर्क पथ की गुणवत्ता की जांच करता है।

**उदाहरण:**
```
pathping www.example.com
```
यह कमांड बताएगा कि पथ में कौन से हॉप्स में देरी या पैकेट हानि हो रही है।

### 10. GETMAC
यह कमांड आपके नेटवर्क इंटरफेस के MAC पते को दिखाता है।

**उदाहरण:**
```
getmac
```
यह कमांड आपके कंप्यूटर के सभी नेटवर्क इंटरफेस के MAC पते दिखाएगा।

---
