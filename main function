def main():
    """
    Fungsi utama untuk menjalankan aplikasi Book Hunt.
    
    Program akan menampilkan menu, menerima input pengguna,
    dan memanggil fungsi pencarian / daftar buku sesuai pilihan.
    Berhenti ketika pengguna memilih opsi 0.
    """
    while True:
        tampilkan_menu()
        pilihan = input("Pilih opsi (0-4): ")

        if pilihan == "1":
            list_buku()
        elif pilihan == "2":
            cari_judul()
        elif pilihan == "3":
            cari_penulis()
        elif pilihan == "4":
            cari_genre()
        elif pilihan == "0":
            print("\nTerima kasih telah menggunakan Book Hunt! 📚")
            break
        else:
            print("\n❌ Pilihan tidak valid. Silakan pilih angka 0-4.")
