# Homework-8 Questions And Solutions

1. Let's create a table named employee in your test database with column information id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100).

    ```
    CREATE TABLE employee (
    	id INTEGER NOT NULL,
    	name VARCHAR(50) NOT NULL,
    	birthday DATE,
    	email VARCHAR(100)
    );
    ```

2. Let's add 50 data to the employee table we created using the 'Mockaroo' service.

    ```
    insert into employee (id, name, birthday, email) values (1, 'Ferd', '1951/10/14', 'fivankov0@a8.net');
    insert into employee (id, name, birthday, email) values (2, 'Devy', '1971/03/28', 'dgambie1@nyu.edu');
    insert into employee (id, name, birthday, email) values (3, 'Lucho', '1964/10/11', 'lfoggo2@homestead.com');
    insert into employee (id, name, birthday, email) values (4, 'Aili', '1989/02/23', 'amertin3@opera.com');
    insert into employee (id, name, birthday, email) values (5, 'Lynnet', '1943/10/06', 'lsuggate4@linkedin.com');
    insert into employee (id, name, birthday, email) values (6, 'Bidget', '1964/05/23', 'bventham5@unblog.fr');
    insert into employee (id, name, birthday, email) values (7, 'Falito', '1953/03/12', 'fgaffney6@smugmug.com');
    insert into employee (id, name, birthday, email) values (8, 'Chrissie', '1978/11/10', 'cantonescu7@wufoo.com');
    insert into employee (id, name, birthday, email) values (9, 'Sosanna', '1985/03/16', 'sphilippart8@networksolutions.com');
    insert into employee (id, name, birthday, email) values (10, 'Ira', '1968/09/18', 'iairs9@wired.com');
    insert into employee (id, name, birthday, email) values (11, 'Abba', '1981/08/08', 'acranstonea@dagondesign.com');
    insert into employee (id, name, birthday, email) values (12, 'Frankie', '1965/12/05', 'fcarhartb@earthlink.net');
    insert into employee (id, name, birthday, email) values (13, 'Stephenie', '1987/01/13', 'seggintonc@wp.com');
    insert into employee (id, name, birthday, email) values (14, 'Evanne', '1985/12/26', 'ecalcutd@lycos.com');
    insert into employee (id, name, birthday, email) values (15, 'Jerrilee', '1959/08/02', 'jhegele@example.com');
    insert into employee (id, name, birthday, email) values (16, 'Kirbie', '1961/10/22', 'kchmarnyf@nsw.gov.au');
    insert into employee (id, name, birthday, email) values (17, 'Amitie', '1943/02/12', null);
    insert into employee (id, name, birthday, email) values (18, 'Ingamar', '1990/03/02', 'ihurdidgeh@cam.ac.uk');
    insert into employee (id, name, birthday, email) values (19, 'Dedra', '1981/08/15', null);
    insert into employee (id, name, birthday, email) values (20, 'Riki', '1965/12/29', 'rtuplinj@loc.gov');
    insert into employee (id, name, birthday, email) values (21, 'Dukey', '1961/07/24', 'djouhank@a8.net');
    insert into employee (id, name, birthday, email) values (22, 'Aurthur', null, null);
    insert into employee (id, name, birthday, email) values (23, 'Jobey', null, 'jbriskeym@lulu.com');
    insert into employee (id, name, birthday, email) values (24, 'Dayna', '1994/10/05', 'dgidneyn@elpais.com');
    insert into employee (id, name, birthday, email) values (25, 'Sinclare', null, 'schampnesso@opera.com');
    insert into employee (id, name, birthday, email) values (26, 'Hayward', '1954/08/08', 'hmcartanp@eventbrite.com');
    insert into employee (id, name, birthday, email) values (27, 'Amandy', '1984/09/10', 'acarmichaelq@wsj.com');
    insert into employee (id, name, birthday, email) values (28, 'Chen', null, 'cdurramr@smh.com.au');
    insert into employee (id, name, birthday, email) values (29, 'Sanford', '1959/08/04', 'stordiffes@yelp.com');
    insert into employee (id, name, birthday, email) values (30, 'Lazarus', '1983/01/16', 'lguthrumt@123-reg.co.uk');
    insert into employee (id, name, birthday, email) values (31, 'Neille', '2003/03/14', 'ncathericku@biglobe.ne.jp');
    insert into employee (id, name, birthday, email) values (32, 'Tish', '1968/10/19', 'tpendleberryv@typepad.com');
    insert into employee (id, name, birthday, email) values (33, 'Angeline', '1941/11/06', 'abiermatowiczw@google.cn');
    insert into employee (id, name, birthday, email) values (34, 'Taber', null, null);
    insert into employee (id, name, birthday, email) values (35, 'Robinett', null, 'rklouzy@accuweather.com');
    insert into employee (id, name, birthday, email) values (36, 'Carol-jean', null, 'candraschz@paypal.com');
    insert into employee (id, name, birthday, email) values (37, 'Donnell', '1996/03/30', 'dcubbit10@nytimes.com');
    insert into employee (id, name, birthday, email) values (38, 'Milissent', '2000/02/18', 'mmacpharlain11@opera.com');
    insert into employee (id, name, birthday, email) values (39, 'Kylen', '1988/01/06', 'kmckeeman12@amazon.com');
    insert into employee (id, name, birthday, email) values (40, 'Hedy', null, 'hhouseman13@oracle.com');
    insert into employee (id, name, birthday, email) values (41, 'Jayson', '1995/11/17', 'jhumerstone14@indiatimes.com');
    insert into employee (id, name, birthday, email) values (42, 'Karel', '2003/04/21', 'kjesse15@plala.or.jp');
    insert into employee (id, name, birthday, email) values (43, 'Brenden', '1976/07/05', 'bturgoose16@archive.org');
    insert into employee (id, name, birthday, email) values (44, 'Christean', '1975/02/17', 'clacer17@cbslocal.com');
    insert into employee (id, name, birthday, email) values (45, 'Hermia', '1949/07/06', 'hgittens18@bigcartel.com');
    insert into employee (id, name, birthday, email) values (46, 'Noby', '1951/12/09', 'nheifer19@ezinearticles.com');
    insert into employee (id, name, birthday, email) values (47, 'Lance', '1968/09/16', 'lsmeall1a@dropbox.com');
    insert into employee (id, name, birthday, email) values (48, 'Cynthy', '1976/12/07', 'ccullerne1b@wordpress.com');
    insert into employee (id, name, birthday, email) values (49, 'Leonora', '1984/01/14', 'lgandrich1c@businessweek.com');
    insert into employee (id, name, birthday, email) values (50, 'Patience', '2004/02/25', 'pscrinage1d@ed.gov');
    
    ```

3. Let's perform 5 UPDATE operations for each column that will update the other columns.

    ```
    UPDATE employee
    SET name = 'Okan'
    birthday = '2001-10-18'
    WHERE id = 10;
    
    UPDATE employee
    SET birthday = '1982-01-14'
    WHERE id = 24;
    
    UPDATE employee
    SET email = 'empty@gmail.com'
    WHERE email LIKE '%@ed.gov';
    
    UPDATE employee
    SET name = 'David'
    WHERE name = 'Riki';
    
    UPDATE employee
    SET name = 'Fincher'
    WHERE id BETWEEN 15 AND 20 ;
    ```
4. Let's perform 5 DELETE operations that will delete the relevant row for each column.

    ```
    DELETE FROM employee
    WHERE name LIKE 'F%';
    
    DELETE FROM employee
    WHERE id = 26;
    
    DELETE FROM employee
    WHERE email IS NULL;
    
    DELETE FROM employee
    WHERE birthday IS NULL;
    
    DELETE FROM employee
    WHERE birthday > '2000-01-01';
    ```
