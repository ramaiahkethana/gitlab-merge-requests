# Gitlab Merge Requests
Create merge requests for multiple branches at same time using gitlab rest api

## Steps for using
First download this html locally and open it in browser.

### Projects data placing in local storage
1. Take a projects variable like as below and stringify it. You can find name and project id in project settings
```json
[
    {
        "name": "sample-project",
        "value": 1234
    },
    {
        "name": "sample-project2",
        "value": 1235
    }
]
```
2. Create ```projects``` variable in local storage and place above stringified data in it.

### Gitlab access token placing in local storage
1. Create a access token from gitlab with api access
2. Create a variable ```GITLAB_ACCESS_TOKEN``` in local storage and place the above generated token from gitlab
