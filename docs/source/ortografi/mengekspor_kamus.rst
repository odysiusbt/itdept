.. include:: ../_static/substitution.rst

Mengekspor Kamus
================

Tim penerjemah menggunakan program `WeSay <https://software.sil.org/wesay/>`_ untuk membuat kamus dalam bahasa daerah. Meskipun mengekspor kamus secara langsung melalui WeSay dimungkinkan, tetapi opsinya sangat terbatas dan hasilnya kurang bagus. Karena itu, `Lexique Pro <https://software.sil.org/lexiquepro/>`_ diperlukan sebagai program jembatan untuk mengekspor kamus dengan kustomisasi yang lebih bervariasi dan hasil yang relatif lebih bagus.

Berikut ini adalah langkah-langkah untuk mengekspor dokumen kamus dari program **WeSay** dan **Lexique Pro**.

Menyesuaikan *Custom Sorting*
-----------------------------

Terkadang kamus bahasa daerah menggunakan *custom sorting* untuk mengelompokkan kata-kata yang diawali oleh bunyi tertentu yang berbeda dari abjad, seperti: /ŋ/ atau /ʔ/. *Custom sorting* ini perlu ditransfer ke Lexique Pro untuk memastikan hasil ekspor kamus sesuai dengan pengelompokan kata yang seharusnya.

Lewati langkah ini jika kamus tidak menggunakan *custom sorting*.

#. Di jendela program **WeSay**, klik pada tab **Home**.

#. Klik kanan pada ruang kosong, lalu pilih **Configure this project...**.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_1.png
      :width: 300

#. Klik pada tab **Input Systems**, lalu pilih bahasa yang diinginkan di daftar sebelah kiri.

#. Dengan bahasa yang dipilih tersorot di sebelah kiri, klik pada tab **Sorting** di sebelah kanan.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_2.png
      :width: 300

#. Klik pada tab **Actions**, lalu pilih **Open in Lexique Pro**.

    .. attention::
      Menu **Open in Lexique Pro** tidak akan dapat dipilih jika program **Lexique Pro** belum diinstal.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_3.png
      :width: 300

#. Di jendela program **Lexique Pro**, klik **Tools** |rarr| **Configure Language** |rarr| **NAMA BAHASA**.

#. Pada tab **Sorting**, ubah pengaturan *sorting* dengan menggunakan **Custom Simple rules**, masukkan teks yang sudah disalin dari langkah sebelumnya, lalu klik **OK**.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_4.png
      :height: 250

Mengekspor sebagai Dokumen (``.docx``)
--------------------------------------

Lewati langkah 1-3 jika proyek kamus sudah terbuka di program Lexique Pro setelah menyesuaikan *custom sorting* seperti pada instruksi sebelumnya.

#. Di jendela program **WeSay**, klik pada tab **Home**.

#. Klik kanan pada ruang kosong, lalu pilih **Configure this project...**.

#. Klik pada tab **Actions**, lalu pilih **Open in Lexique Pro**.

    .. attention::
    	Menu **Open in Lexique Pro** tidak akan dapat dipilih jika program **Lexique Pro** belum diinstal.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_3.png
      :width: 300

#. Setelah itu, klik **File** |rarr| **Export as Document...**.

#. Pada bagian **Export Type**, pilih **Alphabetical Dictionary of lexical entries**, lalu klik **Next**.

#. Pada bagian **Export Fields**, pastikan semua *field* sudah dicentang, lalu klik **Next**.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_6.png
      :width: 300

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_7.png
      :width: 300

#. Pada bagian **Pictures**, pilih **None: do not include any pictures**, lalu klik **Next**.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_8.png
      :width: 300

#. Pada bagian **Page Settings** dan **Paragraph Settings**, atur sesuai konfigurasi berikut, lalu klik **Next**.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_9.png
      :width: 300

#. Pada bagian **Document Name**, pilih **Word 2007 Document (.docx)** sebagai tipe *output*. Klik **Next**, lalu klik **Export**.

