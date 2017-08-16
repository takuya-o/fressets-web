fressets-web
============

[![wercker status](https://app.wercker.com/status/0fe49cb40aaef9c748fc99a0d9cd797d/m/ "wercker status")](https://app.wercker.com/project/byKey/0fe49cb40aaef9c748fc99a0d9cd797d)

Fressets, Inc. official website's source code repository.



Setup
-----

```
$ npm install
$ npm install --global gulp-cli
```



Debug
--------

```
$ gulp start
```

Now, you can review the current contents by visiting http://localhost:8080/.
Once you modify the source code, the contents will be automatically rebuild and you may see the new site shortly.

If you want only to build, execute

```
$ gulp dist
```



Upload (Publish)
----------------

When `master` or `staging` branch has a new commit, Wecker will automatically detect it and build.
Then the new contents will be uploaded to Amazon S3 and be published.



