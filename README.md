<<<<<<< HEAD
<<<<<<< HEAD
# 1-Contacts-CRUD-Project-React-JS-
This is a React-based Contact Management Application designed to manage a list of contacts effectively
=======
# Vite

- Klasik react uygulamalarına göre daha güncel olan bu metot sayesinde daha hızlı şekilde uygulama oluşturup ayağa kaldırırız.

# Vite ile oluşturlan react uygulaması && Klasik react uygulaması

- Vite ile oluşturulan bir proje klasik react uygulamasına göre kullanmadığımız bağımlılıkları içermediğinden çok daha hızlı şekilde oluşturulur.Bunun yanında klasik react uygulmasına göre daha performanslı çalışır.Build işlemi de klasik uygulamaya göre çok daha hızlıdır.

- HMR: Vite projesinin değişiklikleri tarayıcaya çok daha hızlı bir şekilde aktarmasını sağlar.

# JSON SERVER

- Bir proje temel olarak iki kısımından oluşur.

- i-) Frontend
- ii-) Backend

- Proje geliştirken api a istek atar verileri alır bu verilerle arayüz oluştururuz.Fakat elimizde bir api'ın bulunmadığı yada api'ın hazırlanmasının uzun süreceği durumlarda sanki bir api a sahibiz gibi geliştirme yapmamıza olanak sağlayan bir kütüphane mevcuttur.`json-server` kütüphanesi sayesinde fake bir api elde ederiz.

- Bu fake api oluşturulurken önce `npm install json-server` ile kütüphane projemize indirilir.
- Sonrasında proje klasöründe `db.json` dosyası oluşturulur.Burada önemli kısım bu dosyanın src klasörüyle aynı dizinde olmasıdır.
- Bu `db.json` dosyası içerisinde veriler oluşturulur.
- `npx son-server db.json` komutuyla ilgili fake api ayağa kaldırılır

# HTTP METOTLARI

- Server ve client arasında arasında veri alışverişi sağlamak için kullanılır.

- 1. GET:
- Serverdan verileri almak için kullanılır.

- 2. POST:
- Server a veri göndermek için kullanılır.Gönderilecek veriler isteğin body'si içerisine eklenir.

- 3. PUT:
- Serverdaki bir veriyi güncellemek için kullanılır.Bu metot veriyi tamamen güncellemek için kullanılır.

- 4. PATCH:
- Serverdaki veriyi güncellemek için kullanılır.Bu metot verinin sadece bir kısmını güncellemek için kullanılır.

- 5. DELETE:
- Serverdaki veriyi silmek için kullanılır.

# Axios:

- Güncel projelerin büyük bir çoğunda kullanılan axios kütüphanesi bizim için api'a istek attığımızda büyük kolaylıklar sağlar.

- Gelen isteğin jsondan js nesnesine çevirilmesi işlemini axios yapar
- Gönderilecek isteğin bodysinde yer alacak verinin json a çevirilmesi işlemini yine axios yapar
- Parametreleri işler
- İsteklere zamana bağlı kontrol özelliği ekleme yeteneği sağlar
- Uzun uzun url yazmak yerine bu urlleri özelleştirme yeteneği sunar

  1.28
>>>>>>> d0f6da9 (Initial commit)
=======

## Contacts-CRUD-Project-React-JS 📇
This is a React-based Contact Management Application designed to manage a list of contacts effectively. The app allows users to perform CRUD (Create, Read, Update, Delete) operations on their contacts while leveraging a modern React workflow.
## Preview
![Contact_Crud](https://github.com/user-attachments/assets/0ff82c75-2e9e-4c92-b9f6-0cbff2bcea0d)



🚀 Features
Add New Contacts: Easily add new entries to your contact list.
Search Functionality: Quickly find contacts with the search bar.
Update Contacts: Edit existing contact information seamlessly.
Delete Contacts: Remove unwanted contacts with a single click.
Dynamic UI: A responsive and interactive user interface.

🛠️ Built With
React: Frontend library for building the user interface.
Axios: To handle API requests.
JSON Server: Mock backend server for managing the contact database.
React Icons: For clean and modern icons in the app.

📝 Usage
Add a new contact by clicking the "Add Contact" button.
Edit a contact by clicking the edit icon next to it.
Delete a contact by clicking the delete icon.
Use the search bar to find specific contacts.
🎉 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue to suggest improvements.

>>>>>>> 7ae121696471019882591f107bae4b71b22ed0f9
