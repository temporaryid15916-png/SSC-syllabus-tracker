# SSC StudyHub

বাংলা ভাষার SSC প্রস্তুতি ও অধ্যায় ট্র্যাকার ওয়েব অ্যাপ।

## Features
- ৮টি বিষয় ও ৮৬টি অধ্যায়ের ট্র্যাকিং
- অধ্যায়ভিত্তিক স্ট্যাটাস/প্রগ্রেস
- নোট ও সার্চ/ফিল্টার
- সূত্র ভাণ্ডার
- Pomodoro study timer
- Daily goals
- Quiz / mock test
- Quiz-এ MCQ options দেখানো হয় না; প্রশ্ন দেখে নিজে উত্তর ভেবে **উত্তর দেখুন** চাপলে উত্তর ও ব্যাখ্যা দেখা যায়
- Progress ও কিছু user data `localStorage`-এ সংরক্ষিত হয়

## Run locally
`index.html` ফাইলটি ব্রাউজারে খুললেই অ্যাপটি চালানো যায়।

## GitHub Pages
1. GitHub-এ নতুন repository তৈরি করুন, যেমন `ssc-studyhub`
2. এই folder-এর `index.html`, `README.md`, `.gitignore` upload করুন
3. Repository → **Settings** → **Pages**
4. **Deploy from a branch** নির্বাচন করুন
5. Branch হিসেবে `main` এবং folder হিসেবে `/ (root)` নির্বাচন করুন
6. Save করুন
7. কিছুক্ষণ পর GitHub Pages-এর URL থেকে অ্যাপটি চালু হবে

## Note
অ্যাপটি static HTML/JavaScript ভিত্তিক; আলাদা backend প্রয়োজন নেই।
Tailwind CSS, Lucide Icons এবং Google Fonts CDN থেকে লোড হয়।
