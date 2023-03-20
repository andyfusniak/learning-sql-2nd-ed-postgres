# learning-sql-2nd-ed-postgres

This repository contains an equivelent PostgreSQL version of the example database for the book. The book used MySQL and included `ENUM`, `DOUBLE` and `FLOAT` types that were replaced with a custom type, `DOUBLE PRECISION` and `REAL` respectively.

The insert statements used null for the primary key values. In MySQL null is accepted as the "next value" in the AUTO_INCREMENT sequence - these were replaced with PostgreSQL's `SERIAL`.

Learning SQL, Second Edition, by Alan Beaulieu. Copyright 2009 O'Reilly Media, Inc. 978-0-596-52083-0. See the book for Using Code Examples for fair use. If you are considering buying the book, the 3rd edition is now available from O'Reilly as of time of writing.

