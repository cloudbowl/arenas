Cloud Bowl Arenas
-----------------

[Learn about building a microservice for battle](INSTRUCTIONS.md)

After deploying your microservice, you can send a pull request to be added to an arena by editing its json file to include an object in the `players` list like:
```
{"name": "Foo Bar", "url": "https://asdf.app", "github_user": "foo"}
```

If you do not specify the `github_user` a random avatar will be used.

Available arenas:

| Arena | Description | |
|-------|-------------|-|
| test  | All of [the Cloud Bowl samples][cloudbowl-samples] | [view][test-view] - [join][test-edit] |
| beginner | For those just getting started | [view][beginner-view] - [join][beginner-edit] |
| googlers | Googlers | [view][googlers-view] - [join][googlers-edit] |
| wtf | Winter Tech Forum | [view][wtf-view] - [join][wtf-edit] |

[cloudbowl-samples]: https://github.com/GoogleCloudPlatform/cloudbowl-microservice-game/tree/master/samples
[test-edit]: https://github.com/cloudbowl/arenas/edit/master/test.json
[test-view]: https://cloudbowl.gcplab.me/test
[beginner-edit]: https://github.com/cloudbowl/arenas/edit/master/beginner.json
[beginner-view]: https://cloudbowl.gcplab.me/beginner
[googlers-edit]: https://github.com/cloudbowl/arenas/edit/master/googlers.json
[googlers-view]: https://cloudbowl.gcplab.me/googlers
[wtf-edit]: https://github.com/cloudbowl/arenas/edit/master/wtf.json
[wtf-view]: https://cloudbowl.gcplab.me/wtf