#. Jika kamus berhasil diekspor, berkas baru akan berhasil dibuat. Klik **Find File in Explorer...** untuk menemukan berkas yang dimaksud atau klik **Close** untuk menutup jendela *wizard*.

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_11.png
      :width: 300

    .. image:: ../images/mengekspor_menggabungkan_kamus_1_12.png
      :width: 300

Menyesuaikan Format Dokumen
---------------------------

Jika teks kamus hasil ekspor dari Lexique Pro langsung disalin/tempel ke dokumen sistem penulisan, perbedaan pengaturan dan *styles* antara kedua dokumen tersebut akan menyebabkan konflik, sehingga dokumen akan perlu disesuaikan ulang. Penyesuaian ulang ini biasanya akan sangat manual dan memerlukan banyak waktu sehingga tidak efisien jika dilakukan berulang kali. Karena itu, sebelum teks kamus dapat digabungkan ke dokumen sistem penulisan, ada beberapa hal yang perlu kita lakukan terhadap dokumen kamus supaya teks siap untuk disalin/ditempel tanpa perlu banyak penyesuaian setelahnya.

Menghapus *Header* & *Footer*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Dokumen kamus hasil ekspor secara otomatis sudah memiliki *header* dan *footer*. Namun, *header* dan *footer* ini perlu kita hapus supaya ketika teks disalin ke dokumen sistem penulisan, teks akan mengikuti format *header* dan *footer* yang diatur di dokumen sistem penulisan.

#. Di jendela **Microsoft Word**, klik **File** |rarr| **Info** |rarr| **Check for Issues** |rarr| **Inspect Document**.

    .. image:: ../images/menyesuaikan_format_dokumen_1_1.png
      :width: 300

#. Berikan centang pada bagian **Headers, Footers, and Watermarks** dan hapus centang pada semua bagian yang lain, lalu klik **Inspect**.

    .. image:: ../images/menyesuaikan_format_dokumen_1_2.png
      :width: 300

#. Di jendela berikutnya, klik **Remove All** untuk menghapus semua *header* dan *footer*, lalu klik **Close**.

    .. image:: ../images/menyesuaikan_format_dokumen_1_3.png
      :width: 300

Mengatur Ukuran *Header* & *Footer*
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. Di jendela **Microsoft Word**, klik dua kali di bagian *header* atau *footer* untuk memunculkan tab menu **Header & Footer**.

#. Pada bagian **Position** di sebelah kanan, sesuaikan ukuran *header* & *footer* dengan pengaturan berikut:

    .. list-table::
      :widths: 25 25
      :header-rows: 1

      * - Opsi
        - Pengaturan
      * - Header from Top
        - 0.51 cm
      * - Footer from Bottom
        - 0.3 cm

#. Klik tombol **Close Header and Footer** untuk kembali ke editor dokumen.

Menghapus *Tabs* & *Breaks*
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Di dokumen hasil ekspor kamus, setiap entri kamus dan definisinya pasti dipisahkan dengan karakter *tab*, meskipun tidak terlihat. Dan, setiap *heading* abjad akan diikuti dengan *paragraph break*. Keduanya perlu dihapus untuk menghemat ruang dalam dokumen kamus.

#. Tekan tombol pintasan ``Ctrl + H`` untuk membuka jendela dialog **Find & Replace**.

#. Lakukan **Replace All** terhadap pola-pola berikut:

    .. list-table::
      :widths: 25 25 25
      :header-rows: 1

      * - Find
        - Replace
        - Keterangan
      * - ``^b``
        - (HAPUS)
        - Menghapus semua *paragraph breaks*
      * - ``^t``
        - (HAPUS)
        - Menghapus semua karakter *tab*

Mengatur Tampilan Dua Kolom
^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. Tekan tombol pintasan ``Ctrl + A`` untuk menyorot semua teks dalam dokumen

#. Klik **Layout** |rarr| **Columns** |rarr| **Two**.

