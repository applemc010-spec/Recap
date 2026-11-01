# Recap Matcher - طريقة الحصول على الـ EXE

1. سوّي حساب على github.com (مجاني) واضغط New repository، سمّه recap_matcher.
2. اضغط "uploading an existing file" وانسحب كل محتويات هذا المجلد (مع مجلد .github).
   ملاحظة: على ماك مجلد .github مخفي، اضغط Cmd+Shift+. حتى يظهر.
3. اضغط Commit changes.
4. افتح تبويب Actions - راح يبدأ "Build EXE" لحاله (5-10 دقايق).
5. بعد ما يخلص (علامة خضراء) افتح العملية ونزّل من Artifacts:
   - RecapMatcher-Windows : فيه recap_matcher.exe + ffmpeg.exe + ffprobe.exe جاهزين
   - RecapMatcher-macOS   : البرنامج لماك (يحتاج: brew install ffmpeg)
6. فك الضغط وشغّل recap_matcher.exe مباشرة.
