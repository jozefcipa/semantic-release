> As much as I love JS it is sometimes necessary to use a different language. Since I'm coming from this lovely JS world and like semantic-project I decided to fork it and slightly edit it so it can be used for projects without npm

This is a forked version of the official [semantic-release](https://google.com) package. 

This package also generates `CHANGELOG.md` file.

### How to use
```

  # ~/semantic-release
  git clone git@github.com:jozefcipa/semantic-release.git
  
  cd ~/your-project
  ~/semantic-release/bin/semantic-release.js
```

This will create a new tag, generate changelog file, create a new commit in format `chore(release): vX.Y.Z [skip ci]` and will push it all to the remote repository.
