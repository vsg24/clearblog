# CLEARblog

### **NOTE:** CLEARBlog is no longer maintained.
<br>
A simple and beautiful blogging app powered by ASP.NET MVC5, EF6, MSSQL, Bootstrap 3.x, jQuery 2.x and other industry level tools and standards.

Key features of CLEARblog:

  - 100% Free and Open Source
  - Availabe in Persian and English
  - **Very beautiful management dashboard**
  - Powerful post editor, using TinyMCE 4.X and AJAX
  - Tagging system
  - Simple built-in commenting
  - Custom pages
  - Very easy to use and maintain

Requirements:

  - Windows host with IIS8+ 
  - .NET Framework 4.6.x
  - SQLServer 2008+
  - Browser with Javascript enabled

---

### Installation

CLEARBlog on GitHub comes with source code. In order to get a "Release Build" from source, you need Microsoft Visual Studio 2015 (Any edition should work). Compile it using "Publish" option and select "Release" as compile mode. Then copy all files in the desired location in your host.

CLEARBlog uses a "DB First" approach so you also need to create a database and import the `.sql` file in that database.

Finally you need to edit the Web.config file. You need to replace the connection string with the one for your database.

You can now login with the default user at `/admin`:

Default User Login Info:

Email:

    admin@example.com

Password:

    admin

**You MUST change default user values ASAP.**

***Recomended:*** There are a couple of options that can be customized. Including the language, blog title, number of posts in each page, blog URL (Should end with slash) and more.... They are available at the end of the Web.config file.

---

### Note

If you don't want to build CLEARBlog yourself and prefer an already compiled version of CLEARBlog, you may download it from [here](https://jumpshare.com/b/Mctvwjdg0GPSplbtjBQK). Always download the latest versions.

---

License
----

GNU GPL v3.0

