# PostmanQuest4

#Run only Utilities repo of the collection (--folder argument)
#Tree times will the folder is run (-n argument)
#Two generated reports in html and json Format (-r argument)

newman run https://www.getpostman.com/collections/9a5bee6affb7eaf7b3e7 -n 3 --folder Utilities -r html,json
