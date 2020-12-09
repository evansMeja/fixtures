# Step 1


## Dumping the data

./manage.py loaddata user.json



# step 2

## loading the data

./manage.py dumpdata auth.user --indent 2 > user.json
