# Изучение DevOps

- Автор: [Олег Сердюков](https://github.com/ctrld)
- Источник: [статья в блоге](http://ctrld.me/blog/2015/08/31/learning-devops/)

При изучении темы DevOps возникает множество вопросов, на многие из которых уже даны ответы. Поэтому для начала стоит прочитать несколько книг и попрактиковаться с различными технологиями и инструментами.

Попробую дать свои рекомендации:

- какие книги стоит прочитать чтобы стать хорошим опсом (начальные/среднего уровня/хай левел)
- какие книги стоит почитать чтобы понять что такое DevOps

Рекомендую поработать с Docker (не все книги из приведённых я смотрел):

- [The Docker Book: Containerization is the new virtualization](http://www.amazon.com/Docker-Book-Containerization-new-virtualization-ebook/dp/B00LRROTI4/)
- [Docker: Up & Running](http://www.amazon.com/Docker-Up-Running-Karl-Matthias/dp/1491917571/)
- [Learning Docker](http://www.amazon.com/Learning-Docker-Pethuru-Raj/dp/1784397938/)

Поработать с облачными сервисами:

- DigitalOcean (потому что дёшево и предсказуемо по цене), [мой рефлинк](https://www.digitalocean.com/?refcode=ee03d022570e)
- Amazon AWS, новым клиентам на год даётся минимальный набор сервисов бесплатно, но стоит очень серьёзно контролировать счёт, выставляя billing alarm'ы и трепетно относится к API ключам

Попробовать Vagrant:

- [Vagrant: Up and Running](http://www.amazon.com/Vagrant-Up-Running-Mitchell-Hashimoto-ebook/dp/B00D3VH4IO/)
- [Vagrant Virtual Development Environment Cookbook](http://www.amazon.com/Vagrant-Virtual-Development-Environment-Cookbook/dp/1784393746/)
- [Pro Vagrant](http://www.amazon.com/Pro-Vagrant-Wlodzimierz-Gajda/dp/1484200748/)

Прочитать приятную книгу

- [The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win](http://www.amazon.com/Phoenix-Project-Helping-Business-ebook/dp/B00AZRBLHO/)

Посмотреть на системы Configuration Management, начать с Ansible:

- [Ansible for DevOps](https://leanpub.com/ansible-for-devops)
- [Ansible for AWS](https://leanpub.com/ansible-for-aws)
- [Ansible: Up and Running ](http://www.amazon.com/Ansible-Up-Running-Lorin-Hochstein-ebook/dp/B00WVH5SY8/)
- [Ansible Playbook Essentials](http://www.amazon.com/Ansible-Playbook-Essentials-Gourav-Shah-ebook/dp/B00Z6VSXPW/)
- [Learning Ansible](http://www.amazon.com/Learning-Ansible-Madhurranjan-Mohaan-ebook/dp/B00QAMMHLM/)

Дальше - SaltStack, Chef или Puppet, а лучше всё вместе.

Chef:

- [Chef Infrastructure Automation Cookbook](http://www.amazon.com/Chef-Infrastructure-Automation-Cookbook-Second-ebook/dp/B00YJ64GEW/)
- [Chef Essentials](http://www.amazon.com/Chef-Essentials-John-Ewart-ebook/dp/B00NXWI19O/)
- [Learning Chef: A Guide to Configuration Management and Automation](http://www.amazon.com/Learning-Chef-Configuration-Management-Automation/dp/1491944935/)

Почитать про Agile, Scrum, Kanban:

- [Essential Scrum: A Practical Guide to the Most Popular Agile Process](http://www.amazon.com/Essential-Scrum-Practical-Addison-Wesley-Signature-ebook/dp/B008NAKA5O/)
- [Scrum: a Breathtakingly Brief and Agile Introduction](http://www.amazon.com/Scrum-Breathtakingly-Brief-Agile-Introduction/dp/193796504X/)

Посмотреть теорию по тестированию, Continuous Deployment и остальному:

- [Continuous Delivery: Reliable Software Releases through Build, Test, and Deployment Automation](http://www.amazon.com/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912/). Это классика.
- [Agile Testing: A Practical Guide for Testers and Agile Teams](http://www.amazon.com/Agile-Testing-Practical-Guide-Testers/dp/0321534468/)
- [Release It!: Design and Deploy Production-Ready Software](http://www.amazon.com/Release-Production-Ready-Software-Pragmatic-Programmers/dp/0978739213/)
- [The Practice of Cloud System Administration: Designing and Operating Large Distributed Systems](http://www.amazon.com/The-Practice-Cloud-System-Administration/dp/032194318X/) - автора представлять не нужно
- [The Visible Ops Handbook: Implementing ITIL in 4 Practical and Auditable Steps](http://www.amazon.com/Visible-Ops-Handbook-Implementing-Practical/dp/0975568612/)
- [Web Operations: Keeping the Data on Time](http://www.amazon.com/Web-Operations-Keeping-Data-Time/dp/1449377440)

В качестве одной из методологий посмотреть на Immutable Server (к своему стыду я целый год не удосуживался прочитать описание, и применял термин не совсем правильно):

- [ImmutableServer](http://martinfowler.com/bliki/ImmutableServer.html)
- [Trash Your Servers and Burn Your Code: Immutable Infrastructure and Disposable Components](http://chadfowler.com/blog/2013/06/23/immutable-deployments/)

И всё время практиковаться в автоматизации.

Буду благодарен за добавления, поправки и ваши мысли по поводу DevOps.

## TODO

- разбить книги и инструменты по уровням начальный/средний/хай левел