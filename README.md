# Employee-Database-Management-System-with-PostgreSQL

### Description:
The new television "REYDI" started its activity a month ago on the initiative
of businessmen in collaboration with young IT programmers named Merey and Adilya. If you combine their names (meREY + aDIlya), you will get the name of television. Now television maintains its data manually in papers. An organization consists of 44 employees, who are divided by departments, such as administration, media, the department of release and analysis and so on. The administration department concludes contracts with shippers, who are providing to organization products(movies) for special prices. Also, this department pays salaries to employees and works on jurisprudence. A director manages television, signs contracts, documents and has own secretary. The secretary helps director with answering calls, taking messages and handling correspondence, maintaining diaries and arranging appointments, typing, preparing and collating reports. A workers of media department responsible for the equipment that projects movies onto a screen, editing recorded raw material into a finished product, developing concepts and layouts for
project illustrations, planning, coordinating, and revising material for publication. As each department has a principal, media is controlled by head producer and subhead. A department of economic support (worker management) consists cleaners, drivers, mechanic, locksmith and fitter, who are in charge of office. They are clean the room, inspect and repair machinery, responsible for security systems and mechanical systems. A technical department has engineers, who are overseen the technical problems. For example, they oversee the installation and commissioning of new equipment, improve energy efficiency, controls the video equipment, configure and test operating systems. A department of release and analysis works directly with airtime. Its employees control all sounds, oversee network connection, controls video broadcast and responsible for broadcasting. To assist in storing all information about employees, Merey and Adilya, as programmers wants to provide an environment for "REYDI" that is convenient and efficient to use in retrieving and storing database information. So, in general the advantages of database are fast accessing of data, multiple users access the data at the same time and providing security of data. However, for the television it can be helpful in the following cases: storing the information about employees, generating receipt and other balance records, accessing information of the workers, updating them, making requires knowing about their projects and so on. Figure 1 indicates logo
our organization.

### What is the purpose of the database? Why is it needed? What should it do?
The purpose of our database on the television «REYDI» is to develop an efficient project management system to track and control activities for employees. The database is typically designed so that it is easy to store and access information. The developed system can assist director in tracking and control of his workers and their projects in a real‐time.

### Who are the users and what are their information needs?
There are multiple users for this system defined by their role. The main users are director and administration department of television organization. A job of the director is to add or dismiss the employee in the system. Using this functionality, the director accesses the list of accepted workers and controls their works. The list of employees can be filtered by first name, last name, gender, job, salary, hire date and quit date.

###What are the problems that the system should solve?
We have decided to create a simple database management system for new television. The ways that database improve our life: the ability to test before making changes without disturbing the persistent data; enabling data to be read as fast as possible; the ability to get instant insights into workers and TV shows; some queries grab individual pieces of data; the last one is that more and more data will be analyzed in real time.

### What input data is available to the database?
The id is the employee ID that links the permanent information to the employee’s entry in the database. Each employee has first name, last name, gender, job and own salary. Hire date and quit date describes whether the employee has left the work or is a currently attending worker. Job name describes which job the employee is pursuing secretary, video maker, graphic designer, driver, cleaner, head engineer and so on. Director_id, admin_id, media_id, WM_id, tech_id, R_A_id and comm_id all represent codes needed by the organization to describe the employee’s job position. Work_schedule lists the number of hours the employee works weekly. A shipper, who provides to organization products(movies) has id, name of company, name of product, price for this product, quality and dubbing. A table “work” stores all information about employees, their work description and deadline for their works.

### What kind of information should be stored in the database?
The database will store all the pertinent information about employees, starting from director, including people from a lot of departments like administration, media, worker management, technical management, commercial service and department of release and analysis.
3
Since it is television database, there will be shippers from whose TV programmes will be purchased and of course information about this programmes.

### Business rules:
• Employee is managed by Director. (1:1)

• Director collaborates with Shippers. (1:M)

• Administration makes purchase Shipper’s products. (1:M)

• Employee contains administration, worker management, media, commercial service, department of release and analysis and technical management. (1:1)

•Work has information of administration, worker management, media, commercial service, department of release and analysis and technical management. (1:1)

### ER Diagram
<img width="884" alt="Снимок экрана 2022-04-20 в 16 49 40" src="https://user-images.githubusercontent.com/77274898/164215166-5cf3c5d0-165a-4bf0-874f-a2caececf793.png">
