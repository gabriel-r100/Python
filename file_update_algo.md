# Algorithm-file-update-Python

## Project description
The task to complete is to create an algorithm that will check whether an allow list, for IP addresses, contains IP addresses from a provided remove list. 

## Open the file that contains the allow list and create an array from the provided remove list
![open-file-create-array](https://github.com/gabriel-r100/Algorithm-file-update-Python/assets/55646808/daa4c4ac-f4d5-4550-abce-c8de7892ecc2)

## Read the file contents
![read-file-contents](https://github.com/gabriel-r100/Algorithm-file-update-Python/assets/55646808/bf7b87aa-1bb9-496c-bf77-d5d449219c26)

## Convert the string into a list
![convert-string-to-list](https://github.com/gabriel-r100/Algorithm-file-update-Python/assets/55646808/ad7f99c0-3e0f-40e6-9376-5f153a896239)

## Iterate through the remove list
![iterate-remove-list](https://github.com/gabriel-r100/Algorithm-file-update-Python/assets/55646808/0e326998-7601-49a8-8f9f-f8d33c16f491)

## Remove IP addresses that are on the remove list
![remove-ip-addresses](https://github.com/gabriel-r100/Algorithm-file-update-Python/assets/55646808/8f226f76-9bc8-4cf1-b294-5094d97c1800)

## Update the file with the revised list of IP addresses 
![update-file](https://github.com/gabriel-r100/Algorithm-file-update-Python/assets/55646808/b64edcf6-7b33-4f56-92d5-42243fb3f324)

## Summary
After having completed the steps, we have removed the provided IP addresses from our allowed IP addresses. The only caveat is that it would not have removed any duplicates if they were included in the initial allowed IP addresses.
I was able to turn our file into a string, which I then turned into a list to easily iterate through the values to remove the requested IP addresses. In the end, I joined the list back into a string to update the original file.
