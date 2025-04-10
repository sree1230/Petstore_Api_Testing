 PetStore API – Postman Collection (XML Model)

This repository contains a Postman collection for testing the [Swagger Petstore API](https://petstore.swagger.io) using **XML payloads**. It covers the full lifecycle of a pet: create, retrieve, update, and delete.

---

## 📦 Collection Name
**`PetStore_XML_Model.postman_collection.json`**

---

## 🧪 Included Requests

| Request Name           | Method | Description                        |
|------------------------|--------|------------------------------------|
| 🐶 Add a New Pet        | POST   | Adds a new pet using XML body      |
| 🔍 Find Pet by ID       | GET    | Retrieves pet details by ID        |
| ✏️ Update Pet Name      | PUT    | Updates pet information via XML    |
| 🗑️ Delete Pet by ID     | DELETE | Deletes the pet using `{{petId}}`  |

---

## 🔧 How to Use in Postman

1. Open **Postman**.
2. Click **Import** → Select `PetStore_XML_Model.postman_collection.json`.
3. Send requests in order:
   - **Add a New Pet**: Stores `petId` in collection variables.
   - **Find, Update, Delete**: Reuse the same `petId`.
4. Make sure your headers are correct for XML:
   - `Content-Type: application/xml`
   - `Accept: application/json`

---

## 📝 Notes

- The XML format used follows Swagger Petstore's schema.
- `petId` is stored as a collection variable automatically after creating a pet.
- This collection is useful for practicing API testing, automation, and Postman workflows using XML.

---

## 📚 Related

- [Swagger Petstore API Docs](https://petstore.swagger.io)
- [Postman Docs](https://learning.postman.com/docs/)

---

## 🛠️ Author

Made for testing and demo purposes. Feel free to fork, extend, or contribute!
