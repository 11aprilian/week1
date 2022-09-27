# **Writing and Presentation Test Week 1**

## **Unix Commad Line**

###  **Command Line Interface (CLI)**
  <div align="justify">CLI atau Command Line Interface adalah sebuah program yang memungkinkan user mengetik perintah atau command yang akan mmemerintahkan perangkat komputer untuk melakukan suatu tugas tertentu.

  ### **Shell**
  <div align="justify">Shell adalah user interface pengelola CLI dan berperan sebagai perantara yang menghubungkan user dan sistem operasi. Maka dari itu user memerlukan yang namanya shell.
 
  ### **Terminal**
  <div align="justify">User dan komputer dihubungkan dengan namanya terminal, yaitu tempat/aplikasi dimana user dapat mengetikan atau memberikan suatu perintah. Disinilah tempat dimana shell akan berperan.

  ### **File System Structure**

  <div align="justify">Struktur dimana mengatur cara bagaimana data disimpan dalam sistem. Contoh dalam Sistem Operasi Windows struktur file yang disimpan menggunakan struktur yang bentuknya mirip sebuah pohon seperti gambar dibawah.

    ## Berikut adalah tampilan dari Command Line Interface :


- ## Beberapa perintah navigation files dan directory

  - pwd (print working directory), untuk melihat current working directory 
  - ls (list), untuk melihat isi file di dalam directory
  - ls - la ,untuk melihat files yang di hidden 
  - cd (change directory), untuk masuk ke directory tertentu
  - cd .. ,merupakan command untuk berpindah directory
  - mkdir ,digunakan untuk membuat directory baru
  - dir (directory), untuk melihat directory
  - touch, untuk membuat file directory
  - ni, digunakan untuk membuat file di windows
  - cp (copy), untuk menyalin file directory
  - cp -r ,digunakan untuk menyalin directory 
  - mv (move), untuk memindahkan file directory
  - rm (remove), untuk menghapus file directory

  ### Perbedaan  Git dan GitHub
- **Git**
  <div align="justify">Git adalah sebuah software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project.

- **GitHub**
  <div align="justify">GitHub merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git).

  <hr>
  <br>

## **HTML**

- ### **Penejelasan HTML**
  <div align="justify">HTML adalah singkatan dari Hypertext Markup Language. HTML adalah bahasa komputer yang digunakan untuk membuat kerangka atau struktur untuk Web pages (halaman website) di internet.
  Fungsi HTML adalah sebagai 'kerangka' dari sebuah website.
  <br>
  Catatan : 
  
  > HTML bukanlah sebuah bahasa pemrograman, artinya HTML tidak bisa dinamis mengolah data.

  - ### **HTML Structure**
```html
  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <p>Hello World</p>
</body>
</html>
  ```

-  ### HTML Element
    <div align="justify">terdiri atas opening tag, content, closing tag
    <br>
        - opening tag :
    
      ```html
      <p>
      ```
    - content : Hello world
    - closing tag :

      ```html
      </p>
      ```
      - ### HTML Atribut
  Property dari subah element HTML. Contohnya id, class, name.

- ### Single Tag atau Singular Tag 

  ```html
  <br> <!-- Membuat baris baru -->
  <hr> <!-- Membuat Garis Horizontal -->
  <img src=""/> <!-- Untuk Menmapilkan gambar-->
  ```

- ### Paired Tag atau Double Tag

  ```html
  <h1></h1> 
  <p></p>
  ```

- ### HTML Command
  <div align="justify">Digunakan untuk memberikan komentar atau keterangan pada suatu line code

  ```html
  <!-- Komentar -->
  ```

  <hr>

## **CSS**
- ### Penjelasan CSS
  <div align="justify">CSS (Cascading Style Sheets)adalah bahasa yang digunakan untuk mendesain halaman website.
  Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.

  - ### Struktur CSS
  ```css
  .elementshtml{
    property : value
  }
  ```
- ### CSS Comment
  <div align="justify">Dengan menggunakan CSS Comment, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan.

  ```css
  /* Komentar */
  ```

   ## 3 Cara Menggunakan CSS
  - **Inline Styles**
    <div align="justify">Inline styles adalah kita menambahkan CSS pada attribute element HTML

    ```html
    <P style="color : blue; font-size : 40px">Hello world</p>
    ```

  - **Internal CSS**
    <div align="justify">Menambahkan kode Style pada html di bagian head. contohnya seperti berikut :

    ```html
    <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
          <style>
              h1 {
                  color : blue;
                  font-size: 40px;
              }
          </style>
      </head>
      <body>
          <h1>Hello World</h1>
      </body>
      </html>
    ```

  - **Eksternal CSS**
    <div align="justify">Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML.
    <br>

    - Pada file index.html
      ```html
      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
          <link rel="stylesheet" href="style.css">
      </head>
      <body>
          <h1>Hello World</h1>
      </body>
      </html>
      ```

    - Pada file style.css
      ```css
      h1 {
        color : blue;
        font-size : 40px;
      }
      ```



