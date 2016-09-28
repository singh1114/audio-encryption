#audio-encryption


A simple and elegant way for peer-to-peer communication through audio encryption and decryption.


##Idea


Instead of the usual hashing techniques converting text into some gibberish, here we employ a similar method except we do the same the thing to audio data.


* Helps in easy transmission and sharing of data through short distances without using the internet (using devices which can decrypt the data)
* Compatibility of above method in any OS due to use .wav files
* Application of FFTs over primes becomes harder to decrypt
* This is a task-specific encryption/decryption since it cannot be used in all instances, but will surely come to use somewhere, sometime

# For the website

use commands.

mysql -u root -p
Enter password
create database <databasename>
eg : create database encryption;

cd audio_encrytption/website/audio_encrytption/audio_encrytption
vim settings.py

Now find the term Database and put all the information about your Database as suggested.

cd ..

python manage.py makemigrations
python manage.py migrate

python manage.py runserver
