# Habit Tracker for Obsidian

Welcome to the Habit Tracker repository for Obsidian! This project provides a comprehensive system for tracking your habits using the Obsidian markdown note-taking application. It leverages plugins like obsidian-tracker and templater-obsidian to offer an automated and customizable experience.

# Features 

- customizable Habit Dashboard: A centralized dashboard to view your habit data.
- Habit Tracking Templates: Predefined templates to streamline habit entries.
- Automated Tracking: Utilizes the obsidian-tracker plugin to visualize and analyze data.
- Flexible and Extendable: Easily modify templates or add new ones to suit your needs.

# Contents

## Files and Folders

- dashboard.md: The main habit tracking dashboard.
- .obsidian/: Configuration files for Obsidian.
- plugins/obsidian-tracker/: Plugin for habit tracking and data visualization.
- plugins/templater-obsidian/: Plugin for templating habit entries.
- templates/habit template.md: A markdown template to quickly log habits.

# Requirements

1. Obsidian: Install Obsidian from obsidian.md.
2. trackerand templater plugins.

These plugins can be installed from the Obsidian Community Plugins section.

# Installation

1. Clone or Download the Repository or download it as a zip file.
2. open the habbit tracker as a vault in Obsidian.

# Usage

You can open a new file and insert a template in it with Templater.
When you do that, the file will be automatically renamed to the current date and time.

Switch to viewing the note in reading mode and then just check the habits you want to mark as done by ticking the checkbox.

Use the dashboard to check for simple done or not done stats on your habits for last 24 hours, last 7 days, last month, 3 months, 6 month or year.

## Adding new habits

This largely depends on how you work. I usually let each habit have its own template. For me, adding multiple habits in one templates will record the rest of the habits that I haven't ticked as a not done habit anyways.
In other words, having a multi habit template will record multi habit entries and depending on your setup that might not work for you.

Either way, you have to modify the template and add a new habbit by just copying the line of the test habit, pasting it in the line below it and rename the habit.

You then need to go to the dash board and edit it.
Copy the code for the time ranges and paste it after the 1 year code block.
Then, change the search target in the newly pasted text into the new added habit name and that's it.

# Final note

This is just a quick way to get started.
This a simple habit tracking vault. You can improve on it some more if you like. Such as by adding graphs or include more stats.

It's something that didn't take me a long time to build, so there might be a few bugs here and there.