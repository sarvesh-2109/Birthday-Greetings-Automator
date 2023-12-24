# Birthday Email Automator

This Python script automates the process of sending birthday emails to friends or contacts based on the data provided in a CSV file (`birthdays.csv`). The program reads the CSV file to create a dictionary of birthdays, and if it's someone's birthday today, it selects a random letter template and sends a personalized birthday email.

## Output


https://github.com/sarvesh-2109/Birthday-Greetings-Automator/assets/113255836/8e996d08-9010-4228-afbf-bafd731c1dbc




## How It Works

1. **Reading Birthday Data**: The script reads birthday data from the `birthdays.csv` file and creates a dictionary (`birthday_dict`) with the format `(month, day)` as keys.

2. **Checking for Birthdays**: It checks if today's date matches any of the birthdays in the dictionary.

3. **Sending Birthday Email**: If it's someone's birthday, the script selects a random letter template, replaces the placeholder "[NAME]" with the birthday person's name, and sends the email using the SMTP protocol.

## Usage

1. Replace `"your_email"` with your email address in the `MY_EMAIL` variable.
2. Replace `"your_password"` with your mail app password in the `PASSWORD` variable.

## Letter Templates

You can customize the letter templates by editing the files in the `letter_templates` folder. The script randomly selects one of these templates for each birthday.

## Automate with PythonAnywhere

To automate this script, you can upload it to the cloud using [PythonAnywhere](https://www.pythonanywhere.com/). Create a scheduled task that runs this script daily to check for birthdays and send emails automatically.

**Note**: Ensure that your email provider allows access to less secure apps, or use an app-specific password.

Feel free to contribute and improve this birthday email automator! 🎉📧
