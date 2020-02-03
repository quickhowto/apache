# Check .htaccess working or not

## Ubuntu 18, Apache 2.4

1. Make the first of line of `.htaccess` that is to be checked:
```
Is-Htaccess-Working?
```
1. Load a normal-working page that should be affected by this .htaccess file, in browser
   1. If **Internal Server Error** page comes on, then **_.htaccess is working_**
   1. If the page continues to show what it is supposed to (no error) then **.htaccess is not working**
1. Now remove the `Is-Htaccess-Working?` line from `.htaccess`

---

Tags: apache, ubuntu, htaccess
