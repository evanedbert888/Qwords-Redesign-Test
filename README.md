# Qwords-Redesign-Test
Redesigning the landing page of Qwords / Still in progress

To all people who visit this little project of mine, welcome and thank you for your time. This project is built to redesign the landing page of Qwords website using the laravel framework Ver.9.0.

In the process of redesigning the website, there were several factors considered for project. One of them is the sense of familiarity by the users. Most users will feel comfortable by navigating the website after several attempts. In that regard, rather than remaking the whole design of the website, I chose to restructure the placement of content including modifying some of them. Moreover, there were several parts that needs to be added in terms of responsiveness. For instance, adding carousel for the testimonials or small navigation bar to traverse between the starter and favorite packages of hosting service.

To do so, I have taken the liberty of using the complete source code and assets of Qwords landing page as the template. Analyzing the source code of the original landing page, there is a lot of duplication of lines regarding the html. Thus, using the features of blade from laravel, I managed to simplify them. Unfortunately, I could not finish this project due to my carelessness.

Still, I would like to explain my project and the things I have done. First of all, to run this project, Mysql from Xampp will be needed to create the database "qwords_test". The name of the database can be checked in the env file. Next, every table used for this project has been provided including the seeders. So, please run "php artisan migrate --seed" to prepare the database.

Once the database is ready, run "php artisan serve" in the terminal to run the whole project. The link for this project is "http://127.0.0.1:8000/qwords". The view of the landing page might be similar to the original one but I have modified several of them. For instance, the navbar which is still incomplete, the testimonials lacking the carousel for responsiveness and a little navigation bar to showcase the four hostings services.

As for the files, you can check at
