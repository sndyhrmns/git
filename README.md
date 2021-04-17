# git
git config --global user.name "username anda"
git config --global user.email "email anda"

//Login ke git dengan akun github

====================================================
// pertama kali membuat repo
git init                      = inisialisasi repo lokal
git add .                     = menambah file
git commit -m "komentar anda" = membuat checkpoint / nama revisi
git add remote add origin link-repo-anda = memberikan alamat pada repo lokal

git push origin master = upload ke github

====================================================
git clone link-repo = mengambil / download repositori le laptop

=====================================================
git remote add upstream link-repo-fork = mengambil alamat repo pemilik asli

upsream = pemilik asli hasil fork.
origin  = repo di github kita
