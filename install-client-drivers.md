---
title: Install Client Drivers
toc: false
---

CockroachDB supports the PostgreSQL wire protocol, so you can use any available PostgreSQL client drivers. We’ve tested and can recommend the following drivers. 

- For code samples using these drivers, see [Build a Test App](build-a-test-app.html).
- If you have issues with these, or want to share feedback on other drivers, please [get in touch](contribute-to-cockroachdb.html).

Language | Recommended Driver
---------|--------
Go | [pq](https://godoc.org/github.com/lib/pq)
Python | [psycopg2](http://initd.org/psycopg/)
Ruby | [pg](https://rubygems.org/gems/pg)
Java | [jdbc](https://jdbc.postgresql.org)
Node.js | [pg](https://www.npmjs.com/package/pg) 
C | [libpq](http://www.postgresql.org/docs/9.5/static/libpq.html)
C++ | [libpqxx](http://pqxx.org/development/libpqxx/)
Clojure | [java.jdbc](http://clojure-doc.org/articles/ecosystem/java_jdbc/home.html)
PHP | [php-pgsql](http://php.net/manual/en/book.pgsql.php)
Rust | [postgres](http://sfackler.github.io/rust-postgres/doc/v0.11.8/postgres/)