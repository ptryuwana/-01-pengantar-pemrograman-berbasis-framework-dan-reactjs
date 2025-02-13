This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.


## Laporan Praktikum

|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  2241720089 |
| Nama |  Putra Nindya Yuwana |
| Kelas | TI - 3C |


### Praktikum 1: Menyiapkan Lingkungan Pengembangan

1. Download dan Install Git
![Screenshot](assets-report\p1-download-git.png)
2. Download dan Install VSCode
![Screenshot](assets-report\p1-download-vscode.png)
3. Download dan Install NodeJS
![Screenshot](assets-report\p1-download-nodejs.png)

#### Pertanyaan:
1.	Jelaskan kegunaan masing-masing dari Git, VS Code dan NodeJS yang telah Anda install pada sesi praktikum ini!
2.	Buktikan dengan screenshoot yang menunjukkan bahwa masing-masing tools tersebut telah berhasil terinstall di perangkat Anda!
#### Jawaban:
1.	Git adalah sistem kontrol versi (Version Control System) yang digunakan untuk mengelola perubahan kode sumber dalam pengembangan perangkat lunak. VS Code adalah editor kode sumber yang ringan namun memiliki banyak fitur, seperti debugging, syntax highlighting, IntelliSense (auto-complete), serta integrasi dengan terminal dan Git. Node.js adalah runtime JavaScript yang memungkinkan eksekusi kode JavaScript di luar browser. 
2.	Berikut screenshoot bukti terinstall
a.	Git
![Screenshot](assets-report\p1-git.png)
b.	VSCode
![Screenshot](assets-report\p1-vscode.png)
c.	NodeJS 
![Screenshot](assets-report\p1-nodejs.png)

### Praktikum 2: Membuat Proyek Pertama React Menggunakan Next.js

1. Membuat folder proyek baru dengan nama belajar-react. Melalui konsol/command prompt/CMD masuk ke dalam folder tersebut dan jalankan perintah ini: npx create-next-app	 
![Screenshot](assets-report\p2-no1.png)
2. Buat proyek baru dengan nama hello-world seperti di bawah ini. Nama proyek ini perlu dimasukkan pertama kali melalui konsol.
![Screenshot](assets-report\p2-no2.png)	 
3. Buka folder proyek hello-world menggunakan VS Code. Masuk ke dalam folder proyek hello world dengan perintah: cd hello-world. Kemudian setelah masuk ke folder hello-world, masukkan perintah: code .. Maka VS Code akan membuka project react Anda yang telah dibuat bernama hello-world.	 
![Screenshot](assets-report\p2-no3a.png)
![Screenshot](assets-report\p2-no3b.png)
4. Running proyek hello-world dengan memasukkan perintah di bawah ini melalui konsol atau terminal di dalam VS Code. npm run dev. Tunggu proses kompilasi hingga selesai. Lalu Anda dapat membuka alamat localhost di browser: http://localhost:3000/
![Screenshot](assets-report\p2-no4.png)

