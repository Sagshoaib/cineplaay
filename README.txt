CinePlay Android - APK banane ke steps (laptop par kuch install nahi karna)

1) https://github.com par free account banayein, "New repository" dabayein (naam: cineplay, Public ya Private).
2) Repository mein "uploading an existing file" dabayein aur is folder ke andar ki SAARI files/folders drag-drop karein
   (app, settings.gradle, build.gradle, gradle.properties). Commit changes dabayein.
3) Workflow file: "Add file > Create new file" dabayein, naam mein likhein:  .github/workflows/build.yml
   aur is folder ki .github/workflows/build.yml ka text paste karke commit karein
   (agar upload mein .github folder pehle hi chala gaya ho to ye step chhod dein).
4) "Actions" tab kholein > "Build APK" > "Run workflow". 3-5 minute wait karein.
5) Hare tick wale run par click karein > neeche "Artifacts" mein "CinePlay-apk" download karein, zip extract karein: app-debug.apk milegi.
6) APK ko phone mein bhejein (USB / Drive / WhatsApp), kholein, "Install unknown apps" allow karke install karein.
7) App kholein > "Allow access" dabayein. Ab phone ke saare videos aur gaane dikhenge.

Option B: Android Studio mein folder kholein > Build > Build APK(s).
