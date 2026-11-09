# Baba General Store Udhari

यह Android ऐप अभी ऑफलाइन (फोन के SQLite database) में ग्राहक और लेन-देन सेव करता है।

## अभी उपलब्ध
- ग्राहक जोड़ना और मोबाइल नंबर रखना
- उधार देना और जमा लेना
- ग्राहक का कुल बाकी बैलेंस
- लेन-देन इतिहास
- WhatsApp / अन्य ऐप से हिसाब शेयर करना

## APK बनाना
GitHub repository में इस ZIP के अंदर की सभी फाइलें और `.github` folder upload करें। फिर:
1. GitHub में Actions खोलें।
2. `Build Baba Udhari APK` चुनें।
3. `Run workflow` दबाएँ।
4. सफल होने पर workflow run के नीचे Artifacts में APK ZIP डाउनलोड करें।
5. ZIP खोलकर `app-debug.apk` फोन में इंस्टॉल करें।

## Cloud backup की स्थिति
यह starter version अभी local offline database चलाता है। Automatic cloud sync चालू करने के लिए Firebase project और उसके सुरक्षित rules/configuration की जरूरत होगी। इसे जोड़े बिना ऐप को cloud backup वाला न समझें। फोन बदलने या ऐप हटाने से पहले फिलहाल डेटा का अलग backup जरूरी है।
