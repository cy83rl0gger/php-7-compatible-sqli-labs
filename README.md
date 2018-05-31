# PHP-7 and MariaDB Compatible-sqli-labs

SQLI-LABS is a platform to learn SQLI(https://github.com/Audi-1/sqli-labs.git).

SQLI-LABS-PHP7 is based on SQLI-LABS

Following labs are covered for GET and POST scenarios:

    Error Based Injections (Union Select)
        String
        Intiger

    Error Based Injections (Double Injection Based)

    BLIND Injections: 1.Boolian Based 2.Time Based

    Update Query Injection.

    Insert Query Injections.

    Header Injections. 1.Referer based. 2.UserAgent based. 3.Cookie based.

    Second Order Injections

    Bypassing WAF
        Bypassing Blacklist filters Stripping comments Stripping OR & AND Stripping SPACES and COMMENTS Stripping UNION & SELECT
        Impidence mismatch

    Bypass addslashes()

    Bypassing mysqli_real_escape_string. (under special conditions)

    Stacked SQL injections.

    Secondary channel extraction

======================================================================================== Install Instructions:

    Unzip the contents inside the apache folder, for example under /var/www
    This will create a folder sql-labs under it. else you can use git command from within /var/www folder. /var/www folder and then use following command> git clone https://github.com/skyblueee/sqli-labs-php7.git sqli-labs
    Open the file "db-creds.inc" which is under sql-connections folder inside the sql-labs folder.
    Update your MYSQL database username and password.(default for kali are used root:)
    From your browser access the sql-labs folder to load index.html
    Click on the link setup/resetDB to create database, create tables and populate Data.
    Labs ready to be used, click on lesson number to open the lesson page.
    Enjoy the labs

==========================================================================================

Corrosponding walkthrough video tutorials and explainations can be found at: (https://github.com/Audi-1/sqli-labs.git).
