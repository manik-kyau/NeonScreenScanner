# Neon Signal Bot — Native Android Screen Scanner

এই project Quotex-এর দৃশ্যমান screen/chart capture করে basic red/green pixel analysis চালায়।

## ব্যবহার
1. Android Studio-তে project খুলুন।
2. Gradle sync করে APK build করুন।
3. APK ফোনে install করুন।
4. Quotex Real Market chart খুলুন।
5. Neon Signal Bot → START SCREEN SCAN।
6. Android-এর screen capture permission Allow করুন।
7. Quotex screen/window নির্বাচন করুন।
8. Bot screen-এর visible chart pixels থেকে CALL/PUT/WAIT estimate দেখাবে।

## গুরুত্বপূর্ণ
- এই app Quotex-এর private/internal price feed পড়তে পারে না।
- এটি order place/auto-trade করে না।
- Screen pixel analysis একটি prototype; 100% accurate signal নয়।
- EMA/RSI/MACD-এর মতো true indicator চালাতে chart-এর OHLC data বা একই underlying market feed দরকার।
