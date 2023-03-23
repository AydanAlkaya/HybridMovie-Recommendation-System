# HybridMovie-Recommendation-System

## PROJE KONUMUZ:

### IMDB’den ve Kaggle’dan alınan veri setindekindeki verilerle kullanıcıya 3 farklı filtreleme yöntemi sunan; Collaborative filtering ve Content-based filtering yapan, ayrıca   kullanıcıya soru sorup kullanıcın girdisine göre filtreleme yapan bir film öneri sistemidir.


## VERİLER:
### Content-based filtering yöntemini kullandığımız IMDB-Movie-Data.csv adlı veri setinden sağlanmıştır. Veri setinde her örnek 999 özellik içerir. Bu nedenle, her dosya 999 x 12 girdiden oluşan bir tablo içerir. Veri setinin ilk satırı sınıflandırılacak özellikleri içerir. İlk satırında bulunan özellikler 'Rank', 'Title', 'Genre', 'Description', 'Director', 'Actors', 'Year', 'Runtime', 'Rating', 'Votes', 'Revenue ','Metascore’.
Collaborative filtering yönteminde kullandığımız verilerden biri ise movies.csv adlı veri setinden sağlanmıştır. Veri setinde her örnek 9742 özellik içerir. Bu nedenle, her dosya 9742 x 1 girdiden oluşan tablo içerir. Veri setinin ilk satırı sınıflandırılacak özellikleri içerir. İlk satırda bulunan özellik movieId, title, genres ‘dir. 
Collaborative filtering yönteminde kullandığımız diğer bir veri seti ise ratings.csv adlı veri setinden sağlanmıştır. Veri setinde her örnek 100836 özellik içerir. Bu nedenle, her dosya 100836 x 1 girdiden oluşan tablo içerir. Veri setinin ilk satırı sınıflandırılacak özellikleri içerir. İlk satırda bulunan özellik userId, movieId, rating, timestamp ‘dir.



## PROJENİN AMACI:
### Bu projenin amacı, bir kullanıcın film izlemek istediğinde Collaborative filtering ve Content-based filtering yöntemleriyle filtreleme yapan, ayrıca kullanıcıya birtakım sorular sorup ilgi alanına göre mümkün olan en yüksek doğru sınıflandırma yüzdesine sahip filmler önermektir.
