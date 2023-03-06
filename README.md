# aws-search-at-parameter-store
Search any string at all your parameters saved at AWS Systems Manager Parameter Store with multi-account/SSO support.

## E.g.
You have 300 parameters saved in the aws parameter store at your aws account, and you want to see which ones have the string "config_max_limit", then you can run the command: ````python3 searchAtParameters.py -s config_max_limit````

### Help to use:
```
python3 searchAtParameters.py -h
```
Usage:
````
python3 searchAtParameters.py -s [STRING]
````
The script will ask you which AWS profile you want to use to run.