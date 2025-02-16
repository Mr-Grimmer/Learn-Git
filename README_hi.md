# गिट सीखें
यहां आपको मेरे YouTube ट्यूटोरियल सीरीज पर गिट और गिथब सीखने के लिए एक नमूना रिपॉजिटरी मिलेगा।
अगर आपको इस रिपॉजिटरी का उपयोगी मिलता है, तो कृपया इसे एक स्टार ⭐ देने का विचार करें, क्योंकि यह दूसरों के लिए इसे ढूंढ़ने में सहायक होगा।

## यहां एक कदम-से-कदम ट्यूटोरियल है कि गिथब में योगदान कैसे करें
एक GitHub खाता बनाएं: अगर आपके पास पहले से एक GitHub खाता नहीं है, तो आपको एक बनाने की आवश्यकता होगी. github.com पर जाएं और उपरी दाएं कोने में "साइन अप" बटन पर क्लिक करें. अपना खाता बनाने के निर्देशों का पालन करें.

योगदान करने के लिए एक रिपॉजिटरी ढूंढें: एक बार जब आपके पास एक GitHub खाता होता है, तो आप उन रिपॉजिटरियों को खोज सकते हैं जिनमें आप योगदान करने में रुचि रखते हैं. आप रिपॉजिटरियों को नाम या कीवर्ड द्वारा खोजने के लिए GitHub खोज बार का उपयोग कर सकते हैं.

रिपॉजिटरी को फॉर्क करें: जब आपको योगदान करने का इच्छुक रिपॉजिटरी मिल जाता है, तो आपको इसे फॉर्क करने की आवश्यकता होगी.

फॉर्किंग आपके खुद के GitHub खाते में रिपॉजिटरी की एक प्रति बनाता है, जिसे आप मूल रिपॉजिटरी को प्रभावित किए बिना संशोधित कर सकते हैं.

### संदर्भ चित्र
फॉर्क करने के लिए नीचे दिए गए बटन पर क्लिक करें, जो ऊपरी दाएं कोने पर है।

![fork_image](./images/Readme_images/fork.png)

फॉर्क किए गए रिपॉजिटरी को क्लोन करें: रिपॉजिटरी को फॉर्क करने के बाद, आपको इसे अपने स्थानीय मशीन पर क्लोन करने की आवश्यकता होगी. क्लोनिंग आपके कंप्यूटर पर रिपॉजिटरी की एक प्रति बनाता है, जिस पर आप काम कर सकते हैं. रिपॉजिटरी को क्लोन करने के लिए, एक टर्मिनल विंडो खोलें और निम्नलिखित कमांड दर्ज करें:

```
git clone https://github.com/your-username/repository-name.git
```

यह सुनिश्चित करें कि "your-username" और "repository-name" को अपने GitHub उपयोगकर्ता नाम और आपने फॉर्क की गई रिपॉजिटरी के नाम से बदल दें.

### संदर्भ चित्र
![Clone_repo](./images/Readme_images/Clone.png)

यहां दिया गया अनुवाद है:

सुनिश्चित करें कि आप स्रोत कोड में करना चाहते हैं उन परिवर्तनों को प्रकट करने के लिए एक विशेष नामक शाखा बनाते हैं. एक शाखा बनाने के लिए निम्नलिखित सिंटैक्स का उपयोग करें:

```
git branch "शाखा-नाम"
```
### संदर्भ चित्र
![शाखा_बनाना](./images/Readme_images/Branch_making.png)

इस शाखा पर स्विच करने के लिए निम्नलिखित सिंटैक्स का उपयोग करें:
```
git checkout "शाखा-नाम"
```
### संदर्भ चित्र
![शाखा_स्विच](./images/Readme_images/branch_switch.png)

कोड में परिवर्तन करें: एक बार जब आपके पास रिपॉजिटरी क्लोन कर ली होती है, तो आप कोड में परिवर्तन कर सकते हैं. फ़ाइलों को संशोधित करने के लिए अपने पसंदीदा पाठ संपादक या IDE का उपयोग करें.

परिवर्तनों को कमिट करें: कोड में परिवर्तन करने के बाद, आपको उन्हें अपने स्थानीय रिपॉजिटरी में कमिट करने की आवश्यकता होगी. इसके लिए, एक टर्मिनल विंडो खोलें और क्लोन किए गए रिपॉजिटरी की मूल में पहुँचने के लिए निम्नलिखित कमांड का उपयोग करें:

