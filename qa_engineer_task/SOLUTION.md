### Task-1

1. There is a sample project https://github.com/dataengi/crm-seed with documentation and ready to deploy using docker. Try
run it using "Try in PWD" in cloud or locally according to instruction "Running in presentation mode".

- git clone https://github.com/dataengi/crm-seed.git 
- docker-compose up
- listening on localhost port 80

alternate in home
- install Docker for Windows
- click Tre in PWD button
- Add new instance
- git clone https://github.com/dataengi/crm-seed.git
- docker-compose up
- click 80 button


2. Read project general documentation https://github.com/dataengi/crm-seed/wiki

    What is CRM?
    Server Application Architecture
    Users Module Design
    Contacts Module Design


3. Login on web interface with default credentials

- email: admin
- password: admin


### Task-2

1. Write user story for Customer contact add according to Agile best practice 
	Як Менеджер компанії, я хочу мати можливість підтягувати переписку з клієнтами зі своєї робочої електронної скриньки

2. Write 2 use cases for Customer contact add according to Agile best practice

2.1. 
- use case title - Manager company add new contact
- goal - Create new contact
- actor/user - Manager company/Manager, system CRM
- preconditions - Log in CRM
- standard path or main success scenario 
1. Go to Contacts tab
2. Click button +Add contact
3. Fill out New Contact form Name, Email (Main),Phone (Main). It's required fields. 
4. Click the Submit button
5. After show pop-up window "Create contact"
- post conditions: on Contacts tab show new contact 

2.2.
- use case title -  Manager company edit contact (add Company)
- goal - Edit contact
- actor/user - Manager company/Manager, system CRM
- preconditions - Log in CRM, go to Contacts tab
- standard path or main success scenario 
1. Click on a contact's name
2. In the bottom right corner, click Edit.
3. Fill Company
4. Click the Save button
5. After show pop-up window "Update contact"
- alternate paths
1. Near necessary Contact click on Edit button.
2. Fill Company
3. Click the Save button
4. After show pop-up window "Update contact"
- post conditions: on Contacts tab show update contact

3. Write 3 requirements for Customer contact add
- 3.1. Значення в полі Email не повинно розпочинатися із порожнього символа (пропуску). Повинно містити знак @, і доменне імя
- 3.2. Значення в полі Phone не повинно розпочинатися із порожнього символа, може містити лише цифри, дожиною 10-12 символів
- 3.3. Значення в полі Name може містити будь-який набір символів довжиною до 50 симовлів
