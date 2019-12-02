# Squirrel Tracker

# What is it?
This is a semester project dedicated for IEOR 4501 Tools for Analytics. Our team, in this project, made use of Django framework to build a web application for squirrels tracking around Central Park in NYC.

# Data Source



# Key Features 

Management Commands + Views

# Management Commands

Import: A command that can be used to import the data from the 2018 census file (in CSV format). The file path should be specified at the command line after the name of the management command.

python manage.py import_squirrel_data /path/to/file.csv

Export: A command that can be used to export the data in CSV format. The file path should be specified at the command line after the name of the management command.

python manage.py export_squirrel_data /path/to/file.csv

# Views

1. A view that shows a map that displays the location of the squirrel sightings on an openstreets map

2. A view that lists all squirrel sightings with links to edit and add sightings

3. A view to update, create and delete a sighting

4. A view with general statistics about the sightings

# Dependencies


# Documentation

The official description for this project is Squirrel Tracker.

# Background

Eccentric billionaire Joffrey Hosencratz just purchased the web development company you work for. You’ve met him once in an elevator and he was impressed with your skill in developing web applications with the Django framework. He also relayed that his most recent trip to Sedona, AZ has left him in a bit of trouble. See, he fancies the show Rick and Morty and a particular scene coupled with a traumatic childhood squirrel experience and a bad crystal bath experience in Sedona as left him wanting.

He would like to start keeping track of all the known squirrels and plans to start with Central Park. He’s asked you to build an application that can import the 2018 Central Park Squirrel Census data and allow his team to add, update, and delete squirrel data.

# Discussion and Development

Most development discussion is taking place on github in this repo.

# Contributing to Squirrel Tracker

Any contributions, bug reports, bug fixes, documentation improvements, enhancements to make this project better are warmly welcomed.

# Contributors

Group Name: Ninja Turtles

Section Number: 02

Group Member: Jiahao Zhi, Zhenhao Zhang

UNIs: [jz3161, zz2695]
