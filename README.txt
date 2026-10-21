আমার খাতা - Android অ্যাপ প্রজেক্ট

পথ ১: GitHub দিয়ে (কিছু ইনস্টল লাগে না)
1. github.com-এ বিনামূল্যে অ্যাকাউন্ট খুলে একটি নতুন repository বানান।
2. এই ZIP-এর সব ফাইল (লুকানো .github ফোল্ডারসহ) সেখানে আপলোড করুন।
3. Actions ট্যাবে গিয়ে "Build APK" চালান (Run workflow)।
4. ৫-১০ মিনিট পর কাজ শেষ হলে নিচের Artifacts থেকে amar-khata-apk নামান।
5. ZIP খুলে app-debug.apk ফোনে দিয়ে ইনস্টল করুন (Unknown sources অনুমতি দিতে হবে)।

পথ ২: নিজের কম্পিউটারে (Node.js ও Android Studio লাগবে)
npm install
npx cap add android
npx cap sync
npx cap open android
তারপর Android Studio-তে Build > Build APK(s)।

অ্যাপের কোড বদলাতে চাইলে www/index.html এডিট করুন।
