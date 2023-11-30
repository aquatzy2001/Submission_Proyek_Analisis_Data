# Project Data Analytics

 Repositori yang berupa projek analis data, yang dibuat dengan menggunakan **Streamlit** <img src="https://user-images.githubusercontent.com/7164864/217935870-c0bc60a3-6fc0-4047-b011-7b4c59488c91.png" alt="Streamlit logo"></img>

## Deskripsi

<div style='text-align: justify;'>
Proyek ini berupa analis data terhadap <strong>E-Commerce Public Dataset</strong> yang divisualisasikan menggunakan Streamlit. Tujuan utamanya yakni untuk memberikan pengetahuan terkait analisis data menggunakan bahasa python.
</div>

## Sumber Data
E-Commerce Public Dataset [(Link Download)](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view)

## Instalasi

1. Download file dataset ke penyimpanan komputer.
2. Kemudian upload dataset ke Drive pribadi.
3. Pada Google Colab:

    ```shell
    from google.colab import drive
    ```
4. Kemudian untuk file **streamlit**, lakukan Instalasi Library di VS Code dengan perintah berikut:

    ```shell
    pip install streamlit seaborn pandas matplotlib
    ```

## Penggunaan Streamlit
1. Melakukan Akses dan Kompilasi(Local):

    ```shell
    cd streamlit
    streamlit run main.py
    ```