# Portfolio (শুধু HTML + CSS + JavaScript)

কোনো সার্ভার, ডাটাবেজ বা `npm install` লাগে না। `index.html` ডাবল ক্লিক করলেই সাইট খুলবে।

## ফাইল
- `index.html` : পুরো সাইট (ডিজাইন ও কোড)
- `data.js` : আপনার Projects, Services, Videos। **বদলাতে চাইলে শুধু এই ফাইল এডিট করুন।**
- `photo.webp` : আপনার ছবি (একই নামে নতুন ছবি দিলে বদলে যাবে)
- `images/` : প্রজেক্টের ছবি ও ছোট ভিডিও এখানে রাখুন

## এডিট করার নিয়ম (VS Code)
1. VS Code-এ ফোল্ডারটা খুলুন, `data.js` এডিট করে সেভ করুন।
2. প্রজেক্টের ছবি: ছবিটা `images/` ফোল্ডারে রাখুন, তারপর `img: "images/নাম.jpg"` লিখুন (ইংরেজি নাম, স্পেস ছাড়া)।
3. ভিডিও: `src: "images/নাম.mp4"` অথবা YouTube/Drive-এর `link: "https://..."`।
4. কম্পিউটারে দেখতে VS Code-এর "Live Server" এক্সটেনশন বা `index.html` সরাসরি খুলুন।

## GitHub Pages-এ ফ্রিতে চালু করা
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
git push -u origin main
```
তারপর GitHub-এ রিপোতে: Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main`, ফোল্ডার: `/ (root)` -> Save।
এক মিনিট পরে সাইট চালু: `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## পরে কিছু বদলালে
`data.js` (বা অন্য ফাইল) এডিট করে: `git add .` -> `git commit -m "Update"` -> `git push`। GitHub নিজেই আপডেট করে নেবে।

নোট: GitHub-এ একটা ফাইল ১০০ MB-এর কম হতে হবে। বড় ভিডিওর জন্য YouTube লিংক ব্যবহার করুন।
