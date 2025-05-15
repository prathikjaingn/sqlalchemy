
# SQLAlchemy

![PyPI](https://img.shields.io/pypi/v/sqlalchemy)  
![Python](https://img.shields.io/pypi/pyversions/sqlalchemy)  
![Downloads](https://static.pepy.tech/badge/sqlalchemy/month)

## The Python SQL Toolkit and Object Relational Mapper

---

### Introduction

SQLAlchemy is the Python SQL toolkit and Object Relational Mapper that gives application developers the full power and flexibility of SQL. SQLAlchemy provides a full suite of well-known enterprise-level persistence patterns, designed for efficient and high-performing database access, adapted into a simple and Pythonic domain language.

#### Major SQLAlchemy features include:

- An industrial-strength ORM built on the identity map, unit of work, and data mapper patterns. These patterns allow transparent persistence of objects using a declarative configuration system. Domain models can be constructed and manipulated naturally, and changes are synchronized with the current transaction automatically.
- A relationally-oriented query system, exposing the full range of SQL’s capabilities explicitly, including joins, subqueries, correlation, and much more — in terms of the object model.
- A comprehensive and flexible system of eager loading for related collections and objects. Collections are cached within a session and can be loaded on individual access, all at once using joins, or by query per collection across the full result set.
- A Core SQL construction system and DBAPI interaction layer, completely separate from the ORM, offering:
  - A full database abstraction layer
  - SQL expression language
  - Schema metadata
  - Connection pooling
  - Type coercion
  - Custom types
- Database introspection and generation: schemas can be reflected into Python structures and re-emitted as `CREATE` statements — all within the Core.

### SQLAlchemy's Philosophy

- SQL databases behave less like object collections as size/performance scale. SQLAlchemy accommodates both relational and object-oriented design needs.
- The ORM doesn't hide the "R" — relational functionality is fully exposed.
- Developers maintain full control over design, structure, and naming in both the object and relational models.
- You won’t encounter "the ORM generated a bad query" — developers have full control over queries.
- The ORM is optional — the Core gives full SQL construction tools if the ORM is unnecessary.
- Transactions are standard: nothing persists until `.commit()` is explicitly called.
- Bound parameters are used to prevent SQL injection and promote efficient query planning.

---

### 📚 Documentation

The latest documentation is available at:  
🔗 https://www.sqlalchemy.org/docs/

---

### 💾 Installation / Requirements

Installation instructions:  
🔗 [Installation Guide](https://www.sqlalchemy.org/docs/intro.html#installation)

---

### 🛠️ Getting Help / Development / Bug Reporting

For support and community help, visit:  
🔗 [SQLAlchemy Community Guide](https://www.sqlalchemy.org/support.html)

---

### 📜 Code of Conduct

We encourage polite, thoughtful, and constructive interaction between users and developers.  
🔗 [Code of Conduct](https://www.sqlalchemy.org/codeofconduct.html)

---

### 🪪 License

SQLAlchemy is distributed under the [MIT license](https://www.opensource.org/licenses/mit-license.php).
