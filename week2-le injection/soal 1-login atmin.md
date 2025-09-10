dimulai dengan masuk ke halaman login terlebih dahulu di opsi "account"
<img width="1839" height="877" alt="image" src="https://github.com/user-attachments/assets/f7a93bd4-5915-4eeb-ab8f-5cef3f16e462" />

lanjutkan dengan mengikuti instruksi pada tutorial, pertama adalah mengecek apakah login page rentan terhadap SQL injection
<img width="955" height="574" alt="image" src="https://github.com/user-attachments/assets/7c3454b1-5b0d-4a7c-a0a2-296177c8d822" />

dapat dilakukan dengan memasukan tanda petik (') pada login field nya, apabila muncul "internal server error" maka itu berpotensi rentan terhadap SQL injection
<img width="571" height="309" alt="image" src="https://github.com/user-attachments/assets/58e47df5-0ddd-4aca-8f91-ce7e99ad80a5" />
<img width="849" height="117" alt="image" src="https://github.com/user-attachments/assets/747f66b5-d5f6-4a91-b439-93daf6e13d5c" />

darisini dapat ddilanjutkan dengan memasukan payload SQL berupa `'1 OR TRUE--`
<img width="528" height="290" alt="image" src="https://github.com/user-attachments/assets/3f8a1930-5794-40ef-87cd-c47110dd7cab" />

soal pun terselesaikan
<img width="1808" height="803" alt="image" src="https://github.com/user-attachments/assets/1340a5bb-1b25-4f93-8436-fbe9ac2eafb7" />


