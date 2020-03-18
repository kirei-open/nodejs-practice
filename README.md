# nodejs-practice

Learn to build basic NodeJS + Express App

## Description

Belajar membuat aplikasi To-Do List dengan menggunakan Nodejs + Express dan module fs (filesystem)

## Usage

Clone this repository

```
git clone https://github.com/kirei-open/nodejs-practice.git
```

## Step-by-step

1. Install Node & NPM (Node Package Manager) (search di google cara install yang latest LTS untuk windows)
2. Install library express

```bash
npm install express --save
```

3. Install library ejs (embedded javascript)

```bash
npm install ejs --save
```

4. Coding~

## Milestones

### Stage One

#### **Initial Setup**

- [x] Install NPM & Nodejs
- [x] Install Express
- [x] Install ejs
- [x] Setup Initial express app

#### **Setup API Routes**:

- [x] GET: Get All Activity (/api/todos)
- [x] GET: Get One Activity (/api/todo/:id)
- [x] POST: Create Activity (/api/todos)
- [x] PUT: Update Activity (/api/todo/:id)
- [x] DELETE: DELETE Activity (/api/todo/:id)

#### **Setup View Routes**:

- [x] View All Activity (/todos)
- [x] Get an Activity Detail (/todo/:id)
- [x] Create an Activity (/todo/new)
- [x] Edit an Activity (/todo/update/:id)

#### Notes

Setiap pembacaan/perubahan/penambahan activity, harus melihat isi file _data.json_ menggunakan module fs

### Stage Two

#### **Setup DB**

- [x] Install MySQL
- [ ] Setup User Authentication

#### **Setup Model** (raw sql)

- [x] User Model
- [x] Activity Model

#### **Setup Authentication Schema** (raw sql)

- [x] Login View & Schema
- [x] Register User
- [x] Logout Schema
- [x] (CRUD) User Profile
- [x] User Roles

#### **Form Validation**

- [ ] Validation HTML
- [ ] Validation request body (API) -> email, password -> Express validator / Joi

## Prototype

View the prototype here on [Figma](https://www.figma.com/proto/faV6p1i4bpFxo0itRb5jE1/To-Do-LIst?node-id=1%3A2&scaling=contain)
