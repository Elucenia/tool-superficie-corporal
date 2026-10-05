<!-- ELUCENIA technical documentation · superficie-corporal · hi · no clinical/professional/rights approval -->

# शरीर का सतह क्षेत्रफल और BMI

[शर्तें, स्रोत और अनुमतियाँ](https://elucenia.org/hi/tools/superficie-corporal)

## उपयोग कैसे करें

पोर्टल पर उपकरण का उपयोग करें या स्थानीय HTTP सर्वर के माध्यम से index.html खोलें। भाषा चुनें, फ़ील्ड भरें और गणना करें।

## इनपुट और इकाइयाँ

### वज़न

`peso`

kg · सीमा: 2–350

### लंबाई

`altura`

cm · सीमा: 40–240

## विधि का संस्करण

Mosteller 1987 √(cm×kg/3600); DuBois 1916 गुणांक 0.007184, घात 0.425/0.725; अलग BMI

## दस्तावेज़ित सूत्र

Mosteller: शरीर सतह क्षेत्र (m²) = √(लंबाई \[cm\] × वज़न \[kg\] ÷ 3600)

DuBois: शरीर सतह क्षेत्र (m²) = 0.007184 × वज़न0.425 × लंबाई0.725

BMI = वज़न ÷ लंबाई² (m)

## सीमाएँ और जनसमूह

ऊँचाई cm और वजन kg में दें; परिणाम m² में अनुमानित शरीर सतह क्षेत्रफल है, BMI से अलग। Mosteller और Du Bois अलग समीकरण हैं, सतह की प्रत्यक्ष माप नहीं। उद्धृत ASCO 2012 दिशानिर्देश मोटापे वाले वयस्क कैंसर रोगियों में साइटोटॉक्सिक कीमोथेरेपी की खुराक पर है और उस संस्करण के नए लक्षित एजेंटों को शामिल नहीं करता। सतह गणना से खुराक, क्षेत्रफल की अधिकतम सीमा या संकेत तय नहीं होते: निर्णय विशिष्ट प्रोटोकॉल और दवा के अनुसार हो, इस संदर्भ से सार्वभौमिक सीमाएँ न निकालें।

## संदर्भ

- [Mosteller RD. Simplified calculation of body-surface area. N Engl J Med, 1987.](https://doi.org/10.1056/NEJM198710223171717)

- [Griggs JJ et al. Appropriate chemotherapy dosing for obese adult patients with cancer: American Society of Clinical Oncology clinical practice guideline. J Clin Oncol, 2012.](https://doi.org/10.1200/JCO.2011.39.9436)

- [Lang RM et al. Recommendations for cardiac chamber quantification by echocardiography in adults (ASE/EACVI). J Am Soc Echocardiogr, 2015.](https://doi.org/10.1016/j.echo.2014.10.003)

## तकनीकी परीक्षण दोहराएँ

दर्ज कृत्रिम मामलों को दोहराने के लिए इस रिपॉज़िटरी की मूल निर्देशिका में node test.cjs चलाएँ। मूल इनपुट, अपेक्षित परिणाम और सहनशीलता सीमाएँ सुरक्षित रखी गई हैं। तकनीकी परीक्षण नैदानिक सत्यापन नहीं हैं।

```sh
node test.cjs
```

tool.json में स्रोत, संस्करण और समीक्षा का दायरा दिया गया है। examples.json में कृत्रिम इनपुट और अपेक्षित परिणाम सुरक्षित हैं; results.json में प्राप्त परिणाम दर्ज हैं।

[रिकॉर्ड और संदर्भ](../tool.json) · [JavaScript कोड](../calculator.js) · [संदर्भ मामले](../examples.json) · [results.json](../results.json)

## समीक्षा और उपयोग की शर्तें

स्वतंत्र नैदानिक समीक्षा नहीं की गई है।

यह इंटरफ़ेस लेखकों द्वारा किया गया अनुवाद है, कोई आधिकारिक या प्रमाणित संस्करण नहीं। स्वतंत्र नैदानिक समीक्षा, पेशेवर भाषाई समीक्षा और उपकरणों के अधिकारों की अनुमति की प्रक्रिया पूरी नहीं हुई है।

सूत्र या वर्गीकरण का परिणाम। व्याख्या, कार्यवाही और उपयुक्तता पेशेवर मूल्यांकन और चुने गए स्रोत पर निर्भर है।

## लाइसेंस और श्रेय

Apache-2.0 केवल ELUCENIA के कोड पर लागू होता है। उपकरणों, प्रकाशनों, अनुवादों और डेटा के अधिकार उनके संबंधित अधिकारधारकों के पास रहते हैं। LICENSE और NOTICE सुरक्षित रखें।

ELUCENIA · Felipe Guedes · Copyright © 2026
