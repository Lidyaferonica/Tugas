# Tugas java membuat perulangan hingga 100, program bebas dengan menerapkan if else perulangan while, program zodiak, variabel dengan tipe array menggunakan perulangan for.
# 1. perulangan hingga 100 dengan output 1 2 3 4 5 6 7 8 9 (your name) (your name) (your name)
program yang dibuat ini adalah program yang memuat perulangan hingga 100.

        String name = "Lidya Feronica";

        String NPM = "G1A023009";

Di bagian kode tersebut dua variabel name dan npm di deklarasikan dan diinisialisasikan.

        System.out.println("nama :" + name);
        System.out.println("NPM :" + NPM);
        System.out.println("******************");
        
kode ini mencetak variabel nama dan NPM

 for (int i = 0 ; i<=100; i++){
 
            if (i>=10 ){
            
             System.out.println(name);
             
            }
            
            else {
            
                System.out.println(i);
                
            }
            
        }
bagian ini memiliki perulangan for dari 0 hingga 100,disini terdapat kondisi if alse di dalam loop.jika nilai i>=10 maka program akan mencetak nama yaitu lidya feronica.

saat menjalankan program ini maka ia akan mencetak nama lidya feronica sebanyak 91 kali(dari 10 hingga 100).setiap nilai yang >=10 akan meng outputkan nama(lidya feronica) sedangkan jika i<=10 maka yang akan keluar adalah angka 0,1,2,3,4,5,6,7,8,9.


# 2.program dengan menerapkan if else dalam perulangan while
        String nama = "Lidya Feronica";
        String alamat = "Bungamas";

        int counter = 0;
pada kode bagian ini hampir sama seperti nomor 1 tetapi dsisini terdapat int counter yang dideklarasikan dan diinisialisasikan dengan nilai 0.

        int counter = 0;
        while (counter <2 ){
            if (counter == 0){
                System.out.println("nama: " + nama);
            }else {
                System.out.println("alamat: " + alamat);
            }
            counter++;
        }
    }

 program ini menggunakan perulangan while untuk melakukan iterasi nilai dari counter <2(kurang dari dua).Jika counter =0 maka akan muncul nama(Lidya Feronica) dan sebaliknya jika counter tidak sama dengan 0 maka output yang akan muncul yaitu alamat.

      nama: Lidya Feronica
      alamat: Bungamas
jika kode-kode tersebut di run atau program tersebut di jalankan maka akan muncul seperti yang berada di atas.

counter=0 akan mencetak nama:Lidya Feronica

counter=1 akan mencetak alamat:Bungamas

# 3. program zodiak menggunakan fitur input dengan hasil menampilkan zodiak sesuai dengan tanggal dan bulan lahir yang diinputkan
        import java.util.Scanner;
kode di atas berguna untuk membaca input dari pengguna

        Scanner input = new Scanner(System.in);
        int tanggal, bulan;

        System.out.print("Masukkan tanggal lahir (1-31): ");
        tanggal = input.nextInt();

        System.out.print("Masukkan bulan lahir (1-12): ");
        bulan = input.nextInt();
kode tersebut mendeklarasikan dua variabel int yaitu tanggal dan bulan.menggunakan scanner yang berguna untuk mengiinputkan tanggal dan bulan lahir dari pengguna.

        String zodiak = tentukanZodiak(tanggal, bulan);

program memanggil dengan tentukan zodiak dari tanggal dan bulan lahir yang akan mengoutputkan zodiak dari tanggal dan bulan lahir yang dimasukkan.
      
       public static String tentukanZodiak(int tanggal, int bulan) {

kode tersebut menggunakan parameter yaitu tanggal dan bulan,dan menggunakan serangkaian if else untuk menentukan zodiak dengan ketentuan nilai-nilai yang telah dimasukkan

       System.out.println("Zodiak Anda adalah: " + zodiak);

kode ini berfungsi untuk mengoutputkan zodiak dengan tanggal dan bulan lahir yang telas dimasukkan.

        Masukkan tanggal lahir (1-31): 2
        Masukkan bulan lahir (1-12): 2
        Zodiak Anda adalah: Aquarius

hasil akhir dari program'

# 4. buatlah sebuah variabel dengan tipe data arraytampilkan sebuah nilai dengan perulangan for

    String[] names = new String[]{"Dewi", "Ucok","bambang", "Surti"};

 pada kode ini sebuah data array dengan menggunakan variabel nama yang dideklarasikan dengan beberapa nama sebagai bentuk array.


        System.out.println("nama-nama");
             for (int i = 0; i < names.length; ++i) {
              System.out.println(names[i]);
          }

menggunakan loop for atau perulangan for,dimulai dari i=0 hingga i<names.length',program untuk mencetak setiap elemen dari data array yang dimasukkan.        

        nama-nama
        Dewi
        Ucok
        bambang
        Surti

 yang ditampilkan diatas merupakan hasil dari program tersebut jika di run atau dijalankan.
