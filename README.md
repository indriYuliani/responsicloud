BELAJAR MEMBUAT IMAGE DARI DOCKER FILE
1. install docker
2. download docker file,letakan pada pada direktori tertentu.
    contoh : C;\User\Student\dockerFile
3. Jalankan  Docker QuickStart Terminal
4. Masuk kedalam direktori tempat mendownload: C:\User\Student\dockerFile
5. Isi dalam docker File tersebut diganti sesuai kebutuhan

 6. Buka kembali docker quickStart terminal untuk membuka direktori tersebut ;
   cd dockerfile
  7. membuat Image:
    a. build image :
       docker build -t indri/dcf . 
   8. Jalankan dengan 
     docker run -it indri/dcf 
