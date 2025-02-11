# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
 Git, proje içerisinde yapılan değişiklikleri yönetmek için kullanılan açık kaynaklı versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git, açık kaynaklı versiyon kontrolünü sağlayan bir sistemdir. Github, git tabanlı projeleri içinde depolayan, yönetimi ve paylaşımını sağlayan bir platformdur.
3. Neden bir branch oluşturuyoruz?
Ana kod tabanını koruyarak geliştirilme esnasında yeni özellikler eklemek veya oluşan hataları düzeltebilmek için github'da branch oluşturulur.
4. Pull Request'in amacı nedir?
Branch'lerde değiştirilen kodları master branch ile birleştirmek için gönderilen istektir.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout [main]
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git merge; iki branch'i birleştirir, git pull; uzak sunucudaki değişiklikleri çekip local branch ile birleştirir, git fetch ise uzak sunucudaki değişiklikleri local bir kopyaya çeker fakat local branch ile birleştirmez. 
7. Merge conflict nedir?
İki farklı branchte aynı satırların değiştirilmesi sonucu birleştirme işlemi yaparken karşılaşılan çakışmadır.
8. Merge conflict'i nasıl çözeriz?
