Cloud Bowl Arenas
-----------------

[Learn about building a microservice for battle](https://codelabs.developers.google.com/codelabs/battle-peach/index.html)

After deploying your microservice, you can send a pull request to be added to an arena by editing its json file to includean object in the `players` list like:
```
{"name": "Foo Bar", "url": "https://asdf.app", "github_user": "foo"}
```

If you do not specify the `github_user` a random avatar will be used.

Available arenas:

| Arena | Description | |
|-------|-------------|-|
| test  | All of [the Cloud Bowl samples](https://github.com/GoogleCloudPlatform/cloudbowl-microservice-game/tree/master/samples) | [view](http://cloudbowl.gcplab.me/test) - [join](https://github.com/cloudbowl/arenas/edit/master/test.json) |
| beginner | For those just getting started | [view](http://cloudbowl.gcplab.me/beginner) - [join](https://github.com/cloudbowl/arenas/edit/master/beginner.json) |
