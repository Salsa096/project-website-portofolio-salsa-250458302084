Tailwind CSS setup tutorial via CDN:
Pertama, buat file baru bernama index.html dan tambahkan struktur dasar HTML seperti berikut
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind CDN Setup</title>
  </head>
  <body>
  </body>
</html>


Masukkan link CDN Tailwind di dalam tag <head> untuk memuat framework-nya:
<script src="https://cdn.tailwindcss.com"></script>


lalu cara ketiga tambahkan file yang di bawah ini
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tailwind CDN Setup</title>
    <script src="https://cdn.tailwindcss.com"></script>
  </head>
  <body>
    <h1 class="text-3xl font-bold underline text-blue-600 text-center mt-10">
      Hello Tailwind via CDN!
    </h1>
  </body>
</html>
