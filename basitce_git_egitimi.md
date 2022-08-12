												## 			BASİTÇE GİT (Versiyon Kontrol Sistemi)



### GİT TEMEL KOMUTLARI

***git init*** --> bir projede ilk defa git kullanılacaksa git bileşenleri eklemek için kullanılan komuttur. yani projemizie boş bir git deposu eklememizi sağlar.



***git add*** --> untraced(izlenmeyen) veya üzerinde değişiklik yapılan dosyaların *tek tek* staged ortamına eklenip git tarafından takip edilmesini sağlayan komut.

***git add .*** -->gitignore dosyasını projemize ekledikten sonra, bu konutu kullanarak tüm dosyaları tek seferde staged ortamına ekleyebiliriz.



***git rm*** --cached --> staged ortamına eklenmiş bir dosyanın takibinin bırakılmasını sağlar.



***git commit*** --> projemizin anlık snapshat(anlık görüntü) lerini almamızı sağlayan komuttur. yani staged ortamındaki dosyaların yerel repository' mize göndermemizi sağlar. 

***git commit -m 'açıklama'***--> komuttu anlık görüntülerimizde yaptığımız 						  		değişikliklere açıklama eklememiz için kullanılan komut.

***git log*** --> projemizdeki tüm commit geçmişimizi görüntüleyen komuttur.



***git config --global user.name "user_name"*** , ***git config --global user.email "user_email"***--> projemizde hangi kullanıcının nasıl değişiklikler yaptığını görmek için kullanıcı ismi  ve kullanıcı emaili eklememizi sağlayan komuttur. ilk defa commitleme işlemi yaptığımızda, git bize bir kullanıcı ismi  ve e-mail oluşturmamız gerektiğini söyler.



*** git config --list***--> yapılan tüm configrasyon ayarlarını görmek için kullanılan komut.



***git status*** -->üzerinde çalışılan projenin anlık değişimlerini görüntülememizi sağlayan komut.



***git diff*** --> projemizde yaptığımız değişikliklerden sonra dosyalar arasında oluşan farklılıkları ayrıntılı görmemizi sağlayan komut.



***git branch*** --> local veya remote repository üzerinde yeni bir branch ekleme (***git branch <branch_name>***), silme (***git branch -d <branch_name>***) veya listelemek (***git branch -a***) için kullanılan komuttur.



***git checkout*** --> brach'ler (***git checkout <branch_name>***) veya commit'ler (***git chackout <commit_id>***) arası geçiş yapmak için kullanılan komut. 



***git merge  <branch_name>***--> başka bir branch ta olan değişiklikleri, bulunduğumuz branch ile birleştirmek için kullanılır.



***git clone <remote_URL>*** -->  bir Remote Repository nin bilgisayarımızda bir kopyasının oluşturulmasını sağlayan komut.



***git remote add remote_baglantısı***--> local repository ile remote repository arasındaki bağlantıyı kurar. 



***git remote add depo_ismi remote_baglantısı*** --> uzak repository eklememizi sağlayan komut.



***git push -u depo_ismi branch_ismi*** --> projemizin remote repository ye eklenmesini sağlayan komut.



***git pull*** --> remote Repository den loacal Repository' ye projenin eklenmesini sağlayan komut.



		### .GİTIGNORE DOSYASI

Projemizdeki;

görseller, videolar, logolar, paket yöneticisiyle gelen vb. versiyon kontrol sistemine yüklemek istemediğimiz dosyaların eklendiği dosyadır. Bu bilgiler sadece localimizde  kalır paylaşılmaz.



Gitignore dosyasına hangi dosyaları eklenmememiz gerektiğini bilmiyorsak, internette "gitignore_`hangi dili kullanıyorsak`" yazarsak eklemememiz gereken dosyaları bulabiliriz.





		### GİT SERVİSLERİ

### `GitHub`

Yazılımcılar için bir kod kütüphanesi ve bir çeşit sosyal medya ortamıdır. Ücretli ve ücretsiz paket seçenekleri mevcuttur.

### `GitLab`

GitHub gibi bir GIT servisidir. Farklı olarak firmalara GitLab'ı kendi sunucularına kurma imkanı verildiği için genelde kurumsal tarafta kullanılır. 

### `BitBucket`

Genelde kişisel kullanıma yöneliktir. GitHub tarafındaki açık kaynak projeler ve sosyal medya ortamı burada gelişmemiştir.



		### README.md DOSYASI

​	.md(markdown) dısyası kısaca projelerimize açıklayıcı bilgiler eklemeye yarayan kullanışlı ve basit bir dosya tipidir. Basitçe bazı özellikleri mevcuttur. Sadece Githup ta değil diğer dillerle yaptığımız projelerde de kullanabileceğimiz bir dosyadır. ayrıntılı bilgi için;

[markdown](https://commonmark.org/ ) sitesine bakabilirsiniz.

 [Taypora](https://typora.io/),  markdown yazmak için çok kullanışlı bir  bir editör olan editörü de  kullanılabilir.

