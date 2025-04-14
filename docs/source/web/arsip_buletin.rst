.. include:: ../_static/substitution.rst

Arsip Buletin Doa
=================

Berikut ini adalah langkah-langkah yang perlu dilakukan ketika menambahkan edisi baru dalam arsip buletin doa, yang dibagi ke dalam beberapa tahap:

.. :note::
  Pastikan pengguna sudah login dengan akun Admin di situs web Kartidaya untuk dapat mengubah dan/atau menambahkan halaman.

Menambahkan Entri Baru
----------------------

#. Pastikan pengguna berada dalam mode Edit di halaman Doa, lalu aktifkan **Wireframe View** untuk dapat melihat semua modul pada halaman.

#. Klik pada tombol **Settings** di samping modul **CODE** untuk membuka jendela code editor.

#. Tambahkan entri baru pada posisi pertama dalam array **metas** dengan contoh format sebagai berikut:

    .. code-block:: json

      {
        "year": 2025,
        "volume": 12,
        "edition": 4,
        "idFlipbook": "b4359099bf",
        "enFlipbook": "5d8a3b2234",
        "idDownload": "1aQGNPZxZ0Sfgt8uX-n2EVBxcwJ7lZ-Lq",
        "enDownload": "1HjaKheIjLvP8Xh7GABzubNcNxsFWfjM_",
        "idTitle": "Suku Abawiri",
        "enTitle": "Abawiri People Group"
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
        - Judul edisi dalam bahasa Inggris (Kosongkan jika sama dengan bahasa Indonesia

