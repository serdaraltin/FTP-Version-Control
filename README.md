# Version-Control
 
It checks the file in the specified directory at specified intervals and,if the file integrity is ensured,extracts the file from the archive and transfers it to the specified directory.
Meanwhile, all control operations are provided and optionally, backups of each version are taken.
After the update and backup processes are completed, the specified API is triggered. (here used an API that triggers the aws lambda function)
