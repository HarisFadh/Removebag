# Removebag
jadi dikesempatan kali ini saya mendapatkan tugas untuk melakukan pengolahan citra digital menghapus background pada sebuah objek
pertama saya menunjukkan objek asli yaitu tangan dan juga detail yang ada pada HP saya terhadap photo tersebut
selanjutnya yaitu melakukan penghapusan background pada objek 
disini saya menggunakan library rembg yaitu remove yang dimana akan menghapus latar pada objek
sebelumnya pastikan untuk sidah menginstall library tersebut dengan "pip install rembg"
masukkan gambar yg ingin di hilangkan latarnya pada "input_path"
dan kita "output_path" sebagai hasil yang akan dikeluarkan
"input = Image.open(input_path)" untuk mendeklarasikan si gambar tersebut kedalam input yang nanti akan diproses pada
"output = remove(input)" nah input disini akan diproses untuk dihilangkan latar belakangnya dengan perintah remove
plt.imshow(output) untuk menampilkan hasil dari si output tersebut
output.save(output_path) = untuk menyimpan hasil yang didapatkan kedalam devie kita

Background Subtraction
Background subtraction atau nama lainnya adalah foreground detection
merupakan salah satu teknik pada pengolahan citra dan computer vision.
Background subtraction biasanya digunakan untuk melakukan pendeteksian
terhadap objek seperti manusia, kendaraan, tulisan, ataupun bagian dari manusia
itu sendiri. Secara umum metode ini bekerja dengan memisahkan objek yang akan
dideteksi (foreground) dengan latar belakang (background).

teori inilah yang saya gunakan untuk menghilangkan latar pada suatu objek.

reference
https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwiknsHjmPX_AhXgRWwGHV3SBrIQFnoECBkQAQ&url=http%3A%2F%2Frepository.uin-suska.ac.id%2F16729%2F7%2F7.%2520BAB%2520II_2018435TIF.pdf&usg=AOvVaw18PRGLnTcJbWxiv-77WAcu&opi=89978449
