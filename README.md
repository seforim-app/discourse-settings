# Instructions
* Run ```sudo docker exec -t -i app sh -c "cd /var/www/discourse/ && rake site_settings:export > settings.yml" && sudo docker cp app:/var/www/discourse/settings.yml settings.yml``` in this directory on the machine running the docker image to update ```settings.yml```

* # **Important:** Don't forget to clear any secrets before committing!
