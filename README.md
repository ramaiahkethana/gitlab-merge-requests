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
2. Create ```projects``` key in local storage and place stringified data in it. Use online tools to stringify the data. Make sure that data is in double quotes.

### Gitlab access token placing in local storage
1. Create a access token from gitlab with api access
2. Create a key ```GITLAB_PRIVATE_TOKEN``` in local storage and place the above generated token from gitlab

**Your page will be ready after placing two keys in local stoarge. Refresh the page and do the merge requests.**

![local stoarge setup](https://github.com/ramaiahkethana/gitlab-merge-requests/blob/master/local_storage_setup.png?raw=true "local stoarge setup")
