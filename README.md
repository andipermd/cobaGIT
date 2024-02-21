1. git init : add .git (create folder repository)
2. git remote -v : chek tujuan link repository
   - git remote add origin LINK_REPO : memasukkan link repo
   - git remote git remote set-url origin LINK_REPO : mengubah link repo
3. git status : melihat status perubahan pada repo
4. git clone LINK_REPO : mengambil file dari repo untuk di modifikasi dan di push kembali
5. git add . : menambahkan perubahan terbaru pada semua file
6. git commit -m : setelah di "git add . " tambhakan message
7. git branch -M main : tujuan branch
8. git push -u origin main : push ke dalan branch main

catatan : perlu di perhatikan default branch nya

<!-- Large file To GITHUB -->

1. git lfs install
2. git lfs track "\*.zip" : format file apa yang yg akan di push
3. git lfs push --all origin main
4. git add .
5. git commit -m ""
6. git push -u origin main
