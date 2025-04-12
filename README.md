# patterns1_singleton
Just a general review about GoF pattern designs


Singleton ensures a class has only one instance, and provide a global access to it

![image](https://github.com/user-attachments/assets/ce97d64c-5db0-4605-9134-21d36f67b222)

If you have a list of countries, and there is almost no posiblity of changing the name of a country, imagine that you give an instance to every user, that is an instance on memory, seo they can see something that will never change! 

![image](https://github.com/user-attachments/assets/52ed394d-e477-48f2-a04d-6a939e0fb66d)

It'd better to have an unique instance of the object of list of countries. Much better performance.