```
git add .
```

### संदर्भ चित्र
![जोड़_दें](./images/Readme_images/add.png)

इससे रिपॉजिटरी में की गई सभी परिवर्तनों को स्टेज कर दिया जाएगा.

अगले, निम्नलिखित कमांड का उपयोग करके परिवर्तनों को कमिट करें:

```
git commit -m "किए गए परिवर्तनों का एक संक्षेप विवरण"
```

### संदर्भ चित्र
![कमिट](./images/Readme_images/commit.png)

सुनिश्चित हो जाएं कि आपने किए गए परिवर्तनों का एक संक्षेप और जानकारीपूर्ण संदेश शामिल किया है, जिसमें आपने परिवर्तन क्यों किए हैं, यह स्पष्ट होना चाहिए.

आपको बदलाव को GitHub पर पुश करने की आवश्यकता होती है: जब आप अपने स्थानीय भंडारण से परिवर्तनों को समर्थन करते हैं, तो आपको उन्हें GitHub पर पुश करनी होती है। इससे आपके GitHub खाते में रेपोजिटरी की प्रतिलिपि में आपने की गई परिवर्तनों को अद्यतित कर दिया जाता है। परिवर्तनों को पुश करने के लिए, निम्नलिखित कमांड का उपयोग करें:

```
git push origin branch-name
```

### संदर्भ छवि
![Push_image](./images/Readme_images/push.png)

पुश करने के बाद, GitHub पर एक पुल अनुरोध बनाने का विकल्प दिखाई देगा: परिवर्तनों को GitHub पर पुश करने के बाद, जब आप फोर्क की गई रेपोजिटरी को पुनर्लोड करें, तो आपको पुल अनुरोध बनाने का विकल्प दिखाई देगा। पुल अनुरोध बनाने के लिए उस बटन पर क्लिक करें।

### संदर्भ छवि
![Pull_Request](./images/Readme_images/pull%20request.png)

यह आपको एक पृष्ठ पर ले जाएगा जहां आप आपके द्वारा किए गए परिवर्तनों की समीक्षा कर सकते हैं और अपने पुल अनुरोध की विवरण प्रदान कर सकते हैं।

सुनिश्चित करें कि आप उन परिवर्तनों की स्पष्ट और संक्षेप विवरण शामिल करते हैं जो आपने किए हैं और आपने उन्हें क्यों किए हैं।

अगर किसी प्रकार की समस्याएँ या चिंताएँ हैं जिनकी जानकारी रेपोजिटरी के मालिक को जाननी चाहिए, तो सुनिश्चित करें कि आप पुल अनुरोध विवरण में उन्हें उल्लिखित करते हैं।

एक बार जब आप विवरण के साथ संतुष्ट हो जाते हैं, तो "पुल अनुरोध बनाएं" बटन पर क्लिक करें।

### संदर्भ छवि
![Create_pull_request](./images/Readme_images/Create_pull_request.png)

प्रतिक्रिया का प्रतीक्षा करें: पुल अनुरोध बनाने के बाद, रेपोजिटरी के मालिक आपके परिवर्तनों की समीक्षा करेंगे और प्रतिक्रिया प्रदान करेंगे।

वे आपसे अतिरिक्त परिवर्तन करने के लिए कह सकते हैं, या वे आपके परिवर्तनों को मूल रेपोजिटरी में मर्ज कर सकते हैं।

इस प्रक्रिया के दौरान धीरज और सजग रहें, और सुनिश्चित करें कि रेपोजिटरी के मालिक द्वारा उठाई गई किसी भी प्रतिक्रिया या चिंता का समाधान करते हैं।

अपनी फोर्क की गई रेपोजिटरी को अद्यतन करें: यदि रेपोजिटरी के मालिक आपके परिवर्तनों को मूल रेपोजिटरी में मर्ज कर देते हैं, तो आपको अपनी फोर्क की गई रेपोजिटरी को उन परिवर्तनों को प्रतिबिम्बित करने के लिए अद्यतन करनी होगी।

इसके लिए, GitHub पर अपनी फोर्क की गई रेपोजिटरी पर जाएं और "फेच अपस्ट्रीम" बटन पर क्लिक करें।

फिर, अपनी स्थानीय रेपोजिटरी में उनको अद्यतन करने के लिए निम्नलिखित कमांड चलाएं:

