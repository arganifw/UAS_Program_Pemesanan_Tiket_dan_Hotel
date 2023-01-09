#include <stdio.h>

	int main()
{
    char awal[3][99]={"1. Tiket Bus","2. Hotel"};
    char tiket[4][99]={"1. Yogyakarta\t\tRp.125.000\tRp.250.00\tRp.500.000","2. Bandung\t\tp.250.000\tRp.350.000\tRp.750.000"
                       ,"3. Bali\t\tRp.750.000\tRp.1.500.000\tRp.2.500.000","4. Lombok\t\tRp.1.000.000\tRp.2.000.000\tRp.3.000.000"};
    char hotel[4][99]={"1. Bintang 2\t\tRp.125.000\tRp.200.000\tRp.350.000","2. Bintang 3\t\tRp.200.000\tRp.300.000\tRp.450.000",
                       "3. Bintang 4\t\tRp.350.000\tRp.500.000\tRp.750.000","4. Bintang 5\t\tRp.500.000\tRp.750.000\tRp.1.000.000"};
    int harga,umur,diskon,total,jp; /*deklarasi untuk harga, diskon,jumlah pesanan,umur, dan total*/
	char menu,kode,kelas,nambah; /*deklarasi untuk kode,kelas,nambah*/
	char nama[50],alamat[100],telepon[20];


	printf("==SELAMAT DATANG DI TRAVEL KUY==\n\n");
	printf("Harap Lengkapi Data Diri Anda\n");
	printf("------------------------------\n");
    printf("Masukkan Nama Anda: ");
    scanf("%s", &nama);
    printf("Masukkan Umur Anda: ");
    scanf("%d",&umur);
    printf("Masukkan Alamat:(tanpa spasi) ");
    scanf("%s",&alamat);
    printf("Masukkan Nomor telepon: ");
    scanf("%s",&telepon);
    system("cls");

    for (;;)/*untuk perulangan jika ada yang ingin ditambahkan*/
    {
    for (int i=0;i<3;i++)
    {
    printf(" %s \n",awal[i]);
    }
    printf("Masukkan Pilihan  Anda:");
    scanf("%d",&menu);

 switch(menu)/*proses yang akan dilakukan saat kode telah diinput oleh user*/

	{
    case 1:

    system("cls");
    printf("\n                             PO. TAWON KITA                                  \n");
	printf("\n^^^^^^^^^^^^^^^^^^^^^^^^^Reservasi Tiket Pesawat^^^^^^^^^^^^^^^^^^^^^^^^^^^^^\n");
	printf("\n=============================================================================\n");
	printf("Tujuan Anda                  Kelas          Kelas         Kelas\n");
	printf("                           Ekonomi(E)     Bisnis(B)     Eksekutif (X)\n");
	printf("===============================================================================\n");
    for (int i=0;i<4;i++)
    {
    printf(" %s \n",tiket[i]);
    }
    printf("===============================================================================\n");


    printf("\nPilih tujuan anda (1/2/3/4): ");
	scanf("%d",&kode);

	switch(kode)/*proses yang akan dilakukan saat kode telah diinput oleh user*/
	{
		case 1: {/*proses yang akan dilakukan saat user memasukkan kode 1*/
					printf("Tujuan Anda : Yogyakarta\n");
					printf("\n-----------Silahkan Pilih Kelas Pesawat---------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=125000;
						total=harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d",umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Yogyakarta");
						printf("\nKelas: Ekonomi");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp. %d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=250000;
						total=harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Yogyakarta");
						printf("\nKelas: Bisnis");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=500000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Yogyakarta");
						printf("\nKelas: Eksekitif");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
			break;
		}
		case 2: /*proses yang akan dilakukan saat user memasukkan kode 2*/
			{printf("Tujuan Anda : Bandung\n");
					printf("\n-------------Silahkan Pilih Kelas Pesawat-----------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=250000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Bandung");
						printf("\nKelas: Ekonomi");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=350000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Bandung");
						printf("\nKelas: Bisnis");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=750000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Bandung");
						printf("\nKelas: Eksekutif");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}

			break;
		}
		case 3: /*proses yang akan dilakukan saat user memasukkan kode 3*/
			{printf("Tujuan Anda : Bali\n");
					printf("\n-------------Silahkan Pilih Kelas Pesawat-----------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=750000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Bali");
						printf("\nKelas: Ekonomi");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=1500000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Bali");
						printf("\nKelas: Bisnis");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=2500000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Bali");
						printf("\nKelas: Eksekutif");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
			break;
		}
		case 4:/*proses yang akan dilakukan saat user memasukkan kode 4*/
			{printf("Tujuan Anda : Lombok\n");
					printf("\n-------------Silahkan Pilih Kelas Pesawat-----------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=1000000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Lombok");
						printf("\nKelas: Ekonomi");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=2000000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Lombok");
						printf("\nKelas: Bisnis");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=3000000;
						total= harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nTujuan: Lombok");
						printf("\nKelas: Eksekutif");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga Tiket : Rp.%d",harga);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
        break;
		}
		default:
			printf("Maaf, Anda Salah Memasukkan Kode");/*jika user salah memasukkan kode, maka proses akan dimasukkan ke default*/
		}
		break;
        case 2: {/*proses yang akan dilakukan saat user memasukkan kode 1*/

    system("cls");
    printf("\n                             RESERVASI HOTEL                                 \n");
    printf("\n^^^^^^^^^^^^^^^^^^^^^^^^^^^Pilihan Kamar Hotel^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^\n");
    printf("\n===============================================================================\n");
    printf("Kelas Hotel              Kelas              Kelas           Kelas              \n");
    printf("                     Standart Room(E)    Twin Room(B)     VIP Room (X)         \n");
    printf("===============================================================================\n");
    for (int i=0;i<4;i++)
    {
    printf(" %s \n",hotel[i]);
    }
            printf("===============================================================================\n");


	printf("\nPilih Kelas Hotel (1/2/3/4): ");
	scanf("%d",&kode);

	switch(kode)/*proses yang akan dilakukan saat kode telah diinput oleh user*/
	{
		case 1: {/*proses yang akan dilakukan saat user memasukkan kode 1*/
					printf("Kamar Anda : Bintang 2\n");
					printf("\n-----------Silahkan Pilih Kelas Kamar---------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=125000;
						diskon = 0;
						total=harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 2");
						printf("\nKelas: Standart");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp. %d",harga);
						printf("\nDiskon: %d%%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=200000;
						diskon = 0;
						total = harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 2");
						printf("\nKelas: Twin");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);

					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=350000;
						diskon = 5;         //PPN=5%
						total=(harga-(harga*0.05))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 2");
						printf("\nKelas: VIP");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %% ",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
			break;
		}
		case 2: /*proses yang akan dilakukan saat user memasukkan kode 2*/
			{printf("Kelas Anda : Bintang 3\n");
					printf("\n-------------Silahkan Pilih Kelas Kamar-----------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=200000;
						diskon=0;
						total=harga*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 3");
						printf("\nKelas: Standart");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=300000;
						diskon = 5;         //PPN=5%
						total=(harga-(harga*0.05))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 3");
						printf("\nKelas: Twin");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=450000;
						diskon = 5;         //PPN=5%
						total=(harga-(harga*0.05))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 3");
						printf("\nKelas: VIP");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}

			break;
		}
		case 3: /*proses yang akan dilakukan saat user memasukkan kode 3*/
			{printf("Kamar Anda : Bintang 4\n");
					printf("\n-------------Silahkan Pilih Kelas Kamar-----------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=350000;
						diskon = 5;         //PPN=5%
						total=(harga-(harga*0.05))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 4");
						printf("\nKelas: Standart");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=500000;
						diskon = 10;         //PPN=5%
						total=(harga-(harga*0.1))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 4");
						printf("\nKelas: Twin");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=750000;
						diskon = 10;         //PPN=5%
						total=(harga-(harga*0.1))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 4");
						printf("\nKelas: VIP");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
			break;
		}
		case 4:/*proses yang akan dilakukan saat user memasukkan kode 4*/
			{printf("Kamar Anda : Bintang 5\n");
					printf("\n-------------Silahkan Pilih Kelas Kamar-----------\n");
					printf("Masukkan Kode Kelas (E/B/X): ");
					scanf("%s",&kelas);
					printf("Jumlah Pesanan :");
					scanf("%d", &jp);
					system("cls");
					if(kelas=='E' || kelas=='e')
					{
						harga=500000;
						diskon = 10;         //PPN=5%
						total=(harga-(harga*0.1))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 5");
						printf("\nKelas: Standart");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='B' || kelas=='b')
					{
						harga=750000;
						diskon = 10;         //PPN=5%
						total=(harga-(harga*0.1))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 5");
						printf("\nKelas: Twin");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
					else if(kelas=='X' || kelas=='x')
					{
						harga=1000000;
						diskon = 10;         //PPN=5%
						total=(harga-(harga*0.1))*jp;
						printf("Nama: %s", nama);
						printf("\nUmur: %d", umur);
						printf("\nAlamat: %s",alamat);
						printf("\nNo telp: %s",telepon);
						printf("\nHotel: Bintang 5");
						printf("\nKelas: VIP");
						printf("\nJumlah Pesanan: %d", jp);
						printf("\nHarga: Rp.%d",harga);
						printf("\nDiskon: %d %%",diskon);
						printf("\nTotal pembayaran : Rp.%d",total);
					}
			break;
		}
		default:
			printf("Maaf, Anda Salah Memasukkan Kode");/*jika user salah memasukkan kode, maka proses akan dimasukkan ke default*/
		}
    }
}
            printf("\n\nApakah Anda Ingin Memesan yg Lain?  (y/t):");/*jika user ingin membeli tiket lagi*/
			scanf("%s",&nambah);
			system("cls");
			if(nambah=='t')/*jika tidak, maka proses akan berhenti, jika iya maka proses akan berulang*/
				break;
}
    printf("\n\n========================== Terima Kasih =============================\n");
	system("PAUSE");


	return 0;
    }


