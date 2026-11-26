# कक्षपाल तैयारी PWA

## सेटअप (एक बार)
1. GitHub पर Public repo बनाएं (जैसे `kakshpal-app`) और इस folder की सारी files upload करें।
2. Settings → Pages → `main` branch / root → Save। ऐप का लिंक मिल जाएगा।
3. Chrome में लिंक खोलें → Install app।

## रोज़ नए सवाल जोड़ना (सिर्फ आप)
पहली बार की तैयारी:
- **Gemini key:** aistudio.google.com → Get API key
- **GitHub token:** GitHub → Settings → Developer settings → Fine-grained tokens → Generate new token → Repository access: सिर्फ यही repo → Permissions: **Contents = Read and write**

फिर रोज़:
1. ऐप का लिंक खोलें और लिंक के आखिर में `#admin` लगाएं (जैसे `https://naam.github.io/kakshpal-app/#admin`)।
2. पहली बार Gemini key, GitHub token और repo (`naam/kakshpal-app`) डालकर सेव करें।
3. **आज के नए सवाल बनाओ** दबाएं। सवाल देखें, गलत लगे तो निशान हटा दें।
4. **Publish करें** दबाएं। 1-2 मिनट में सब students को नए सवाल दिखेंगे।

## Students
कोई key या login नहीं। वे सिर्फ प्रश्न किताब पढ़ते हैं, अभ्यास और मॉक टेस्ट देते हैं।

## बदलने लायक
- एग्ज़ाम पैटर्न: `index.html` में ऊपर `CFG`।
- AI के सवाल में गलती हो सकती है, इसलिए Publish से पहले जाँच लें।