#### Pertanyaan:
1.	Pada Langkah ke-2, setelah membuat proyek baru menggunakan Next.js, terdapat beberapa istilah yang muncul. Jelaskan istilah tersebut, TypeScript, ESLint, Tailwind CSS, App Router, Import alias, dan Turbopack!
2.	Apa saja kegunaan folder dan file yang ada pada struktur proyek React yang tampil pada gambar pada tahap percobaan ke-3!
3.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!
#### Jawaban:
1.	Berikut penjelasannya:
a.	TypeScript adalah superset dari JavaScript yang menambahkan fitur static typing, memungkinkan deteksi kesalahan lebih awal dengan sistem tipe seperti string dan number.
b.	ESLint adalah alat analisis kode yang memastikan konsistensi dan kualitas kode JavaScript dengan mencegah kesalahan umum.
c.	Tailwind CSS adalah framework CSS utility-first yang memungkinkan styling cepat menggunakan class utility langsung di HTML.
d.	App Router adalah sistem routing terbaru di Next.js yang menggantikan Pages Router.
e.	Import Alias memungkinkan penggunaan path pendek untuk menghindari import yang panjang, misalnya @/components/ui/Button dibandingkan dengan ../../components/ui/Button.
f.	Turbopack adalah bundler generasi baru yang lebih cepat dibandingkan Webpack, dikembangkan dengan Rust untuk meningkatkan performa.
2.	Berikut penjelasannya:
a.	.next/ - Folder yang dihasilkan secara otomatis oleh Next.js ketika proyek dijalankan atau dibangun. 
b.	node_modules/ - Folder ini berisi semua dependencies (dependensi) yang diinstal melalui npm atau yarn. 
c.	public/ - Berisi aset statis seperti index.html, favicon, atau gambar yang tidak diolah oleh Webpack/Vite.
d.	src/ -  Folder utama untuk kode sumber aplikasi React. Semua komponen, fungsi, dan logika aplikasi diletakkan di sini.
e.	.gitignore - File ini menentukan file dan folder yang harus diabaikan oleh Git, seperti node_modules dan file sementara lainnya.
f.	package.json - Berisi informasi proyek seperti nama, versi, dependensi yang digunakan, serta script yang dapat dijalankan (misalnya npm start atau npm run dev).
g.	package-lock.json - File ini secara otomatis dibuat oleh npm untuk mencatat versi pasti dari dependensi yang diinstal, memastikan konsistensi saat instalasi ulang.
h.	next.config.ts - File konfigurasi utama Next.js dalam format TypeScript.
i.	postcss.config.mjs - File konfigurasi untuk PostCSS, yang merupakan alat pemrosesan CSS modern.
j.	tailwind.config.ts - Konfigurasi utama untuk Tailwind CSS dalam format TypeScript.
k.	tsconfig.json - File konfigurasi untuk TypeScript dalam proyek Next.js.
l.	eslint.config.mjs - File ini digunakan untuk mengatur ESLint, yaitu alat yang membantu memastikan kualitas kode dengan mendeteksi error dan gaya penulisan yang tidak sesuai standar.
m.	next-env.d.ts - File deklarasi tipe untuk memastikan bahwa TypeScript mengenali fitur bawaan Next.js dengan benar.
3.	Screenshoot sudah dilampirkan pada proses praktikum.

### Praktikum 3: Menambahkan Komponen React (Button)

1. Di dalam folder proyek yang telah dibuka di VS Code, buka file page.tsx
![Screenshot](assets-report\p3-no1.png)	 
2. Tambahkan fungsi MyButton yang mengembalikan markup komponen button yang akan ditambahkan ke dalam webpage
![Screenshot](assets-report\p3-no2.png)	 
3. Tambahkan komponen button tersebut di samping button Read Our Docs. Perhatikan bahwa komponen MyButton dimulai dengan huruf kapital. Dengan cara itulah Anda mengetahui bahwa itu adalah sebuah komponen React. Nama komponen React harus selalu dimulai dengan huruf kapital, sedangkan tag HTML harus menggunakan huruf kecil. Kata kunci export default menentukan komponen utama di dalam berkas (file).	
![Screenshot](assets-report\p3-no3.png)	 
4. Simpan perubahan dan coba lihat perubahan melalui web browser!	 
![Screenshot](assets-report\p3-no4.png)	 

#### Pertanyaan:
1.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!
#### Jawaban:
1.	Screenshoot sudah dilampirkan pada proses praktikum.

### Praktikum 4: Menulis Markup dengan JSX

1. Tambahkan kode JSX ke dalam file page.tsx.	 
![Screenshot](assets-report\p4-no1.png)	 
2. Tambahkan komponen MyProfile setelah kompnen MyButton.	 
![Screenshot](assets-report\p4-no2.png)
3. Simpan dan amati perubahan di halaman web yang dihasilkan!	 
![Screenshot](assets-report\p4-no3.png)

#### Pertanyaan:
1.	Untuk apakah kegunaan sintaks user.imageUrl?
2.	Buktikan dengan screenshoot yang menunjukkan bahwa tahapan percobaan di atas telah berhasil Anda lakukan!
#### Jawaban:
1.	Sintaks user.imgUrl digunakan untuk mengambil nilai properti imgUrl dari objek user yang telah didefinisikan. Properti ini berisi URL gambar profil yang akan ditampilkan dalam elemen <img>.
2.	Screenshoot sudah dilampirkan pada proses praktikum.
