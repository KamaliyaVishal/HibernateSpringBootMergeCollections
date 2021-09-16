# HibernateSpringBootMergeCollections

How To Merge Entity Collections

Description: This is a Spring Boot example based on the following article. Is a functional implementation of the Vlad's example. It is highly recommended to read that article.

Key points:

- remove the existing database rows that are no longer found in the incoming collection

- update the existing database rows which can be found in the incoming collection

- add the rows found in the incoming collection, which cannot be found in the current database snapshot
