[![हिन्दी](https://img.shields.io/badge/भाषा-हिन्दी-red)](README_HI.md)
[![English](https://img.shields.io/badge/Language-English-red)](README.md)

## 🚀 त्वरित शुरुआत

1. गिटहब पर [ओपन सोर्स क्लाइंट्स](https://github.com/awesome-vpn/awesome-vpn/wiki/Clients) खोजें और इंस्टॉल करें
2. नीचे दिए गए सब्सक्रिप्शन लिंक को क्लाइंट में कॉपी करें
3. उपयुक्त नोड का चयन करें और उपयोग करना शुरू करें

प्रोजेक्ट लिंक:
- [https://github.com/awesome-vpn/awesome-vpn](https://github.com/awesome-vpn/awesome-vpn)

## 📥 सब्सक्रिप्शन लिंक

मुख्य सब्सक्रिप्शन लिंक:
- https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all

मिरर लिंक (यदि गिटहब अस्थिर है तो उपयोग करें):
- https://raw.kkgithub.com/awesome-vpn/awesome-vpn/master/all [अनुकूलित: हांगकांग/जापान/सिंगापुर]
- https://ghp.ci/https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all [अनुकूलित: जापान/कोरिया/यूएसए/यूरोप]
- https://ghproxy.net/https://raw.githubusercontent.com/awesome-vpn/awesome-vpn/master/all [अनुकूलित: जापान]

## 📊 वीपीएन और प्रॉक्सी प्रोटोकॉल विश्लेषण

| ओएसआई लेयर | प्रोटोकॉल | विवरण |
|------------|-----------|--------|
| लेयर 2 - डेटा लिंक | PPTP | प्वाइंट-टू-प्वाइंट टनलिंग प्रोटोकॉल, पुराना, कम सुरक्षा |
| लेयर 2 - डेटा लिंक | L2TP | लेयर 2 टनलिंग प्रोटोकॉल, अक्सर IPsec के साथ उपयोग किया जाता है |
| लेयर 3 - नेटवर्क | IPsec | इंटरनेट प्रोटोकॉल सुरक्षा, L2TP के साथ या अकेले उपयोग किया जा सकता है |
| लेयर 3 - नेटवर्क | WireGuard | नया कुशल वीपीएन प्रोटोकॉल, उच्च प्रदर्शन |
| लेयर 3 - नेटवर्क | GRE | सामान्य रूटिंग एनकैप्सुलेशन, विभिन्न नेटवर्क प्रोटोकॉल को एनकैप्सुलेट कर सकता है |
| लेयर 4 - ट्रांसपोर्ट | TUIC | UDP पर TCP, QUIC आधारित ट्रांसपोर्ट प्रोटोकॉल |
| लेयर 4 - ट्रांसपोर्ट | Hysteria | QUIC आधारित उच्च गति नेटवर्क ट्रांसपोर्ट प्रोटोकॉल |
| लेयर 4 - ट्रांसपोर्ट | Hysteria2 | Hysteria का उन्नत संस्करण, अधिक कुशल और सुरक्षित |
| लेयर 4 - ट्रांसपोर्ट | QUIC | तेज UDP इंटरनेट कनेक्शन, गूगल द्वारा विकसित |
| लेयर 5 - सत्र | SOCKS4 | सरल फायरवॉल ट्रैवर्सल प्रोटोकॉल, प्रमाणीकरण समर्थन नहीं |
| लेयर 5 - सत्र | SOCKS5 | प्रमाणीकरण और UDP समर्थन करने वाला सार्वभौमिक प्रॉक्सी प्रोटोकॉल |
| लेयर 5 - सत्र | SSL/TLS | सुरक्षित सॉकेट्स/ट्रांसपोर्ट लेयर सुरक्षा, एप्लिकेशन लेयर के लिए एन्क्रिप्शन प्रदान करता है |
| लेयर 7 - एप्लिकेशन | OpenVPN | एन्क्रिप्शन के लिए OpenSSL लाइब्रेरी का उपयोग करने वाला वीपीएन सिस्टम |
| लेयर 7 - एप्लिकेशन | Shadowsocks | हल्का एन्क्रिप्टेड प्रॉक्सी प्रोटोकॉल |
| लेयर 7 - एप्लिकेशन | ShadowsocksR | Shadowsocks का विस्तारित संस्करण, अस्पष्टता जैसी विशेषताएं जोड़ता है |
| लेयर 7 - एप्लिकेशन | VMess | TLS आधारित एन्क्रिप्टेड ट्रांसमिशन प्रोटोकॉल, V2Ray प्रोजेक्ट द्वारा प्रस्तावित |
| लेयर 7 - एप्लिकेशन | VLESS | VMess का सरल संस्करण, एन्क्रिप्शन ओवरहेड को कम करता है |
| लेयर 7 - एप्लिकेशन | Trojan | HTTPS ट्रैफिक के रूप में प्रच्छन्न प्रॉक्सी प्रोटोकॉल |
| लेयर 7 - एप्लिकेशन | Trojan-Go | Trojan प्रोटोकॉल का Go कार्यान्वयन, WebSocket जैसी विशेषताएं जोड़ता है |
| लेयर 7 - एप्लिकेशन | HTTP प्रॉक्सी | सबसे बुनियादी प्रॉक्सी प्रकार, आमतौर पर एन्क्रिप्टेड नहीं |
| लेयर 7 - एप्लिकेशन | HTTPS प्रॉक्सी | एन्क्रिप्टेड HTTP प्रॉक्सी, बेहतर सुरक्षा प्रदान करता है |
| लेयर 7 - एप्लिकेशन | SSH टनल | SSH प्रोटोकॉल का उपयोग करके एन्क्रिप्टेड टनल बनाता है |
| लेयर 7 - एप्लिकेशन | Tor | गुमनाम संचार नेटवर्क, बहु-स्तरीय एन्क्रिप्शन और रिले के माध्यम से उच्च गोपनीयता प्रदान करता है |
| लेयर 7 - एप्लिकेशन | Naive | Chromium नेटवर्क स्टैक आधारित HTTPS प्रॉक्सी प्रोटोकॉल |
| लेयर 7 - एप्लिकेशन | Brook | सरल क्रॉस-प्लेटफॉर्म प्रॉक्सी प्रोटोकॉल |
| लेयर 7 - एप्लिकेशन | Shadowtls | Shadowsocks ट्रैफिक को TLS ट्रैफिक के रूप में प्रच्छन्न करने वाला प्रोटोकॉल |
| लेयर 7 - एप्लिकेशन | Reality | TLS 1.3 आधारित नया प्रॉक्सी प्रोटोकॉल, बेहतर पहचान विरोधी क्षमता प्रदान करता है |
| लेयर 7 - एप्लिकेशन | WebSocket | एकल TCP कनेक्शन पर पूर्ण-डुप्लेक्स संचार प्रदान करने वाला प्रोटोकॉल |

## ⚠️ वर्तमान चुनौतियाँ

कई एक-क्लिक वीपीएन क्लाइंट निम्नलिखित समस्याओं का सामना करते हैं:
- अवरुद्ध डोमेन/IP के कारण कनेक्शन समस्याएं
- ऐप स्टोर में अनुपलब्धता
- जबरन भुगतान या समय-सीमित परीक्षण

## 🔬 हमारा मिशन

हम लंबे समय से चल रहे वीपीएन क्लाइंट्स का शोध कर रहे हैं ताकि एक मुफ्त, विश्वसनीय क्रॉस-प्लेटफॉर्म समाधान विकसित किया जा सके। हमारा लक्ष्य एक ऐसा एप्लिकेशन बनाना है जो प्रदान करता है:

- स्थायी रूप से मुफ्त और असीमित उपयोग
- स्थिर कनेक्शन
- सभी प्लेटफार्मों के लिए समर्थन
- कई प्रॉक्सी प्रोटोकॉल के लिए समर्थन
- कई एन्क्रिप्शन विधियों के लिए समर्थन
- मोबाइल संस्करण आधिकारिक ऐप स्टोर के बाहर इंस्टॉलेशन और अपडेट विधियाँ प्रदान करता है

## ⚖️ अस्वीकरण

यह परियोजना केवल शैक्षिक और अनुसंधान उद्देश्यों के लिए है। उपयोगकर्ता इन संसाधनों का उपयोग करते समय स्थानीय कानूनों और विनियमों का पालन करने के लिए जिम्मेदार हैं।
