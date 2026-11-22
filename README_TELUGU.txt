L.N MILK CENTER - Android APK Build Project

ఈ ZIP లో మీ ప్రస్తుత L.N MILK CENTER HTML యాప్‌ను Android WebView యాప్‌గా మార్చే source ఉంది.

APK తయారు చేయడానికి GitHub Actions cloud build ఉపయోగించాలి. ఈ ZIP స్వయంగా APK కాదు.

సులభమైన విధానం:
1. ZIP ను ఫోన్‌లో Extract చేయండి.
2. GitHub.com లో ఉచిత account తో sign in అవ్వండి.
3. New repository create చేయండి. పేరు: ln-milk-center
4. Extract చేసిన folder లోని files/folders అన్నీ repository main branch లో upload చేయండి. .github అనే hidden folder కూడా తప్పనిసరిగా upload కావాలి.
5. Repository లో Actions tab తెరవండి.
6. “Build L.N MILK CENTER APK” workflow ఎంచుకుని “Run workflow” నొక్కండి.
7. Build పూర్తయ్యాక run లోని Artifacts కింద LN-MILK-CENTER-APK download చేయండి.
8. ZIP extract చేసి app-debug.apk ను install చేయండి. Android అడిగితే ఈ source నుంచి Install unknown apps అనుమతించండి.

గమనికలు:
- GitHub account అవసరం; password/OTP ఎవరితోనూ పంచుకోవద్దు.
- ఇది debug APK. Play Store publish చేయడానికి signed release AAB వేరుగా తయారు చేయాలి.
- ప్రస్తుతం HTML యాప్‌లో ఉన్న localStorage data ఫోన్‌లోనే ఉంటుంది. Gmail/Google Drive automatic backup ఈ build లో లేదు. App uninstall చేస్తే local data పోవచ్చు; అందుకే app లోని Backup/Restore ఉపయోగించండి.
