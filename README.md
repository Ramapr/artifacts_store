# artifacts_store

intro 


# getting start 

plan:

- install service
- install local library & setup work with service 
- done 

## service

```
docker compose up -d 
```

## local 

```
pip install "dvc[s3]"
```


## guide
first of all 

```
$ dvc init
# fill dvc config file 
```

```
$ dvc add dir_name/dataset_file.csv 
$ dvc push
on remote 
$ dvc pull 
```

