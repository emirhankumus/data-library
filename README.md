Aşağıdaki komutu doğru klasörde olduğunuzda çalıştırın:

```bash
jupyter notebook Recap.ipynb
```

---

Bu reboot’ta şunları kullanacağız:

- The [Goodreads books](https://www.kaggle.com/jealousleopard/goodreadsbooks) dataset from Kaggle (a CSV to download)
- The [Open Library Books API](https://openlibrary.org/dev/docs/api/books)

Bu projenin amacı, CSV dosyasındaki verileri yükledikten sonra her bir satırı döngüyle işleyerek aşağıdaki bilgilerle zenginleştirmektir:
 
- Konu listesi (Science, Humor, Travel vb.)
- Kitabın kapak görselinin URL’i
- JSON API’nin sunduğu ve işinize yarayabilecek diğer bilgiler