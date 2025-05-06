.. include:: ../_static/substitution.rst

Memperbarui Arsip Buletin Doa
=============================

Berikut ini adalah langkah-langkah yang perlu dilakukan ketika menambahkan edisi baru dalam arsip buletin doa di situs web Kartidaya.org, yang dibagi ke dalam beberapa tahap:

.. :note::
  Pastikan pengguna sudah login dengan akun Admin di situs web Kartidaya untuk dapat mengubah dan/atau menambahkan halaman.

#. Masuk ke halaman `Doa <https://kartidaya.org/doa/>`_ di situs web Kartidaya, lalu klik **Enable Visual Builder**.

    .. image:: ../images/arsip_buletin_1_1.png
      :width: 100%

#. Klik tombol toggle (``...``) di bagian bawah untuk membuka **Settings Bar**, lalu aktifkan **Wireframe View** di panel sebelah kiri. Maka semua modul yang ada pada halaman akan terlihat.

    .. image:: ../images/arsip_buletin_1_2.png
      :width: 100%

#. Klik tombol **Settings** di samping modul yang diberi judul **CODE - DO NOT DELETE**. Maka jendela **Code Settings** akan terbuka.

    .. image:: ../images/arsip_buletin_1_3.png
      :width: 100%

#. Cari variabel array bernama **metas**, lalu tambahkan entri baru pada posisi pertama dengan contoh format sebagai berikut:

    .. code-block:: json

      {
        "year": 2025,
        "volume": 15,
        "edition": 3,
        "idFlipbook": "4298febc3f",
        "enFlipbook": "ac354b6a77",
        "idDownload": "1Bz3BRX_qN8qYh9stZO2r9AKsOzTqYldR",
        "enDownload": "1X2Kz4IqrdLTXgmtIsG0pml-Vq1pbmKZm",
        "idTitle": "Gugus Sriwanda",
        "enTitle": "Sriwanda Cluster"
      },

    .. list-table::
      :widths: 25 25
      :header-rows: 1

      * - Key
        - Keterangan
      * - ``year``
        - Tahun edisi
      * - ``volume``
        - Volume edisi
      * - ``edition``
        - Nomor edisi
      * - ``idFlipbook``
        - ID Flipbook di Heyzine (Bahasa Indonesia)
      * - ``enFlipbook``
        - ID Flipbook di Heyzine (Bahasa Inggris)
      * - ``idDownload``
        - ID file PDF di Google Drive (Bahasa Indonesia)
      * - ``enDownload``
        - ID file PDF di Google Drive (Bahasa Inggris)
      * - ``idTitle``
        - Judul edisi dalam bahasa Indonesia
      * - ``enTitle``
        - Judul edisi dalam bahasa Inggris (Kosongkan jika sama dengan bahasa Indonesia)

#. Klik tombol **Save Changes** untuk menyimpan semua perubahan pada modul sekaligus menutup jendela **Code Settings**.

    .. image:: ../images/arsip_buletin_1_4.png
      :width: 300

#. Klik tombol **Save** untuk menyimpan semua perubahan pada halaman.

    .. image:: ../images/arsip_buletin_1_5.png
      :width: 100%

#. Klik **Exit Visual Builder** untuk keluar dari mode penyuntingan halaman, lalu cek apakah perubahan yang kita buat berhasil ditampilkan.

    .. image:: ../images/arsip_buletin_1_6.png
      :width: 100%

