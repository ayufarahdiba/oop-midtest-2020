========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

To run the project from the command line, go to the dist folder and
type the following:

java -jar "AtmGUI.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have t========================
BUILD OUTPUT DESCRIPTION
========================

Ketika Anda membangun proyek aplikasi Java yang memiliki kelas utama, IDE
secara otomatis menyalin semua JAR
file pada classpath proyek ke folder dist / lib proyek Anda. IDE
juga menambahkan masing-masing file JAR ke elemen Class-Path dalam aplikasi
File JAR file manifes (MANIFEST.MF).

Untuk menjalankan proyek dari baris perintah, buka folder dist dan
ketik berikut ini:

java -jar "AtmGUI.jar"

Untuk mendistribusikan proyek ini, zip folder dist (termasuk folder lib)
dan mendistribusikan file ZIP.

Catatan:

* Jika dua file JAR pada classpath proyek memiliki nama yang sama, hanya yang pertama
File JAR disalin ke folder lib.
* Hanya file JAR yang disalin ke folder lib.
Jika classpath berisi jenis file atau folder lain, file-file ini (folder)
tidak disalin.
* Jika perpustakaan pada proyek classpath juga memiliki elemen Class-Path
ditentukan dalam manifes, konten elemen Class-Path harus di
jalur runtime proyek.
* Untuk mengatur kelas utama dalam proyek Java standar, klik kanan node proyek
di jendela Projects dan pilih Properties. Kemudian klik Jalankan dan masukkan
nama kelas di bidang Kelas Utama. Atau, Anda dapat mengetik secara manual
nama kelas dalam elemen Utama-Kelas manifes.he same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
