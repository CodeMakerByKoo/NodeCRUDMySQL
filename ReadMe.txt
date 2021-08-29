Microsoft Windows [Version 10.0.19042.1165]
(c) Microsoft Corporation. All rights reserved.

C:\Users\User>cd desktop\node

C:\Users\User\Desktop\Node>mkdir NodeCRUDMySQL

C:\Users\User\Desktop\Node>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node

29/08/2021  02:38 PM    <DIR>          .
29/08/2021  02:38 PM    <DIR>          ..
29/08/2021  02:38 PM    <DIR>          NodeCRUDMySQL
27/08/2021  09:28 PM    <DIR>          nodejs_server
29/08/2021  02:33 PM    <DIR>          Solutions
29/08/2021  12:49 PM    <DIR>          whatabyte-portal
               0 File(s)              0 bytes
               6 Dir(s)  53,259,616,256 bytes free

C:\Users\User\Desktop\Node>cd Nodecrudmysql

C:\Users\User\Desktop\Node\NodeCRUDMySQL>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node\NodeCRUDMySQL

29/08/2021  02:38 PM    <DIR>          .
29/08/2021  02:38 PM    <DIR>          ..
               0 File(s)              0 bytes
               2 Dir(s)  53,258,350,592 bytes free

C:\Users\User\Desktop\Node\NodeCRUDMySQL>type nul > db.js

C:\Users\User\Desktop\Node\NodeCRUDMySQL>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node\NodeCRUDMySQL

29/08/2021  02:39 PM    <DIR>          .
29/08/2021  02:39 PM    <DIR>          ..
29/08/2021  02:39 PM                 0 db.js
               1 File(s)              0 bytes
               2 Dir(s)  53,250,719,744 bytes free

C:\Users\User\Desktop\Node\NodeCRUDMySQL>npm install -g express-generator
npm WARN deprecated mkdirp@0.5.1: Legacy versions of mkdirp are no longer supported. Please update to mkdirp 1.x. (Note that the API surface has changed to use Promises in 1.x.)

added 10 packages, and audited 11 packages in 7s

2 low severity vulnerabilities

To address all issues, run:
  npm audit fix --force

Run `npm audit` for details.

C:\Users\User\Desktop\Node\NodeCRUDMySQL>express --view=ejs nodejs-crud

   create : nodejs-crud\
   create : nodejs-crud\public\
   create : nodejs-crud\public\javascripts\
   create : nodejs-crud\public\images\
   create : nodejs-crud\public\stylesheets\
   create : nodejs-crud\public\stylesheets\style.css
   create : nodejs-crud\routes\
   create : nodejs-crud\routes\index.js
   create : nodejs-crud\routes\users.js
   create : nodejs-crud\views\
   create : nodejs-crud\views\error.ejs
   create : nodejs-crud\views\index.ejs
   create : nodejs-crud\app.js
   create : nodejs-crud\package.json
   create : nodejs-crud\bin\
   create : nodejs-crud\bin\www

   change directory:
     > cd nodejs-crud

   install dependencies:
     > npm install

   run the app:
     > SET DEBUG=nodejs-crud:* & npm start


C:\Users\User\Desktop\Node\NodeCRUDMySQL>cd nodejs-crud

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud

29/08/2021  02:43 PM    <DIR>          .
29/08/2021  02:43 PM    <DIR>          ..
29/08/2021  02:43 PM             1,074 app.js
29/08/2021  02:43 PM    <DIR>          bin
29/08/2021  02:43 PM               297 package.json
29/08/2021  02:43 PM    <DIR>          public
29/08/2021  02:43 PM    <DIR>          routes
29/08/2021  02:43 PM    <DIR>          views
               2 File(s)          1,371 bytes
               6 Dir(s)  53,240,913,920 bytes free

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>npm install express-flash --save

added 56 packages, and audited 57 packages in 10s

found 0 vulnerabilities

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>npm install express-session --save

added 6 packages, and audited 63 packages in 5s

1 package is looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>npm install method-override --save

added 2 packages, and audited 65 packages in 3s

1 package is looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>npm install mysql --save

added 9 packages, and audited 74 packages in 7s

1 package is looking for funding
  run `npm fund` for details

found 0 vulnerabilities

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>mkdir lib

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>dir
 Volume in drive C has no label.
 Volume Serial Number is 4E06-2DC1

 Directory of C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud

29/08/2021  03:03 PM    <DIR>          .
29/08/2021  03:03 PM    <DIR>          ..
29/08/2021  02:43 PM             1,074 app.js
29/08/2021  02:43 PM    <DIR>          bin
29/08/2021  03:03 PM    <DIR>          lib
29/08/2021  02:47 PM    <DIR>          node_modules
29/08/2021  02:47 PM            46,340 package-lock.json
29/08/2021  02:47 PM               419 package.json
29/08/2021  02:43 PM    <DIR>          public
29/08/2021  02:45 PM                 0 ReadMe.txt
29/08/2021  02:43 PM    <DIR>          routes
29/08/2021  02:43 PM    <DIR>          views
               4 File(s)         47,833 bytes
               8 Dir(s)  53,641,732,096 bytes free

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>type nul > db.js

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>type nul > routes\books.js

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>type nul > views\books\index.ejs

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>type nul > views\books\add.ejs

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>type nul > views\books\edit.ejs

C:\Users\User\Desktop\Node\NodeCRUDMySQL\nodejs-crud>npm start

> nodejs-crud@0.0.0 start
> node ./bin/www

Connected..!
GET / 200 34.617 ms - 207
GET /stylesheets/style.css 200 12.542 ms - 111
GET /books 200 13.086 ms - 1003
GET /books/add 200 4.871 ms - 1155
POST /books/add 200 44.184 ms - 1298
POST /books/add 302 19.160 ms - 56
GET /books 200 5.826 ms - 1914
