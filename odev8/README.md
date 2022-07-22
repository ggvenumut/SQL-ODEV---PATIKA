# [PATIKA-SQL](https://www.patika.dev) - ODEV8

## ODEV

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

### COZUM

- 1.  ```
        CREATE TABLE employee ( id INTEGER , name VARCHAR(50), email VARCHAR(100), birthday DATE );
      ```

---

- 2.  ```
        insert into employee (id, name, email, birthday) values (1, 'bmcmeekin0', 'dkelshaw0@bandcamp.com', '8/10/2021');
        insert into employee (id, name, email, birthday) values (2, 'oroussell1', 'asparshutt1@cbc.ca', '7/10/2021');
        insert into employee (id, name, email, birthday) values (3, 'astuehmeier2', 'mgoffe2@ft.com', '18/11/2021');
        insert into employee (id, name, email, birthday) values (4, 'skuzma3', 'cmeeking3@globo.com', '17/7/2022');
        insert into employee (id, name, email, birthday) values (5, 'traybould4', 'gspours4@amazonaws.com', '11/3/2022');
        insert into employee (id, name, email, birthday) values (6, 'hgasgarth5', 'hderrington5@hao123.com', '22/4/2022');
        insert into employee (id, name, email, birthday) values (7, 'jcampany6', 'dfetherstone6@nymag.com', '18/7/2022');
        insert into employee (id, name, email, birthday) values (8, 'adecarolis7', 'nmoles7@google.es', '21/9/2021');
        insert into employee (id, name, email, birthday) values (9, 'tmagnus8', 'fingliss8@icio.us', '11/8/2021');
        insert into employee (id, name, email, birthday) values (10, 'sgrigoire9', 'elackmann9@uol.com.br', '29/9/2021');
        insert into employee (id, name, email, birthday) values (11, 'bbelisona', 'mrebeiroa@dailymotion.com', '6/8/2021');
        insert into employee (id, name, email, birthday) values (12, 'gturnorb', 'dstanesbyb@simplemachines.org', '9/11/2021');
        insert into employee (id, name, email, birthday) values (13, 'wcoulstonc', 'trawdalesc@blogtalkradio.com', '7/12/2021');
        insert into employee (id, name, email, birthday) values (14, 'fchamand', 'mgaishd@netlog.com', '30/4/2022');
        insert into employee (id, name, email, birthday) values (15, 'aandrine', 'phamale@mozilla.org', '27/7/2021');
        insert into employee (id, name, email, birthday) values (16, 'jpembridgef', 'jcoppledikef@ca.gov', '20/3/2022');
        insert into employee (id, name, email, birthday) values (17, 'chayleyg', 'akerfutg@cisco.com', '29/5/2022');
        insert into employee (id, name, email, birthday) values (18, 'cmerigoth', 'wpatroneh@shutterfly.com', '9/7/2022');
        insert into employee (id, name, email, birthday) values (19, 'qbricknalli', 'tcaproni@webnode.com', '12/5/2022');
        insert into employee (id, name, email, birthday) values (20, 'bpreecej', 'wdeandreisj@canalblog.com', '9/8/2021');
        insert into employee (id, name, email, birthday) values (21, 'bgrigollik', 'rpenwrightk@blog.com', '1/2/2022');
        insert into employee (id, name, email, birthday) values (22, 'ltroodl', 'rongel@mapy.cz', '24/4/2022');
        insert into employee (id, name, email, birthday) values (23, 'jgraybealm', 'spetruschm@woothemes.com', '4/10/2021');
        insert into employee (id, name, email, birthday) values (24, 'semmottn', 'mquinn@globo.com', '13/7/2022');
        insert into employee (id, name, email, birthday) values (25, 'mroddamo', 'jitschakovo@marketwatch.com', '15/12/2021');
        insert into employee (id, name, email, birthday) values (26, 'ccalytonp', 'mfowliep@wiley.com', '18/1/2022');
        insert into employee (id, name, email, birthday) values (27, 'fpengillyq', 'pudenq@geocities.com', '6/12/2021');
        insert into employee (id, name, email, birthday) values (28, 'hbeloner', 'mkenwrickr@networksolutions.com', '12/2/2022');
        insert into employee (id, name, email, birthday) values (29, 'jscardafields', 'hibesons@biglobe.ne.jp', '12/7/2022');
        insert into employee (id, name, email, birthday) values (30, 'adecourseyt', 'mbramsent@auda.org.au', '29/3/2022');
        insert into employee (id, name, email, birthday) values (31, 'hzupou', 'mwadhamu@mapquest.com', '20/6/2022');
        insert into employee (id, name, email, birthday) values (32, 'ocotillardv', 'baizkovitchv@blog.com', '17/6/2022');
        insert into employee (id, name, email, birthday) values (33, 'kguardw', 'nwoolmerw@europa.eu', '28/10/2021');
        insert into employee (id, name, email, birthday) values (34, 'tsollittx', 'mbertotx@ftc.gov', '15/10/2021');
        insert into employee (id, name, email, birthday) values (35, 'xmcclancyy', 'mhaggithy@amazon.com', '10/4/2022');
        insert into employee (id, name, email, birthday) values (36, 'ashadfourthz', 'mlinkletz@samsung.com', '6/5/2022');
        insert into employee (id, name, email, birthday) values (37, 'ksuarez10', 'rbrownhall10@illinois.edu', '23/9/2021');
        insert into employee (id, name, email, birthday) values (38, 'nimlock11', 'hbowler11@sohu.com', '17/10/2021');
        insert into employee (id, name, email, birthday) values (39, 'fkabsch12', 'fvousden12@mac.com', '24/8/2021');
        insert into employee (id, name, email, birthday) values (40, 'koscallan13', 'grose13@intel.com', '22/2/2022');
        insert into employee (id, name, email, birthday) values (41, 'psillito14', 'wsimonelli14@posterous.com', '23/9/2021');
        insert into employee (id, name, email, birthday) values (42, 'ajelphs15', 'mmandre15@wiley.com', '31/7/2021');
        insert into employee (id, name, email, birthday) values (43, 'bcoldtart16', 'awhiskerd16@umn.edu', '3/1/2022');
        insert into employee (id, name, email, birthday) values (44, 'kkitchin17', 'mbringloe17@slideshare.net', '11/5/2022');
        insert into employee (id, name, email, birthday) values (45, 'nbricket18', 'ecometto18@admin.ch', '6/1/2022');
        insert into employee (id, name, email, birthday) values (46, 'lhayford19', 'pkyngdon19@accuweather.com', '9/5/2022');
        insert into employee (id, name, email, birthday) values (47, 'agleder1a', 'aluckings1a@census.gov', '17/9/2021');
        insert into employee (id, name, email, birthday) values (48, 'rmattiassi1b', 'lgaukroger1b@noaa.gov', '18/11/2021');
        insert into employee (id, name, email, birthday) values (49, 'vyousef1c', 'rspurdon1c@europa.eu', '30/7/2021');
        insert into employee (id, name, email, birthday) values (50, 'mnellis1d', 'gbrach1d@china.com.cn', '7/3/2022');
      ```

  ```

  ```

---

- 3.  ```
        UPDATE employee
        SET name = 'XXXX YYYY',
        birthday = '2000-05-12',
        email = 'xxxx@yyyy.com'
        WHERE id = 13;

        UPDATE employee
        SET name = 'a SET'
        WHERE name LIKE 'a%';

        UPDATE employee
        SET name = 'm SET'
        WHERE name LIKE 'm%';

        UPDATE employee
        SET name = 'v SET'
        WHERE name LIKE 'v%';

      ```

---

- 4. ```
       DELETE FROM employee
       WHERE name LIKE 'V%';

       DELETE FROM employee
       WHERE id > 30;

       DELETE FROM employee
       WHERE name = 'a SET';

       DELETE from employee
       WHERE email = 'xxxx@yyyy.com';

       DELETE FROM employee
       WHERE id = 10;
     ```

  ```

  ```