```
git pull
```

यह आपको Git का उपयोग करने के एक संक्षिप्त विचार देगा, स्वच्छंद है कि आप इस रेपोजिटरी में बनाई गई सबकों का आकार बढ़ा सकते हैं, जिसके लिए मैंने इस रेपोजिटरी में बनाई हैं।

## सुनिश्चित पहली समस्या

आप इस प्रोजेक्ट का उपयोग ओपन सोर्स प्रोजेक्ट्स में योगदान करने का एक तरीका के रूप में कर सकते हैं। यह एक **अच्छी पहली समस्या** हो सकती है, आपके अपने GitHub रेपोजिटरी से जुड़ने के लिए [CONTRIBUTORS.md](https://github.com/rcallaby/Learn-Git/blob/main/CONTRIBUTORS.md) फ़ाइल को संशोधित करें, जैसा कि फ़ाइल में दिखाए गए मार्कडाउन का उपयोग करें।

कृपया [First-Contributions](https://github.com/rcallaby/Learn-Git/tree/main/First-Contributions) डायरेक्टरी पर एक कदम-से-कदम निर्देशों के लिए देखें कि इस रेपोजिटरी में योगदान कैसे करें।

### सूची

- [भाग 00 - इतिहास और नींव](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-00-History-and-Foundations/history-of-git.md)
- [भाग 01 - मूल नेविगेशन](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-01-Basic-Navigation/basic-navigation.md)
- [भाग 02 - Git की आरंभिकीकरण](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-02-Initializing-Git/getting-started.md)
- [भाग 03 - शाखा बनाने और मर्ज करने](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-03-Branching-and-Merging/branching-and-merging.md)
- [भाग 04 - दूरस्थ रेपोजिटरी के साथ सहयोग](https://github.com/rcallaby/Learn-Git/tree/main/Lessons/en/Part-04-Collaborating-with-Remote-Repositories/collaborating-with-remote-repos.md)
- [भाग 05 - उन्नत Git अवयव](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-05-Advanced-Git-Concepts/advanced-git.md)
- [भाग 06 - सीआई-सीडी और Git और Github](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-06-CI-CD-with-Git-and-Github/ci-cd-git-github.md)
- [भाग 07 - Git के श्रेष्ठ अभ्यास और सुझाव](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-07-Git-Best-Practices-and-Tips/best-practices-tips.md)
- [भाग 08 - Git और Github में एगाइल विकास](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-08-Git-and-Github-in-Agile-Development/git-github-agile-dev.md)
- [भाग 09 - Github और कोडस्पेस](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-09-Github-and-Codespaces/github-codespaces.md)
- [भाग 10 - Github क्रियाएँ](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-10-Github-Actions/github-actions.md)
- [भाग 11 - उन्नत Github क्रियाएँ](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-11-Advanced-Github-Actions/advanced-github-actions.md)
- [भाग 12 - Github में ज्यूपिटर कोडस्पेस का उपयोग](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-12-Using-Jupyter-Codespaces-in-Github/github-jupyter-codespace.md)
- [भाग 13 - Github में C# कोडस्पेस का उपयोग](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-13-Using%20Csharp-Codespaces-in-Github/github-Csharp-codespace.md)
- [भाग 14 - Github में React कोडस्पेस का उपयोग](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-14-Using-React-Codespaces-in-Github/github-react-codespace.md)
- [भाग 15 - Github में Express कोडस्पेस का उपयोग](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-15-Using-Express-Codespaces-in-Github/github-express-codespace.md)
- [भाग 16 - Github में Ruby on Rails कोडस्पेस का उपयोग](https://github.com/rcallaby/Learn-Git/blob/main/Lessons

/en/Part-16-Using-Ruby-on-Rails-Codespaces/github-rubyrails-codespace.md)
- [भाग 17 - Github में Django कोडस्पेस का उपयोग](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-17-Using%20Django%20Codespaces-in-Github/github-django-codespace.md)
- [भाग 18 - Github प्रोजेक्ट प्रबंधन उपकरण](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-18-Github-Project-Management-Tools/github-project-management-tools.md)
- [भाग 19 - Github प्रोजेक्ट बोर्ड और नोट्स](https://github.com/rcallaby/Learn-Git/blob/main/Lessons/en/Part-19-Github-Project-Boards-and-Notes/github-project-boards-and-notes.md)
