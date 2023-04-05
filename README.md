# TECHNICAL-ASSESSMENT
BookStore WebApi


1.Change the Connection String in file appsettings.Development.json
2. Update-DataBase


Api Url To Get Result


1.write a method to return a sorted list of these by Publisher, Author (last, first), then title.
https://localhost:7204/api/BooksDetail/GetBookList

2.Write another API method to return a sorted list by Author (last, first) then title.
https://localhost:7204/api/BooksDetail/GetBookByAuthorFirst
3. Write an API method to return the total price of all books in the database.
https://localhost:7204/api/BooksDetail/GetTotalBookPrice

4.Write stored procedures for steps 1 and 2, and use them in separate API methods to return
the same results.

please check Migration Folder with 
20230405071805_GetBook_StoredProcedure.cs
20230405072913_GetBookSortedByAuthorFirst.cs

5. If you have a large list of these in memory and want to save the entire list to the database,
with only one call to the DB server.

Please Check Seed Class inside Data folder in Current Webapi Project


6. Add a property to the Book class that outputs the MLA (Modern Language Association)
style citation as a string ( https://images.app.goo.gl/YkFgbSGiPmie9GgWA ). Please add
whatever additional properties the Book class needs to generate the citation.

7.Add another property to generate a Chicago style citation (Chicago Manual of Style)
( https://images.app.goo.gl/w3SRpg2ZFsXewdAj7 ).

please check Migration Folder with
20230405094333_MLACMSPropertyAdded.cs



