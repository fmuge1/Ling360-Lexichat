Ön Not: TÜRKÇE metni aşağıda bulabilirsiniz.

LEXI-CHAT
===========


Project Description
-------------------

LEXI-CHAT is a word guessing game supported by simple natural language processing techniques and the natural language processing model, ChatGPT-3.5 Turbo, an artificial intelligence. By using these techniques, it aims to give the user the feeling of interacting with a real host and to design a more enjoyable and efficient game based on mutual communication. The conversational language used is intended to resemble the host of the "Word Game" competition, "Ali İhsan Varol." In addition to having fun, the project is envisioned as an effective method for improving language skills.


Installation and Usage
----------------------

Prerequisites:
----
Below are the files required to run the program:

1. ".txt files" containing questions and answers (Gungore, 2022)
2. "gts.json" file for the usage of hint functions (Işık, 2019)
3. If you are using the ChatGPT API key stored in a .json file, the "datakey.json" file

You need to add these files to the directory where the code is located if you are running the code locally; if you are running it in an online environment (e.g., Colab), you need to upload them to that directory.

Code:
----
All the code is stored in a single main file. After opening the Lexichat.ipynb file, you can run the entire code at once and activate the functions. If you don't have a "datakey" file, you can deactivate the relevant part in the code and follow the instructions provided in the code comments to upload your API key and run the entire code. Alternatively, you can replace your API key with the sample key provided in the datakey.json file and use that file. After successfully completing this, you can run the "run()" function at the bottom and try the game.


Game Rules
--------------

"""
    Before starting the game, please read the following points that include the rules and steps to ensure an enjoyable gaming experience.

    1. This game is designed inspired by the Turkish TV show "Kelime Oyunu" to make you feel the presence of the host.
    2. The game consists of a total of 14 questions, ranging from 4-letter to 10-letter words, with two questions for each length. You have 5 minutes to answer the questions.
    3. Each letter has a value of 100 points, and the maximum score you can achieve in the game is 9800 points.
    4. During the game, you can request a letter by typing "h" for any word. Each opened letter deducts 100 points from the score that the word would give you.
    5. You can request additional information about the word or write your guesses using the message box provided.
    6. Based on your guesses or the current score, the host can provide you with additional hints.
    7. If you think one of your guesses is correct, you should first type "bb" to stop the running time and then provide your answer in the newly opened box.
    8. The game will end after completing the 14 questions or if you finish the entire game time before the questions, and your total score will be shown.

    NOTE: To get the most out of the game, please refrain from communicating with the host in a way that may deceive it. Yes, you can trick, cause errors, and break the host, but please remember that one day it can break you too.

                                                                            HAVE FUN!
"""


Gameplay
-------
You can follow this link for an example gameplay video: https://www.youtube.com/watch?v=9jmTaclAfTE
Note: The server audio and visuals in this video are not included in the program.


Contributors
---------
Fatma Müge Akcan
Nurullah Ertaş
Stenai Nuh


References
---------

The following resources have been used in the development of this project:

- [word-game](//github.com/arasgungore/word-game): A similar word game project, the .txt files are obtained from here.
- [guncel-turkce-sozluk](https://github.com/ogun/guncel-turkce-sozluk): A comprehensive dictionary repository, the gts.json file is obtained from here.
- [zemberek-python] (https://github.com/loodos/zemberek-python/tree/master): The python version of the Zemberek, an NLP library for Turkish.
- [TurkishWordnet-Py] (https://github.com/StarlangSoftware/TurkishWordNet-Py/tree/master): The Turkish wordnet by StarlangSoftware.

We would like to thank these contributors for their assistance and support in developing this project.

For more detailed information, you can visit these resources.





TÜRKÇE
------


LEXI-CHAT
===========

Proje Açıklaması
----------------

LEXI-CHAT, basit doğal dil işleme teknikleriyle ve doğal dil işleme modeli yapay zeka Chatgpt-3.5 Turbo ile desteklenmiş bir kelime tahmin etme oyunudur.
Bu teknikleri kullanarak kullanıcıya gerçek bir sunucu ile iletişim kuruyor hissiyatı vermesi amaçlanmış ve karşılıklı iletişime dayalı daha keyifli ve verimli bir oyun tasarlanması hedeflenmiştir.
Sunucunun bir kişiliği olması hedeflenerek kullanılan konuşma dili "Kelime Oyunu" yarışması sunucusu "Ali İhsan Varol"a benzetilmesi amaçlanmıştır.
Eğlenmenin yanında projenin, dil becerisini geliştirmek için etkin bir yöntem olarak da değerlendirilebileceği ön görülmüştür.


Kurulum ve Kullanım
-------------------

Ön adımlar:
----
Programı çalıştırmak için gereken bazı dosyalar aşağıda verilmiştir, bunlar:

1- Soru ve yanıtlarını içeren ".txt dosyaları" (Gungore, 2022)
2- İpucu işlevlerinin kullanımı için "gts.json" dosyası (Işık, 2019)
3- Eğer Chatgpt api anahtarınızı .json dosyasında depolayarak kullanıyorsanız "datakey.json" dosyası

Bu dosyaları, eğer kodu yerelde çalıştırıyorsanız, kodun bulunduğu dosya dizinine eklemeniz; eğer çevrim içi ortamda (örn. Colab)
çalıştırıyorsanız o dizine yüklemeniz gerekmektedir.

Kod:
----
Tüm kod tek bir main dosyasında depolanmıştır. Lexichat.ipynb dosyasını açtıktan sonra
tüm kodu tek seferde çalıştırıp fonksiyonları aktif hale getirebilirsiniz ("datakey" dosyanız yoksa
kod içerinde bulunan ilgili kısmı pasif hale getirip size kod üzerinde yorumlar ile sağlanan yönlendirmeler ile
api anahtarınızı yükleyip tüm kodu çalıştırabilirsiniz ya da api anahtarınızı size sağlanan datakey.json dosyası içerisindeki örnek anahtar ile değiştirip, o dosyayı kullanabilirsiniz).
Bunun başarılı bir şekilde tamamlanması sonrasında en altta bulunan "run()" fonksiyonunu çalıştırıp oyunu deneyebilirsiniz.


Oyun kuralları
--------------

"""
    Oyuna başlamadan önce lütfen kuralları ve oyun sürecinde, oyundan keyif almanızı sağlayacak adımları içeren aşağıdaki maddeleri okuyunuz.

    1- Bu oyun bir televizyon programı olan "Kelime Oyunu"ndan ilham alarak hazırlanmış ve size sunucunun varlığını hissettirecek şekilde tasarlanmıştır.
    2- Oyunda, size verilen 5 dakikayı kullanarak bilmeniz gereken 4 harflilerden 10 harfli kelimelere kadar her birinden iki tane olacak şekilde toplam 14 soru bulunmaktadır.
    3- Her bir harf değeri 100 puan olmakla beraber oyundan alabileceğiniz maksimum puan  9800 puandır.
    4- Oyunda, herhangi bir kelime için "h" yazarak harf talep edebilirsiniz, her açılan harf için o kelimenin size kazandıracağı puandan 100 puan eksilir.
    5- Oyun süresince size verilen mesaj kutucuğundan, soru öncesi ya da sırasında kelime ile ilgili ek bilgi talep edebilir ve tahminlerinizi yazabilirsiniz.
    6- Yazdığınız tahminlere ya da içinde bulunduğunuz puan durumuna göre sunucu size ek ipuçları verebilir.
    7- Tahminlerinizden birinin doğru olduğunu düşünüyorsanız yanıtınız kabul edilmesi için önce "bb" yazıp akan süreyi durdurmalı ve açılan yeni kutucukta yanıtınızı belirtmelisiniz.
    8- 14 soru da bittikten sonra ya da oyun süresinin tamamını sorulardan önce bitirdiğinizde oyun sonlanacaktır ve toplam puanınız gösterilecektir.

    NOT: Oyundan yüksek verim almak için lütfen oyun sunucusunu aldatmaya yönelik iletişim kurmaktan çekininiz. Evet, siz sunucuyu kandırabilir, hata vermesine neden olabilir ve kırabilirsiniz ancak
    lütfen bir gün onun da sizi kırabileceğini hatırlayın.

                                                                            KEYİFLİ OYUNLAR
"""


Oynanış
-------
Örnek oyun videosu için bu bağlantıyı takip edebilirsiniz: https://www.youtube.com/watch?v=9jmTaclAfTE
Not: Bu videodaki sunucu sesi ve görüntüsü, programa dahil edilmemiştir. 


Katkıda Bulunanlar
---------
Fatma Müge Akcan
Nurullah Ertaş
Stenai Nuh


Kaynaklar
---------

Bu projeyi geliştirirken aşağıdaki kaynaklardan yararlanılmıştır:

- [word-game](//github.com/arasgungore/word-game): Benzer bir kelime oyunu projesi, .txt dosyaları buradan alınmıştır.
- [guncel-turkce-sozluk](https://github.com/ogun/guncel-turkce-sozluk): Detaylı bir sözlük deposu, gts.json dosyası buradan alınmıştır.
- [zemberek-python] (https://github.com/loodos/zemberek-python/tree/master): The python version of the Zemberek, an NLP library for Turkish.
- [TurkishWordnet-Py] (https://github.com/StarlangSoftware/TurkishWordNet-Py/tree/master): The Turkish wordnet by StarlangSoftware.

Projeyi geliştirirken bize kolaylık sağlayan ve yardımcı olan bu isimlere teşekkür ederiz.

Siz de daha detaylı bilgi için bu kaynakları ziyaret edebilirsiniz.
