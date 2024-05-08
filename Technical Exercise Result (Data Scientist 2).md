# Technical Exercise Result (Data Scientist 2)

### Project name: Submission Analisis Data **Bike Sharing**

## Project Summary

- Memberikan dokumentasi menggunakan **text cell** pada notebook (.ipynb) untuk menjelaskan **setiap tahapan analisis data**.
- Membuat visualisasi data yang baik dan efektif
- Konklusi pertanyaan bisnis masih kurang tepat dan perlu diperbaiki.
- Selain menggunakan matplotlib, kamu dapat mencoba memanfaatkan library seaborn untuk menampilkan visualisasi data yang telah kamu buat.

Sebagai tambahan kamu bisa menerapkan saran berikut.

- Deploy dashboard ke dalam **streamlit cloud**.
- **Menerapkan teknik analisis lanjutan** seperti *RFM analysis*, *geoanalysis*, *clustering*, dll. (Tanpa menggunakan algoritme machine learning).

Kedepannya kamu bisa mencoba mengembangkan kemampuanmu dengan lebih explore lagi mengenai streamlit. Kamu bisa mempelajari : **[Streamlit cheat sheet](https://docs.streamlit.io/library/cheatsheet)**.

Berikut beberapa framework visualisasi data yang dapat kamu pelajari :

- **[The McCandless Method](https://www.informationisbeautiful.net/visualizations/what-makes-a-good-data-visualization/)**
- **[Kaiser Fung’s Junk Charts Trifecta Checkup](https://junkcharts.typepad.com/junk_charts/junk-charts-trifecta-checkup-the-definitive-guide.html)**

Agar kemampuan analisa datamu menjadi lebih luas, kamu bisa mempelajari lebih dalam tentang materi berikut :

- **[Pandas cheat sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)**
- **[Matplotlib cheat sheet](https://matplotlib.org/cheatsheets/_images/cheatsheets-1.png)**
- **[Seaborn cheat sheet](https://www.kaggle.com/code/themlphdstudent/cheat-sheet-seaborn-charts)**

# Code Review

```markdown
- Conclution pertanyaan 1 Pada riset kali ini, kita tidak menggunakan chi square error test, melainkan hanya melihat dari tabel visualisasi date. pada tabel tersebut dapat dilihat bahwa kurva yang dimiliki temperature mirip dengan data pengguna harian. Maka dapat dikonklusikan bahwa temperature memiliki korelasi dengan catatan pengguna harian.
- conclution pertanyaan 2 Pada riset kedua, kita akan melihat pada tabel visualiasi month. Dari tabel tersebut dapat dilihat bahwa catatan pengguna hariannya menaik walau terdapat penurun di beberapa periode waktu. Hal ini dapat terjadi akibat perubahan cuaca maupun liburan yang membuat penggunanya tidak menggunakan sepeda.
```

> Konklusi dari pertanyaan bisnis yang telah diajukan masih belum tepat. Pada analisis hubungan atau korelasi 2 variabel jenis korelasi yang dapat terjadi antara lain korelasi positif, negatif, dan tidak ada korelasi. Pada konklusi kedua anda perlu menjelaskan terlebih dahulu mengapa perubahan catatan pengguna dipengaruhi perubahan cuaca dan liburan.
>