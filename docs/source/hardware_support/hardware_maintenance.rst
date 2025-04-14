.. include:: ../_static/substitution.rst

Pengecekan/Pemeliharaan Laptop
==============================

Dalam melakukan pengecekan atau pemeliharaan terhadap laptop, adapun skala penilaian yang dapat kita gunakan adalah sebagai berikut:

.. list-table::
  :widths: 25 25
  :header-rows: 1

  * - Skala
    - Keterangan
  * - :greentext:`Baik`
    - Aset dalam keadaan baru atau sangat baik, dan semua komponennya berfungsi sebagaimana mestinya
  * - :bluetext:`Cukup Baik`
    - Aset menunjukkan penurunan kualitas akibat usia/pemakaian, tetapi segala sesuatu masih berfungsi
  * - :orangetext:`Kurang Baik`
    - Aset mengalami kerusakan di beberapa komponen, tetapi masih dapat digunakan sampai batas tertentu
  * - :redtext:`Perlu Diganti`
    - Aset mengalami kerusakan berat sehingga pemakaiannya sangat terbatas atau tidak bisa dipakai sama sekali

Physical Condition
------------------

Beberapa hal yang perlu dicek saat memeriksa kondisi fisik laptop secara umum, termasuk charger:

* **Goresan & Penyok**: Adakah goresan atau bagian yang penyok?
* **Engsel**: Apakah engsel laptop berfungsi sebagaimana mestinya?
* **Fungsi Dasar**: Apakah semua *port* di laptop berfungsi (USB, audio jack, HDMI, dst..)?
* **Kelengkapan**: Adakah bagian yang hilang atau rusak (sekrup, karet pelindung, dsb..)?

Display
-------

Ketika memeriksa layar laptop, periksa:

* **Dead Pixels**: Adakah pixel yang mati atau titik-titik hitam pada layar?
* **Layar Bergaris/Berkedip**: Adakah bagian layar yang bergaris atau berkedip
* **Pencahayaan**: Apakah layar memiliki tingkat kecerahan yang konsisten atau ada yang cahayanya redup/mati?
* **Respons**: Jika layar sentuh, apakah interaksi sentuh berfungsi sebagaimana mestinya?

.. tip::
  Gunakan situs seperti `Test My Screen <https://testmyscreen.com>`_ untuk menolong pengecekan layar.

Camera
------

Ketika memeriksa kamera:

* **Fungsi**: Apakah kamera berfungsi dan gambarnya cukup jelas?

Keyboard & Touchpad
-------------------

Saat memeriksa keyboard dan touchpad:

* **Keys**: Apakah semua tombol di keyboard berfungsi? Adakah tombol yang terlalu mudah/sulit ditekan?
* **Touchpad**: Apakah touchpad cukup responsif saat disentuh/diklik?

.. tip::
  Gunakan situs seperti `Keyboard Test Online <https://keyboard-test.space/>`_ untuk menolong pengecekan dead keys dan touchpad.

Microphone
----------

Saat memeriksa mikrofon laptop:

* **Audio Input**: Apakah mikrofon dapat menangkap suara dengan baik?

.. tip::
  Gunakan situs seperti `Online Mic Test <https://onlinemictest.com>`_ untuk memeriksa sensitivitas mikrofon.

Speakers
--------

Saat memeriksa *speakers* pada laptop:

* **Audio Output**: Apakah *speakers* dapat menghasilkan suara? Jika tidak, periksa apakah sistem operasi sudah menggunakan *driver* yang sesuai/terbaru.
* **Kejernihan**: Apakah suara yang dikeluarkan jelas dan tidak retak-retak/bersemut?

.. tip::
  Gunakan situs seperti `Test My Screen <https://testmyscreen.com>`_ untuk menolong pengecekan layar.

Battery
-------

Saat memeriksa baterai laptop:

* **Battery Report**: Hasilkan *battery report* dengan menjalankan perintah berikut di PowerShell atau Command Prompt.

    .. code-block:: bash

      powercfg /batteryreport