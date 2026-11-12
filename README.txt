TUGAS PBO PERTEMUAN 8 - ENCAPSULATION

File:
BangunDatar.java, Persegi.java, Lingkaran.java,
PersegiPanjang.java, Segitiga.java, Main.java.

Cara menjalankan:
1. Buat Java Application baru di NetBeans.
2. Buat keenam file Java di Source Packages.
3. Letakkan semua file dalam package yang sama.
4. Jalankan Main.java.

Catatan:
- Atribut bangun datar bersifat private dan memiliki setter/getter.
- Class anak menggunakan extends BangunDatar.
- Method luas() dan keliling() dioverride.
- Diagram menandai luas() dan keliling() private, tetapi method
  private tidak dapat dioverride di Java. Karena instruksi tugas
  mewajibkan overriding, method tersebut dibuat protected abstract.
- Segitiga ditambah atribut sisiMiring untuk menghitung keliling.
